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
<button type="button" class="btn btn-primary btn-lg tc" data-toggle="modal" data-target="#myRegisterModal"> LOGIN / REGISTER MODAL </button>
<div class="modal fade" id="myRegisterModal">
  <div class="modal-dialog modal-md">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
        <h2 class="modal-title tc bold" id="myModalLabel">JOIN OUR FABOLOUS COMMUNITY TODAY!</h2>
      </div>
      <div class="modal-body">
        <div class="row">
          <div class="col-sm-10 col-sm-offset-1" id="welcome-menu-login">
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
              <div class="col-sm-6">
                <h4> First time here? Create your account </h4>
                <form method="post" class="register" id="payment_form" name="payment_form">
                  <input type="hidden" name="gender" id="gender" value="">
                  <input type="hidden" name="Other" id="Other" value="">
                  <input type="hidden" name="TP1" id="TP1" value="">
                  <input type="hidden" name="TP2" id="TP2" value="">
                  <div class="form-group">
                    <select id="title" name="title" class="form-control">
                      <option value="">Title</option>
                      <option value="Mr">Mr</option>
                      <option value="Mrs">Mrs</option>
                      <option value="Ms">Ms</option>
                      <option value="Miss">Miss</option>
                    </select>
                  </div>
                  <div class="form-group">
                    <label for="reg_name" style="display:block;"> Name <span class="required">*</span></label>
                    <input type="text" name="firstname" value="" class="form-control" id="inputFName" placeholder="First Name">
                    <label for="firstname" class="errorText hidden" name="inputFName_em" id="inputFName_em"></label>
                  </div>
                  <div class="form-group">
                    <input type="text" value="" name="lastname" class="form-control" id="inputLName" placeholder="Last Name">
                    <label for="lastname" class="errorText hidden" name="inputLName_em" id="inputLName_em"></label>
                  </div>
                  <div class="form-group" id="enter_email_pop">
                    <label for="reg_email"> Email address <span class="required">*</span></label>
                    <input type="email" placeholder="Enter Email address" class="form-control" name="pay_from_email" id="inputEmail1" value="">
                    <label for="email" class="errorText hidden" name="inputEmail1_em" id="inputEmail1_em"></label>
                  </div>
                  <div class="form-group" id="reenter_email_pop" style="display:none;">
                    <label for="reg_email"> Re-enter Email address <span class="required">*</span></label>
                    <input type="email" placeholder="Re-enter Email address" class="form-control" name="pay_from_email_reenter" id="inputEmail2" value="">
                    <label for="email" class="errorText hidden" name="inputEmail2" id="inputEmail2"></label>
                  </div>
                  <div class="form-group">
                    <p class="form-row form-row-wide">
                      <label for="reg_password"> Mobile <span class="required">*</span></label>
                      <input type="tel" name="phone_number" class="form-control" id="inputMobile" placeholder="Enter Mobile Number" onblur="validateTelephone()" onkeypress="checkNumber(event);" maxlength="12">
                      <label for="phone_number" class="errorText hidden" name="phone_number_em" id="phone_number_em"></label>
                    </p>
                  </div>
                  <!-- Spam Trap -->
                  <div style="left:-999em; position:absolute;">
                    <label for="trap"> Anti-spam </label>
                    <input type="text" name="email_2" id="trap" tabindex="-1">
                  </div>
                  <div id="aggreeCheckBox" class="form-group">
                    <div class="checkbox smallText" style="left: auto;margin: 0;padding: 0; position: relative;">
                      <label>
                        <input type="checkbox" name="terms_and_condition">
                        I confirm that I am at least 16 years old and that I have read, understood and accepted the <a style="text-decoration:underline;line-height: 12px;padding: 0;" target="_blank" href="http://www.ecommerce.lotto-social.com/terms-and-conditions-for-lottery-syndicate-service/">Terms</a> and <a style="text-decoration:underline;line-height: 12px;padding: 0;" target="_blank" href="http://www.ecommerce.lotto-social.com/privacy-policy-for-lottery-syndicate-members/">Privacy Policy</a>. </label>
                    </div>
                  </div>
                  <div class="form-group">
                    <input type="hidden" name="_wp_http_referer" value="/">
                    <input type="button" onclick="return ValidatePaymentForm()" class="button button-register" name="validatePaymentForm" value="Register ￫">
                  </div>
                </form>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
