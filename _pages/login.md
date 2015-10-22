---
ID: 1595
post_title: Login
author: Olu
post_date: 2015-08-13 11:04:52
post_excerpt: ""
layout: page
permalink: >
  http://www.ecommerce.lotto-social.com/login/
published: true
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
lotto_page_redirect:
  - 'no'
lotto_reg_form:
  - 'no'
---
<div id="customer_login" class="row">
          <div class="col-sm-6">
<h4> Login </h4>
            <form method="post" class="login">
              <div class="form-group">
                <label for="login_mobile"> Mobile Number <span class="required">*</span></label>
                <input type="text" class="form-control" name="login_mobile" id="login_mobile" value="">
                <label for="login_mobile" class="errorText hidden" name="mobile_errorlbl" id="mobile_errorlbl"></label>
              </div>
              <div class="form-group">
                <label for="login_password"> Password <span class="required">*</span></label>
                <input class="form-control" type="password" name="login_password" id="login_password">
                <label for="login_password" class="errorText hidden" name="password_errorlbl" id="password_errorlbl"></label>
              </div>
              <div class="form-group">
                <input type="hidden" id="_wpnonce" name="_wpnonce" value="00b49eda77">
                <input type="hidden" name="_wp_http_referer" value="/">
                <input type="button" class="button button-login" onclick="return customValidation();" name="login" value="Login">
                <p class="lost_password"> <a href="http://www.ecommerce.lotto-social.com/my-account/lost-password/"> Lost password? </a> </p>
                <!-- <label for="rememberme" class="inline">
                                                        <input name="rememberme" type="checkbox" id="rememberme" value="forever" /> Remember me                                                    </label> --> 
              </div>
              <div class="form-group"> </div>
            </form>
</div>
</div>