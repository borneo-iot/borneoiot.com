---
title: contact
---

## Contact Us {#contactus}

- [Yunnan BinaryStars Technologies, Co., Ltd.](https://www.binarystarstech.com/en)
- **TEL/WhatsApp:** (+86) 15687397605
- **Email:** contact@binarystarstech.com
- **Address:** Room 2, 34th Floor, Tower A, Kechuang Building, No. 505 Kexue Road, Wuhua District, Kunming City, Yunnan Province, China

{{< socialbuttons orientation="vertical" showTitle="true" >}}

<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.2.4/jquery.min.js"></script>
<script>
$(function(){
  $("#contactform").submit(async function(e){
    e.preventDefault();
    var $form = $(this);
    var href = $form.attr("action");
    var siteKey = $form.data("recaptchaSitekey");
    var recaptchaAction = $form.data("recaptchaAction") || "submit";

    if (siteKey) {
      if (!window.grecaptcha) {
        alert("reCAPTCHA failed to load. Please refresh the page and try again.");
        return;
      }

      try {
        var token = await new Promise(function(resolve, reject) {
          window.grecaptcha.ready(function() {
            window.grecaptcha.execute(siteKey, { action: recaptchaAction }).then(resolve, reject);
          });
        });

        $form.find('[name="g-recaptcha-response"]').val(token);
      } catch (error) {
        alert("reCAPTCHA verification failed. Please try again.");
        return;
      }
    }
    
    $.ajax({
        type: "POST",
        url: href,
        data: new FormData(this),
        dataType: "json",
        processData: false,
        contentType: false,
        success: function(response){
          if(response.status == "success"){
              window.location.href = "/contact-thankyou";
          }
          else if(response.code === 422){
            alert("Field validation failed");
            $.each(response.errors, function(key) {
              $('[name="' + key + '"]').addClass('formcarry-field-error');
            });
          }
          else{
            alert("An error occured: " + response.message);
          }
        },
        error: function(jqXHR, textStatus){
          const errorObject = jqXHR.responseJSON

          alert("Request failed, " + errorObject.title + ": " + errorObject.message);
        },
        complete: function(){
          // This will be fired after request is complete whether it's successful or not.
          // Use this block to run some code after request is complete.
        }
    });
  });
});
</script>