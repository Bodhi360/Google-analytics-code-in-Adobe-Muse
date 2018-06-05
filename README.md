# Google-analytics-code-in-Adobe-Muse
                                   How to insert Google analytics code in Adobe Muse<br>
Click Adobe Muse and open the page you want to edit in Design mode. Choose Page > Page Properties and paste the code in the Metadata section of the Page Properties window. Or simply paste the code anywhere on the page to embed it. The tracking script won’t affect the page’s layout.

 Add the tracking code to a master page to quickly add tracking to all of the related pages. Choose page properties form the page menu and paste the tracking code in to the meta tag Section on the page.

<!-- Google Analytics -->
<script><br>
(function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){<br>
(i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),<br>
m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)<br>
})(window,document,'script','https://www.google-analytics.com/analytics.js','ga');<br>

ga('create', 'UA-XXXXX-Y', 'auto');<br>
ga('send', 'pageview');<br>
</script>
<!-- End Google Analytics -->

•‘UA-xxxxx-y’ should be replaced With "Property Id" Also called the
<br>('tracking Id') of the google analytics property


<img src="https://github.com/Bodhi360/Google-analytics-code-in-Adobe-Muse/blob/master/Muse_meta%20tag.png">
<a href="http://www.bodhi360.cloud/">Bodhi360</a>
