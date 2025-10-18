---
title: contact
---

## Contact Us

- Yunnan BinaryStars Technologies, Co., Ltd.
- **TEL/WhatsApp:** (+86) 15687397605
- **Email:** contact@binstarstech.com
- **Address:** Room 2, 34th Floor, Tower A, Kechuang Building, No. 505 Kexue Road, Wuhua District, Kunming City, Yunnan Province, China

{{< socialbuttons >}}


<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.2.4/jquery.min.js"></script>
<script>
$(function(){
  $("#contactform").submit(function(e){
    e.preventDefault();
    var href = $(this).attr("action");
    
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