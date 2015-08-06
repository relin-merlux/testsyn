---
ID: 1563
post_title: Welcome Login
author: Olu
post_date: 2015-08-03 15:15:18
post_excerpt: ""
layout: page
permalink: >
  http://www.ecommerce.lotto-social.com/welcome-login/
published: true
slide_template:
  - default
---
<script src="<?php echo get_template_directory_uri(); ?>/js/customLogin.js"></script>
<div class="col-md-12 whitePaper">
		<h2 class="bold blue">Login</h2>
		<form name="SeparateLoginForm" method="post" id="Login-form2" class="form-horizontal">
			<div class="col-md-8 col-md-offset-1">
				<div class="form-group">
					<label class="col-sm-5 control-label"><strong>Enter
					your Mobile Number</strong></label>
					<div class="col-sm-6">
						<input type="text" value="" style="color: black;" placeholder="Enter your Mobile Number" name="SeparateLoginForm[mobile]" maxlength="100" id="SeparateLoginForm_mobile" class="form-control">
					</div>
				</div>
				<div class="form-group">
					<label class="col-sm-5 control-label"><strong>Enter
					your Password <span title="" data-title="" data-my="bottom center" data-hasqtip="1" data-close="no" data-classes="su-qtip qtip-bootstrap su-qtip-size-default" data-behavior="hover" data-at="top center" class="su-tooltip"><img width="16" height="16" src="/wp-content/uploads/info.png" class="infoPopUpModal"></span></strong></label>
					<div class="col-sm-6">
						<input type="password" value="" style="color: black;" placeholder="Enter your Password" name="SeparateLoginForm[password]" id="SeparateLoginForm_password" class="form-control">
					</div>
				</div>
				<div class="form-group">
					<div class="col-sm-6 col-sm-offset-5"><button type="button" onclick="return customLoginValidation('separatepg')" id="login2" class="btn btn-primary popupLogin btn-block">Login</button><img style="display:none;" src="http://lottosocial.s3.amazonaws.com/cms2/wp-content/uploads/2013/11/move-spinner.gif" class="loadSection" alt="spinner"></div>
				</div>
				<div class="form-group">
					<div class="col-sm-5">
						<div class="checkbox col-lg-offset-4">
							<label><input type="checkbox" name="Separateremember" id="Separateremember"> Remember
							Me</label><br>
							<a href="/forgot-password">Forgot your
							password?</a>
						</div>
					</div>
					<div class="col-sm-6">
						Tip: your password may include uppercase and
						lowercase characters (LOTTO is different from
						lotto)
					</div>
				</div>
			</div>
		</form>
	</div>