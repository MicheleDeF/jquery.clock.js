# JQuery Clock

>Clock is a jQuery plug-in for  live analog clock, the clock is achieved without the use of images, but only with CSS


###How to get started

>HTML Code

<div id="clock"></div>



>use a div#clock and put the latest version of jquery, the plug-in jquery.clock.js and clock.css.

    <link rel="stylesheet" href="css/clock.css">
    <script src="js/jquery-x.x.x.js" type="text/javascript"></script>     
    <script src="js/jquery.clock.js" type="text/javascript"></script>
    
###jquery.clock.js    
 
>At this point, to obtain the clock live:

    <script type="text/javascript">
         $(document).ready(function(){
         $('#clock').clock();
            });
    </script>
    
>To change the color of the clock you have to make changes to the style sheet clock.css, 'border-color' of #clock to the edge of the clock, the 'background' of #clock:after the center of the clock, 'background 'of #secondi:after, #ore:after, #minuti:after, respectively, to change the color of the second hand, hour and minute.

<p data-height="268" data-theme-id="0" data-slug-hash="MYOrJq" data-default-tab="result" data-user="MicheleDeF" class='codepen'>See the Pen <a href='http://codepen.io/MicheleDeF/pen/MYOrJq/'>MYOrJq</a> by michele de falco (<a href='http://codepen.io/MicheleDeF'>@MicheleDeF</a>) on <a href='http://codepen.io'>CodePen</a>.</p>
