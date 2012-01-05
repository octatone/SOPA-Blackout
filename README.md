SOPA-Blackout
=============
![SOPA-Blackout Screenshot](http://i.imgur.com/xmqRh.png "SOPA-Blackout Screenshot")

SOPA-Blackout is a simple blackout script that censors your site until your visitors click anywhere on the page.

Installation
============
Just copy and paste the following code into your site's html, somewhere before the closing `</body>` tag:

    <!-- SOPA Blackout -->
    <style type="text/css">#fuck-sopa-wrapper{background-color:#000;position:absolute;top:0;left:0;width:100%;height:100%;margin:0;padding:0;}#fuck-sopa-content{font-family:helvetica,verdana;background:gray;width:300px;margin:100px auto 0 auto;padding:15px;text-align:center;border:2px solid darkred;-webkit-border-radius:15px;-moz-border-radius:15px;border-radius:15px;}#fuck-sopa-content h1{margin-top:0;font-size:x-large;color:darkred;}#fuck-sopa-content a{color:#000;}</style><script>var html='<div id="fuck-sopa-wrapper">  <div id="fuck-sopa-content">    <h1>WEBSITE BLOCKED</h1>    <p>If internet blacklist legislation becomes law, this may be all that remains of this website in the future.</p>    <p>Learn more about the adverse affects SOPA and PIPA will have for you and the internet at <a href="http://americancensorship.org/">americancensorship.org</a>  </div></div>';document.write(html);var sopa_banner=document.getElementById("fuck-sopa-wrapper");
    sopa_banner.onclick=function(){sopa_banner.style.display="none"};</script>
    <!-- END SOPA BLACKOUT -->