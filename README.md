<p>10/12/2014 13.29.25 </p>
<h1>JQuery Clock</h1>
<blockquote>
<p>Clock is a jQuery plug-in for  olorologio digital live.</p>
</blockquote>
<h3>How to get started</h3>
<blockquote>
<p>HTML Code</p>
</blockquote>
<pre><code>&lt;div class=&quot;watch&quot;&gt;&lt;/div&gt;
</code></pre>
<blockquote>
<p>use a div with a class whatever (in this case I chose watch), and include the latest version of jquery and the plug-in jquery.clock.js.</p>
</blockquote>
<pre><code>&lt;script src=&quot;jquery-1.9.1.js&quot; type=&quot;text/javascript&quot;&gt;&lt;/script&gt;

&lt;script src=&quot;jquery.clock.js&quot; type=&quot;text/javascript&quot;&gt;&lt;/script&gt;
</code></pre>
<h3>jquery.clock.js</h3>
<blockquote>
<p>At this point, to obtain the clock live:</p>
</blockquote>
<pre><code>&lt;script type=&quot;text/javascript&quot;&gt;
     $(document).ready(function(){
     $('.watch').clock({font_size:18 , color:'green'}
          );
        });
&lt;/script&gt;
</code></pre>
<blockquote>
<p>&quot;fontsize&quot; and &quot;color&quot; are respectively the pixel value and the color of the numbers of the clock that we can choose at will (in this example are 18px and green) by default are set to 22px and the color red.size&quot; and &quot;color&quot; are respectively the pixel value and the color of the numbers of the clock that we can choose at will (in this example are 18px and green) by default are set to 22px and the color red.</p>
</blockquote>
<h3>Demo</h3>
<iframe src="http://micheledefalco.altervista.org/github/clock/clock.html" width="300" height="300">
  Contenuto alternativo per i browser che non leggono gli iframe.
</iframe>
