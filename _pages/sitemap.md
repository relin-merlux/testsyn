---
ID: 740
post_title: Sitemap
author: olu
post_date: 2014-06-06 09:21:19
post_excerpt: ""
layout: page
permalink: >
  http://www.ecommerce.lotto-social.com/sitemap/
published: true
slide_template:
  - default
vc_teaser:
  - 'a:2:{s:4:"data";s:115:"[{"name":"title","link":"post"},{"name":"image","image":"featured","link":"none"},{"name":"text","mode":"excerpt"}]";s:7:"bgcolor";s:0:"";}'
ulp_version:
  - "4.9"
ulp_onload_mode:
  - default
ulp_onload_period:
  - "5"
ulp_onload_delay:
  - "0"
ulp_onload_close_delay:
  - "0"
ulp_onload_popup:
  - default
ulp_onload_popup_mobile:
  - default
ulp_onexit_mode:
  - default
ulp_onexit_period:
  - "5"
ulp_onexit_popup:
  - default
ulp_onexit_popup_mobile:
  - default
ulp_onscroll_popup:
  - default
ulp_onscroll_popup_mobile:
  - default
ulp_onscroll_mode:
  - default
ulp_onscroll_period:
  - "5"
ulp_onscroll_offset:
  - "600"
ulp_onidle_mode:
  - default
ulp_onidle_delay:
  - "30"
ulp_onidle_period:
  - "5"
ulp_onidle_popup:
  - default
ulp_onidle_popup_mobile:
  - default
lotto_reg_form:
  - 'no'
---
&lt;div class="whitePaper tc siteMapText"&gt;
&lt;div class="col-lg-4 col-md-4 col-sm-4 col-xs-12"&gt;&lt;a title="Home" href="/"&gt;Home&lt;/a&gt;
&lt;a title="About us" href="/about-lottery-syndicates/"&gt;About us&lt;/a&gt;
&lt;a title="FAQ" href="/lottery-syndicate-faqs/"&gt;FAQ&lt;/a&gt;
&lt;a title="Security" href="/managed-lottery-syndicate-service-security-policy/"&gt;Security&lt;/a&gt;&lt;/div&gt;
&lt;div class="col-lg-4 col-md-4 col-sm-4 col-xs-12"&gt;&lt;a title="Contact us" href="/contact-syndicate-management/"&gt;Contact us&lt;/a&gt;
&lt;a title="Promotions" href="/lottery-syndicate-promotions/"&gt;Promotions&lt;/a&gt;
&lt;a title="Lottery results" href="/lottery-results-for-lotto-and-euromillions/"&gt;Lottery results&lt;/a&gt;
&lt;a title="Terms &amp;amp; Conditions" href="/terms-and-conditions-for-lottery-syndicate-service/"&gt;Terms &amp;amp; Conditions&lt;/a&gt;&lt;/div&gt;
&lt;div class="col-lg-4 col-md-4 col-sm-4 col-xs-12"&gt;&lt;a title="Privacy" href="/privacy-policy-for-lottery-syndicate-members/"&gt;Privacy&lt;/a&gt;
&lt;a title="Privacy" href="/news/"&gt;Lottery News&lt;/a&gt;
&lt;a id="site_map_login" title="Login" href="/login/"&gt;Login&lt;/a&gt;
&lt;a title="Service Guide" href="/lottery-syndicate-service-guide/"&gt;Service guide&lt;/a&gt;
&lt;a title="Sitemap" href="/site-map/"&gt;Sitemap&lt;/a&gt;
<?php <br ?> session_start();
if($_SESSION['user_session_id']!=""){
echo '&lt;a title="Monthly Prize Draw" href="/monthly-prize-draw/"&gt;Monthly Prize Draw&lt;/a&gt;';
}
else if($_SESSION['user_session_id']==""){
echo '&lt;a title="Monthly Prize Draw" href="/monthly-prize-draw/"&gt;Monthly Prize Draw&lt;/a&gt;';
}
?&amp;gt;
&lt;/div&gt;
&lt;/div&gt;
[footer_images_reg]