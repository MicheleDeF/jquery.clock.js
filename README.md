# JQuery Clock

>Clock è un plug-in jquery per olorologio live

###Come iniziare

>Codice HTML

    <div class="watch"></div>



>usare un div con una classe qualunque ( in questo caso ho scelto watch ), e inserire l'ultima versione di jquery e il plug-in jquery.clock.js

    <script src="js/jquery-1.9.1.js" type="text/javascript"></script>
     
    <script src="jquery.clock.js" type="text/javascript"></script>
     
###Il Plug-in jquery.clock.js     
>A questo punto per ottenere l'orologio live:

    <script type="text/javascript">
         $(document).ready(function(){
         $('.watch').clock({font_size:18 , color:'green'}
              );
            });
    </script>
    
> "font_size" e "color" sono rispettivamente il valore in pixel e il colore dei numeri dell'orologio che possiamo scegliere a nostro piacimento ( in questo esempio sono 18px e colore verde ), di default sono impostati a 22px e colore rosso.

###Demo
 
 <iframe src="http://micheledefalco.altervista.org/github/clock/clock.html" style="border:none;">
</iframe>    


