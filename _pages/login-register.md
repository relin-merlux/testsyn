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
        <h3 class="modal-title tc bold" id="myModalLabel">JOIN OUR FABOLOUS COMMUNITY TODAY!</h3>
      </div>
      <div class="modal-body">
        <div class="row">
          <div class="col-sm-10 col-sm-offset-1" id="welcome-menu-login">
            <div id="customer_login" class="row">
              <div class="col-sm-6">
                <h4> Login </h4>

            <form method="post" class="login">
                <div class="form-group">
                    <label for="login_mobile1"> Mobile Number   <span class="required">*</span></label>
                    <input type="text" class="form-control" name="login_mobile1" id="login_mobile1" value="">
                    <label for="login_mobile1" class="errorText hidden" name="mobile_errorlbl1" id="mobile_errorlbl1"></label>
              </div>
              <div class="form-group">
                <label for="login_password1">Password<span class="required">*</span></label>
                <input class="form-control" type="password" name="login_password1" id="login_password1">
                <label for="login_password1" class="errorText hidden" name="password_errorlbl1" id="password_errorlbl1"></label>
              </div>
              <div class="form-group">
                  <label><input type="checkbox" id="remember" name="remember">Remember me </label> </div>
                  <div class="form-group">
                       <input type="hidden" name="_wp_http_referer" value="/login-register/"> 
					   <input type="button" class="button button-login" onclick="return customValidation();" name="login1" value="Login">
                <p class="lost_password"> <a href="http://www.ecommerce.lotto-social.com/my-account/lost-password/">Lost password? </a> </p>
       
              </div>
              <div class="form-group"> </div>
              </form>
	  </div>
              <div class="col-sm-6">
                <h4> First time here? Create your account </h4>

            <form method="post" class="register" id="payment_form1" name="payment_form1">
                            <input type="hidden" name="gender1" id="gender1" value="">
              <input type="hidden" name="Other1" id="Other1" value="">
              <input type="hidden" name="TP11" id="TP11" value="">
              <input type="hidden" name="TP21" id="TP21" value="">
              <div class="form-group">
                <select id="title1" name="title1" class="form-control">
                  <option value="">Title</option>
                  <option value="Mr">Mr</option>
                  <option value="Mrs">Mrs</option>
                  <option value="Ms">Ms</option>
                  <option value="Miss">Miss</option>
                </select>
              </div>
              <div class="form-group">
                <label for="reg_name" style="display:block;"> Name <span class="required">*</span></label>
                <input type="text" name="firstname1" value="" class="form-control" id="inputFName1" placeholder="First Name">
                <label for="firstname1" class="errorText hidden" name="inputFName_em1" id="inputFName_em1"></label>
              </div>
              <div class="form-group">
                <input type="text" value="" name="lastname1" class="form-control" id="inputLName1" placeholder="Last Name">
                <label for="lastname1" class="errorText hidden" name="inputLName_em1" id="inputLName_em1"></label>
              </div>
              <div class="form-group" id="enter_email_pop">
                <label for="reg_email"> Email address  <span class="required">*</span></label>
                <input type="email" placeholder="Enter Email address" class="form-control" name="pay_from_email1" id="inputEmail11" value="">
                <label for="email" class="errorText hidden" name="inputEmail1_em1" id="inputEmail1_em1"></label>
              </div>
              <div class="form-group" id="reenter_email_pop1" style="display:none;">
                <label for="reg_email"> Re-enter Email address  <span class="required">*</span></label>
                <input type="email" placeholder="Re-enter Email address" class="form-control" name="pay_from_email_reenter1" id="inputEmail21" value="">
                <label for="email" class="errorText hidden" name="inputEmail21" id="inputEmail21"></label>
              </div>
              <div class="form-group">
                <p class="form-row form-row-wide">
                  <label for="reg_password">Mobile<span class="required">*</span></label>
                  <input type="tel" name="phone_number1" class="form-control" id="inputMobile1" placeholder="Enter Mobile Number" onblur="validateTelephone()" onkeypress="checkNumber(event);" maxlength="12">
				  
                  <label for="phone_number1" class="errorText hidden" name="phone_number_em1" id="phone_number_em1"></label>
                </p>
              </div>
              <!-- Spam Trap -->
              <div style="left:-999em; position:absolute;">
                <label for="trap">Anti-spam  </label>
                <input type="text" name="email_21" id="trap" tabindex="-1">
              </div>
              <div id="aggreeCheckBox1" class="form-group">
                <div class="checkbox smallText" style="left: auto;margin: 0;padding: 0; position: relative;">
                  <label>
                    <input type="checkbox" name="terms_and_condition1">
                    I confirm that I am at least 16 years old and that I have read, understood and accepted the <a style="text-decoration:underline;line-height: 12px;padding: 0;" target="_blank" href="http://www.ecommerce.lotto-social.com/terms-and-conditions-for-lottery-syndicate-service/">Terms</a> and <a style="text-decoration:underline;line-height: 12px;padding: 0;" target="_blank" href="http://www.ecommerce.lotto-social.com/privacy-policy-for-lottery-syndicate-members/">Privacy Policy</a>. </label>
                </div>
              </div>
              <div class="form-group">
                    <input type="hidden" name="_wp_http_referer" value="/login-register/">   
		    <input type="button" onclick="return ValidatePaymentForm()" class="button button-register" name="validatePaymentForm1" value="Register ￫">
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
