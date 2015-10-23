---
ID: 4497
post_title: Free Registration Step4c
author: Olu
post_date: 2015-08-18 09:35:15
post_excerpt: ""
layout: page
permalink: >
  http://www.ecommerce.lotto-social.com/free-reg-step4c/
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
lotto_free_registration_step:
  - free-reg-step4c
---
<div class="free-registration 4c">
<div class="target_url hide">{%target_url%}</div><div class="iframe_url hide">{%iframe_url%}</div>
<div class="offer-popup hide" style="vertical-align: middle;">
<div class="whiteBg1">
<div class="offerreject1">
<p class="descriptiontext">Are you sure you want to turn down this offer? Be aware that you won‘t be able to access this offer in the future.</p>
<a class="btn btn-success btn-lg close-popup-link">BACK TO THE OFFER</a> <a class="btn btn-link btn-lg free_reg_step4c_btn1 ladda-button" data-style="expand-right">I don't want it</a>

</div>
<div class="spinner spinner4cNew hide"></div>
</div>
</div>
<div class="welcom-4c-page text-center">
<h2>{%title%}</h2>
{%body%}
<div id="LoadingDiv" class="spinner"></div>
<div id="ValidatingDiv" class="spinner" style="display: none; opacity: 0; z-index: 100000; margin-left: 100px; margin-bottom: -220px; margin-top: 100px; position: relative;"></div>
<iframe id="Payment_Iframe" style="display: none; height: 480px;" src="" width="300" height="150"> </iframe>
<a class="btn btn-link btn-lg notinterested-btn">{%linkbutton%}</a>

</div>
</div>
<div id="spinner-on" style="display: none;"></div>
<div id="spinner-off" style="display: none;"></div>
<script id="loader" src="/cms2/wp-content/themes/textlotto/js/spinner.js" type="text/javascript"></script><script>// <![CDATA[
$(document).ready(function() { $(".offer-popup").hide(); $(".notinterested-btn").click(function() { $(".offer-popup").show(); }); $(".close-popup-link").click(function() { $(".offer-popup").hide(); }); $(".free_reg_step4c_btn1").click(function() { $(".whiteBg1").css("height", "200"); $(".offerreject1").hide(); $(".spinner4cNew").show(); }); var spinner; $("#spinner-on").click(function(){ spinner = new ajaxLoader($('.welcom-4c-page'), {classOveride: 'blue-loader', bgColor: '#fff', opacity: '0.5'}); $('#ValidatingDiv').css('display', 'block').css('opacity', '0.6'); }); $("#spinner-off").click(function(){ if (spinner) spinner.remove(); $('#ValidatingDiv').css('display', 'none').css('opacity', '0'); }); });
// ]]></script>