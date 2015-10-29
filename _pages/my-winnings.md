---
ID: 4319
post_title: My Winnings
author: Olu
post_date: 2013-11-20 13:38:46
post_excerpt: ""
layout: page
permalink: >
  http://www.ecommerce.lotto-social.com/my-winnings/
published: true
bwps_enable_ssl:
  - ""
slide_template:
  - default
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
lotto_visible_to_user:
  - logged
---
<h3 class="blue"><strong>My Winnings</strong></h3>
<div class="tabbable">
<ul class="nav nav-tabs">
	<li class="active"><a class="tab1" href="#tab1" data-toggle="tab">Account Balance</a></li>
	<li><a class="tab2" href="#tab2" data-toggle="tab">Pending Claims</a></li>
	<li><a class="tab3" href="#tab3" data-toggle="tab">Paid Claims</a></li>
</ul>
<div class="tab-content banner_container">
<div id="tab1" class="tab-pane active">
<div class="col-lg-12 table-responsive">{%accountBalance%}{%Claimbtn%}

</div>
</div>
<div id="tab2" class="tab-pane">
<div class="col-lg-12 table-responsive">{%pendingClaims%}</div>
</div>
<div id="tab3" class="tab-pane">
<div class="col-lg-12 table-responsive">{%paidClaims%}</div>
</div>
</div>
</div>
<div class="row ">
<div class="col-lg-12"><a href="membersarea"><button id="jq_cancel_btn" class="btn btn-default login" type="button">Done</button></a></div>
</div>