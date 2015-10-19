---
ID: 1941
post_title: Login
author: Olu
post_date: 2014-11-18 07:52:21
post_excerpt: ""
layout: page
permalink: >
  http://www.ecommerce.lotto-social.com/login-2/
published: true
slide_template:
  - default
vc_teaser:
  - 'a:2:{s:4:"data";s:82:"[{"name":"title","link":"post"},{"name":"image","image":"featured","link":"none"}]";s:7:"bgcolor";s:0:"";}'
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
---
<div class="row">
<div class="col-md-9 whitePaper">
<h2 class="bold blue">Login</h2>
<form id="Login-form2" class="form-horizontal" method="post" name="SeparateLoginForm">
<div class="col-md-8 col-md-offset-1">
<div class="form-group"><label class="col-sm-5 control-label"><strong>Enter your Mobile </strong></label>
<div class="col-sm-6"><input id="SeparateLoginForm_mobile" class="form-control" style="color: black;" maxlength="100" name="SeparateLoginForm[mobile]" type="text" value="<?php echo Yii::app()->request->cookies['coki_msn']->value;?>" placeholder="Enter your Mobile Number" /></div>
</div>
<div class="form-group"><label class="col-sm-5 control-label"><strong>Enter your Password [tooltip style="bootstrap" position="top" shadow="no" rounded="no" size="default" title="" content="Your password may include uppercase and lowercase characters (LOTTO is different from lotto). You can also use your latest unique order reference to login." behavior="hover" close="no" class=""]<img class="infoPopUpModal" src="/images/info.png" alt="" width="16" height="16" />[/tooltip]</strong></label>
<div class="col-sm-6"><input id="SeparateLoginForm_password" class="form-control" style="color: black;" name="SeparateLoginForm[password]" type="password" value="<?php echo Yii::app()->request->cookies['coki_pwd']->value;?>" placeholder="Enter your Password" /></div>
</div>
<div class="form-group">
<div class="col-sm-6 col-sm-offset-5"><button id="login2" class="btn btn-primary popupLogin btn-block" type="button">Login</button><img class="loadSection" src="http://lottosocial.s3.amazonaws.com/cms2/wp-content/uploads/2013/11/move-spinner.gif" alt="spinner" /></div>
</div>
<div class="form-group">
<div class="col-sm-5">
<div class="checkbox"><label><input id="Separateremember" name="Separateremember" type="checkbox" /> Remember Me</label>
<a href="/forgot-password">Forgot your password?</a></div>
</div>
<div class="col-sm-6">Tip: your password may include uppercase and lowercase characters (LOTTO is different from lotto)</div>
</div>
<div class="form-group hide">
<div class="col-sm-5 control-label"></div>
<div class="col-sm-6 tc orImage"><img src="http://lottosocial.s3.amazonaws.com/cms2/wp-content/uploads/2015/03/or-login.png" alt="or" /></div>
</div>
<div class="form-group hide">
<div class="col-sm-5 control-label"></div>
<div class="col-sm-6 tc"><a class="btn btn-block btn-primary fb-Btn" href="<?php echo $fb;?>">Facebook</a><a class="btn btn-block btn-primary gplus-Btn" href="<?php echo $fb;?>">Google+</a></div>
</div>
</div>
</form></div>
[home_top_right_elements]

</div>