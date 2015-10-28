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
<html>
<body style="background-color:white;background-image:none">   
<div class="modal fade" id="directdebit" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
<style>
.modal-open {
overflow: hidden;
width: 100%;
height: 100%;
position: fixed;
left: 0px;
top: 0px;
}
</style>
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-body">
<h2>Direct Debit Agreement <img src="http://lottosocial.s3.amazonaws.com/cms2/wp-content/uploads/2014/03/dd.png"></h2>
<p> - This Guarantee is offered by all banks and building societies that accept instructions to pay Direct Debits.
If there are any changes to the amount, date or frequency of your Direct Debit (insert your organisation name)will notify you (insert number of) working days in advance of your account being debited or as otherwise agreed. </p>
<p>- If you request (insert your organisation name) to collect a payment, confirmation of the amount and date will be given to you at the time of the request.</p>
<p> - If an error is made in the payment of your Direct Debit, by (insert your organisation name) or your bank or building society, you are entitled to a full and immediate refund of the amount paid from your bank or building society.</p>
<p>- If you receive a refund you are not entitled to, you must pay it back when (insert your organisation name) asks you to
You can cancel a Direct Debit at any time by simply contacting your bank or building society. Written confirmation
</p>
<h3>Joint Account Holder</h3>
<p>Please print the direct debit agreement if you are a joint account holder &amp; return to payment setup. Please also notify us by emailing customersupport<at>lotto-social.com</at></p>
</div>
</div>
</div>
</div>
	<div class="modal fade" id="LoadingDiv" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true" style="display: none; margin-left:-160px; top:10%;overflow:hidden;width:320px; height:200px; position: absolute; z-index:9999; left: 50%;">
		<table class="table table-striped">
		<tr>
	
		<td class="ajax_loader">
		<h2 style="margin-left:13px;">Setting up account</h2>
		<div class="ajaxloader tableajaxloader" style="margin-top:5%" align="center"></div>
		</td>
		<td align='center' class="lottery_results hide table-responsive">
		</td>
		</tr>
		</table>
	</div>
<!-----------------------------------END--------------------- -->
    <div class="col-lg-12" style="background-color:white;">
        <form id="payment_form1" class="form signup" target="_self" name="payment_form" method="post" action="#" >
        	
            <div id="Step1" style="display: block;">
                <div class="row">
                    <div class="col-lg-12 form-group">
                        <div class="row">
                            <label for="lblBankSortCode" class="col-xs-12 control-label"><strong>Bank sort code</strong></label>
                            <div class="col-xs-3">
                                <input type="text" id="txtSortCode1" maxlength="2" placeholder="" value="" class="form-control selectFirstField" onKeyPress="return checkNumber(event)">
                            </div>
                            <div class="col-xs-1 tc">-</div>
                            <div class="col-xs-3">
                                <input type="text" id="txtSortCode2" maxlength="2" placeholder="" value="" class="form-control" onKeyPress="return checkNumber(event)">
                            </div>
                            <div class="col-xs-1 tc">-</div>
                            <div class="col-xs-3">
                                <input type="text" id="txtSortCode3" maxlength="2" placeholder="" value="" class="form-control" onKeyPress="return checkNumber(event)">
                            </div>
                            <div class="formtip alert-danger hidden" id="code_err" style="clear:both;margin-left:15px;"></div>
                        </div>
                    </div>
                    <div class="col-lg-12 form-group">
                        <div class="row">
                            <label for="inputBankAccNumber" id="lblAccNumber" class="col-sm-12 control-label" ><strong>Account Number</strong></label>
                            <div class="col-xs-11">
                                <input type="text" id="txtAccountNumber" maxlength="20" class="form-control" value="" placeholder="Enter Account Number" onKeyPress="return checkNumber(event)">
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-12 form-group">
                        <div class="row">
                            <label for="inputBankHolderName" class="col-sm-12 control-label" ><strong>Bank Holder Name</strong></label>
                            <div class="col-xs-11">
                                <input type="text" id="txtBankHolderName" class="form-control" value="<?php echo $_REQUEST['Acc_name'];?>" placeholder="Enter Bank Holder Name">
                            </div>
                        </div>
                    </div>
                    
                    <div class="form-group">
                    <div class="col-lg-12 tc" id="dvProceed">
                        <button id="btnProceed" type="button" onClick="return OpenStep2()" class="col-lg-12 btn-next"><span>Proceed</span></button>
                     </div>
                    </div>
                </div>
            </div>
            <div style="display: none;" id="Step2">
                <div class="form-group row">
                    <label class="col-xs-12 control-label" for="lblpostCode" >Post code</label>
                    
                    <div class="col-sm-10 col-xs-9 form-group">
                        <input type="text" id="txtBankPostalCode" class="form-control" name="bankPostCode" placeholder="Enter Postal Code" value="">
						<div class="formtip alert-danger hidden">This is the tooltip about this field</div>
                    </div>
                    <div class="col-sm-1 col-xs-2 form-group tr">
                    <img src="http://lottosocial.s3.amazonaws.com/cms2/wp-content/uploads/2014/06/search-icon.png" width="31px;" height="34px;" alt="lotto-icon" onClick="javascript:fetchAddress();"/>
                    </div>
                    <label class="col-xs-12 control-label" for="lblAddress">Address</label>
                    <div class="col-xs-11 spacetwofieldvertical">
                        <select class="form-control" onChange="return OpenStep3()" id="drpAddress">
                        </select>
                    </div>
                </div>
            </div>
             <div style="display: none;" id="Step3">
                <label class="col-lg-12 control-label label-left" for="lblPostalAdd" >Postal Address</label>
                <div class="row">
                    <label class="col-lg-12 control-label label-left" for="lblPostCode" >Address Line 1</label>
                    <div class="col-xs-12 form-group ">
                        <input type="text" class="form-control" id="txtbankAddLine1" name="bankPostCode" placeholder="Enter Address Line 1" value="">
                    </div>
                    <label class="col-lg-12 control-label label-left" for="inputBankpostCode" >Address Line 2</label>
                    <div class="col-xs-12 form-group " >
                        <input type="text" class="form-control" id="txtbankAddLine2" name="bankSortCode3" placeholder="Enter Address Line 2" value="">
                    </div>
                    <label class="col-lg-12  control-label label-left" for="lblPostCode">Town</label>
                    <div class="col-xs-12 form-group">
                        <input type="text" class="form-control" id="txtBankTown" name="bankPostCode" placeholder="Enter Town" value="">
                    </div>
                    <label class="col-lg-12  control-label label-left" for="inputBankpostCode">Post Code</label>
                    <div class="col-xs-12 form-group">
                        <input type="text" class="form-control" id="txtBankPostCode" name="bankSortCode3" placeholder="Enter Postal Code" value="">
                    </div>
                </div>
                <div class="form-group row">
                    <div class="col-lg-11">
                        <div class="checkbox smallText">
                            <label>
                                <input type="checkbox" name="terms_and_condition" id="chkConfirm">
                                I confirm that my details are correct, I have read the <a href="#" onClick="javascript:showDDInfo();" data-toggle="modal" data-target="#directdebit">direct debit guarantee</a> and I am the sole account holder. Click here if you are you a joint account holder?
								<div class="formtip alert-danger hidden">This is the tooltip about this field</div>
                            </label>
                        </div>
                    </div>
                </div>
                <div class="col-lg-12 tc">
                <button class="btn-next" type="button" id="btnPlaceOrder" onClick="javascript:makePayment();"><span>PLACE ORDER &gt;&gt;</span></button>
                </div>
            </div>
        </form>
    </div>

    <!-- END -->
</body>
</html>