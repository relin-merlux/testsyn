---
ID: 5696
post_title: dfcpaymentstep1
author: Olu
post_date: 2015-10-28 14:04:25
post_excerpt: ""
layout: page
permalink: >
  http://www.ecommerce.lotto-social.com/dfcpaymentstep1/
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
lotto_visible_to_user:
  - all
---
&nbsp;

<form id="IframepaymentDFC" action="IframepaymentDFC" method="post" name="IframepaymentDFC"><input name="title" type="hidden" value="" />
<input name="firstName" type="hidden" value="" />
<input name="surname" type="hidden" value="" />
<input name="dateOfBirth" type="hidden" value="" />
<input name="postCode" type="hidden" value="" />
<input name="line1" type="hidden" value="" />
<input name="line2" type="hidden" value="" />
<input name="line3" type="hidden" value="" />
<input name="line4" type="hidden" value="" />
<input name="homePhoneNumber" type="hidden" value="" />
<input name="mobilePhoneNumber" type="hidden" value="" />
<input name="email" type="hidden" value="" />
<input name="customerRef" type="hidden" value="" />
<input name="accountHolderName" type="hidden" value="" />
<input name="accountNumber" type="hidden" value="" />
<input name="bankSortCode" type="hidden" value="" />
<input name="amount" type="hidden" value="" />
<input name="CustomerWebLeadID" type="hidden" value="" />
<input name="OfferID" type="hidden" value="" />
<input name="sessionid" type="hidden" value="" />
<input name="Prosub_ID" type="hidden" value="" />
<input name="ACTIVITY" type="hidden" value="" />
<input name="New_Old_MemberArea" type="hidden" value="" /></form>
<div id="LoadingDiv"></div>
<!-----------------------------------END--------------------- -->
<div class="col-lg-12" style="background-color: white;"><form id="payment_form1" class="form signup" action="#" method="post" name="payment_form" target="_self">
<div id="Step1" style="display: block;">
<div class="row">
<div class="col-lg-12 form-group">
<div class="row"><label class="col-xs-12 control-label" for="lblBankSortCode"><strong>Bank sort code</strong></label>
<div class="col-xs-3"><!--<input type="text" id="txtSortCode1" maxlength="2" placeholder="" value="" class="form-control selectFirstField" onKeyPress="return checkNumber(event)">-->
<input id="txtSortCode1" class="form-control selectFirstField" maxlength="2" type="text" value="" placeholder="" /></div>
<div class="col-xs-1 tc">-</div>
<div class="col-xs-3"><!--<input type="text" id="txtSortCode2" maxlength="2" placeholder="" value="" class="form-control" onKeyPress="return checkNumber(event)">-->
<input id="txtSortCode2" class="form-control" maxlength="2" type="text" value="" placeholder="" /></div>
<div class="col-xs-1 tc">-</div>
<div class="col-xs-3"><!--<input type="text" id="txtSortCode3" maxlength="2" placeholder="" value="" class="form-control" onKeyPress="return checkNumber(event)">-->
<input id="txtSortCode3" class="form-control" maxlength="2" type="text" value="" placeholder="" /></div>
</div>
</div>
<div class="col-lg-12 form-group">
<div class="row"><label id="lblAccNumber" class="col-sm-12 control-label" for="inputBankAccNumber"><strong>Account Number</strong></label>
<div class="col-xs-11"><input id="txtAccountNumber" class="form-control" maxlength="20" type="text" value="" placeholder="Enter Account Number" /></div>
</div>
</div>
<div class="col-lg-12 form-group">
<div class="row"><label class="col-sm-12 control-label" for="inputBankHolderName"><strong>Bank Holder Name</strong></label>
<div class="col-xs-11"><input id="txtBankHolderName" class="form-control" type="text" value="<?php echo $_REQUEST['Acc_name']; ?>" placeholder="Enter Bank Holder Name" /></div>
</div>
</div>
<div class="form-group">
<div id="dvProceed" class="col-lg-12 tc"><button id="btnProceed" class="col-lg-12 btn-next" type="button">Proceed</button></div>
</div>
</div>
</div>
<div id="Step2" style="display: none;">
<div class="form-group row"><label class="col-xs-12 control-label" for="lblpostCode">Post code</label>
<div class="col-sm-10 col-xs-9 form-group"><input id="txtBankPostalCode" class="form-control" name="bankPostCode" type="text" value="" placeholder="Enter Postal Code" /></div>
<div class="col-sm-1 col-xs-2 form-group tr"><img src="http://lottosocial.s3.amazonaws.com/cms2/wp-content/uploads/2014/06/search-icon.png" alt="lotto-icon" width="31px;" height="34px;" /></div>
<span id="prepoaddress" style="font-style: italic; font-size: smaller; position: absolute; margin-left: 15px; margin-top: 35px;"></span>
<label class="col-xs-12 control-label" for="lblAddress">Address</label>
<div class="col-xs-11 spacetwofieldvertical"><select id="drpAddress" class="form-control" onchange="return OpenStep3()">
<option>Select Address</option>
</select></div>
</div>
</div>
<div id="Step3" style="display: none;"><label class="col-lg-12 control-label label-left" for="lblPostalAdd">Postal Address</label>
<div class="row"><label class="col-lg-12 control-label label-left" for="lblPostCode">Address Line 1</label>
<div class="col-xs-12 form-group "><input id="txtbankAddLine1" class="form-control" name="txtbankAddLine1" type="text" value="" placeholder="Enter Address Line 1" /></div>
<label class="col-lg-12 control-label label-left" for="inputBankpostCode">Address Line 2</label>
<div class="col-xs-12 form-group "><input id="txtbankAddLine2" class="form-control" name="txtbankAddLine2" type="text" value="" placeholder="Enter Address Line 2" /></div>
<label class="col-lg-12 control-label label-left" for="lblPostCode">Town</label>
<div class="col-xs-12 form-group"><input id="txtBankTown" class="form-control" name="txtBankTown" type="text" value="" placeholder="Enter Town" /></div>
<label class="col-lg-12 control-label label-left" for="inputBankpostCode">Post Code</label>
<div class="col-xs-12 form-group"><input id="txtBankPostCode" class="form-control" name="txtBankPostCode" type="text" value="" placeholder="Enter Postal Code" /></div>
</div>
<div class="form-group">
<div class="col-lg-11">
<div class="checkbox smallText"><label>
<input id="chkConfirm" name="terms_and_condition" type="checkbox" />
I confirm that my details are correct, I have read the <a href="#" data-toggle="modal" data-target="#directdebit">Direct Finance Collection Guarantee</a> and I am the sole account holder. Click here if you are you a joint account holder?
</label></div>
</div>
</div>
<div class="col-lg-12 tc"><button id="btnPlaceOrder" class="btn-next" type="button">PLACE ORDER &gt;&gt;</button></div>
</div>
</form></div>
<!-- END -->

