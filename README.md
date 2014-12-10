# JQuery Clock

>Clock is a jQuery plug-in for  olorologio digital live.

###How to get started

>HTML Code

    <div class="watch"></div>



>use a div with a class whatever (in this case I chose watch), and include the latest version of jquery and the plug-in jquery.clock.js.

    <script src="jquery-1.9.1.js" type="text/javascript"></script>
     
    <script src="jquery.clock.js" type="text/javascript"></script>
     
###jquery.clock.js     
>At this point, to obtain the clock live:

    <script type="text/javascript">
         $(document).ready(function(){
         $('.watch').clock({font_size:18 , color:'green'}
              );
            });
    </script>
    
>"font_size" and "color" are respectively the pixel value and the color of the numbers of the clock that we can choose at will (in this example are 18px and green) by default are set to 22px and the color red.

###Demo

[clock.html](http://micheledefalco.altervista.org/github/clock/clock.html)



