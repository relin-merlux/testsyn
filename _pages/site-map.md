---
ID: 128
post_title: Sitemap
author: Olu
post_date: 2013-11-11 13:26:50
post_excerpt: ""
layout: page
permalink: >
  http://www.ecommerce.lotto-social.com/site-map/
published: true
---
<div class="whitePaper tc siteMapText">
  <div class="col-lg-4 col-md-4 col-sm-4 col-xs-12"> <a title="Home" href="/">Home</a><br>
    <a title="About us" href="/about-lottery-syndicates/">About us</a><br>
    <a title="FAQ" href="/lottery-syndicate-faqs/">FAQ</a><br>
    <a title="Security" href="/managed-lottery-syndicate-service-security-policy/">Security</a><br>
  </div>
  <div class="col-lg-4 col-md-4 col-sm-4 col-xs-12"> <a title="Contact us" href="/contact-syndicate-management/">Contact us</a><br>
    <a title="Promotions" href="/lottery-syndicate-promotions/">Promotions</a><br>
    <a title="Lottery results" href="/lottery-results-for-lotto-and-euromillions/">Lottery results</a><br>
    <a title="Terms &amp; Conditions" href="/terms-and-conditions-for-lottery-syndicate-service/">Terms &amp; Conditions</a><br>
  </div>
  <div class="col-lg-4 col-md-4 col-sm-4 col-xs-12"> <a title="Privacy" href="/privacy-policy-for-lottery-syndicate-members/">Privacy</a><br>
    <a title="Privacy" href="/news/">Lottery News</a><br>
    <a id="site_map_login" title="Login" href="/login/">Login</a><br>
    <a title="Service Guide" href="/lottery-syndicate-service-guide/">Service guide</a><br>
    <a title="Sitemap" href="/site-map/">Sitemap</a><br>
    <?php
    session_start();
if($_SESSION['user_session_id']!=""){
	echo '<a title="Monthly Prize Draw" href="/monthly-prize-draw/">Monthly Prize Draw</a>';
}
else if($_SESSION['user_session_id']==""){
	echo '<a title="Monthly Prize Draw" href="/monthly-prize-draw/">Monthly Prize Draw</a>';
}    
    ?>
    <br>
  </div>
</div>
[footer_images_reg]