[en](https://github.com/KC3Kai/kc3-docs/tree/master/en) / [Strategy Room](https://github.com/KC3Kai/kc3-docs/blob/master/en/Strategy_Room.md) / Player / [Screenshots](https://github.com/KC3Kai/kc3-docs/blob/master/en/Strategy_Room_-_Screenshots.md)

# Overview
Here is where you can get list of screenshots that you have made via pressing the button from KC3 Kai's panel.

The date represented in the list is in: Month Day, Year - Hours:Minutes AM/PM


**Note:** This only works for screenshots that has been uploaded to http://imgur.com

**Developers Notes:**
````javascript
    showPage :function( page ){
    KC3Database.get_screenshots(page, function(screenshots){

       $(".screenshot_list").html("");
       var ss_thumb;
       $.each(screenshots, function(i, screenshot){
           ss_thumb = $(".tab_screenshots .factory .ss_thumb").clone().appendTo(".screenshot_list");
           $("img", ss_thumb).attr("src", screenshot.imgur);
           $(".ss_date", ss_thumb).text( (new Date( screenshot.ltime*1000)).format("mmm dd, yyyy - hh:MM tt") );
                 });
           });
     }
````