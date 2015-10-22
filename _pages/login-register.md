---
ID: 5267
post_title: 'Login &#8211; Register'
author: Olu
post_date: 2015-10-22 11:27:42
post_excerpt: ""
layout: page
permalink: >
  http://www.ecommerce.lotto-social.com/login-register/
published: true
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
slide_template:
  - default
lotto_reg_form:
  - 'no'
---
<button type="button" class="btn btn-primary btn-lg" data-toggle="modal" data-target="#myLoginModal"> Login button </button>
<div class="modal fade" id="myLoginModal">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
        <h4 class="modal-title" id="myModalLabel">Login</h4>
      </div>
      <div class="modal-body">
        <div class="customer-login-box customer-login-box1">
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
    </div>
  </div>
</div>
