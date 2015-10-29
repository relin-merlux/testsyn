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
<html>    <body style="background-color:white;background-image:none">
        <form action="http://www.ecommerce.lotto-social.com/IframepaymentDFC" method="post" name="IframepaymentDFC" id="IframepaymentDFC">
            <input type="hidden" name="title" value="">
            <input type="hidden" name="firstName" value="">
            <input type="hidden" name="surname" value="">
            <input type="hidden" name="dateOfBirth" value="">
            <input type="hidden" name="postCode" value="">
            <input type="hidden" name="line1" value="">
            <input type="hidden" name="line2" value="">
            <input type="hidden" name="line3" value="">
            <input type="hidden" name="line4" value="">
            <input type="hidden" name="homePhoneNumber" value="">
            <input type="hidden" name="mobilePhoneNumber" value="">
            <input type="hidden" name="email" value="">
            <input type="hidden" name="customerRef" value="">
            <input type="hidden" name="accountHolderName" value="">
            <input type="hidden" name="accountNumber" value="">
            <input type="hidden" name="bankSortCode" value="">
            <input type="hidden" name="amount" value="">
            <input type="hidden" name="CustomerWebLeadID" value="">
            <input type="hidden" name="OfferID" value="">
            <input type="hidden" name="sessionid" value="">
            <input type="hidden" name="Prosub_ID" value="">
            <input type="hidden" name="ACTIVITY" value="">
            <input type="hidden" name="New_Old_MemberArea" value="">
        </form>
        <div id="LoadingDiv">
            <div class="tploader"></div>
        </div>
        <style>
            #LoadingDiv {
                display: none;
                overflow: hidden;
                width: 100%;
                height: 100%;
                position: fixed;
                z-index: 9999;
                left: 0;
                top: 0px;
                background-color: rgba(255,255,255,0.8);
            }
        </style>
        <!-----------------------------------END--------------------- -->
        <div class="col-lg-12" style="background-color:white;">
            <form id="payment_form1" class="form signup" target="_self" name="payment_form" method="post" action="#" >

                <div id="Step1" style="display: block;">
                    <div class="row">
                        <div class="col-lg-12 form-group">
                            <div class="row">
                                <label for="lblBankSortCode" class="col-xs-12 control-label"><strong>Bank sort code</strong></label>
                                <div class="col-xs-3">
                                    <!--<input type="text" id="txtSortCode1" maxlength="2" placeholder="" value="" class="form-control selectFirstField" onKeyPress="return checkNumber(event)">-->
                                    <input type="text" id="txtSortCode1" maxlength="2" placeholder="" value="" class="form-control selectFirstField">
                                </div>
                                <div class="col-xs-1 tc">-</div>
                                <div class="col-xs-3">
                                    <!--<input type="text" id="txtSortCode2" maxlength="2" placeholder="" value="" class="form-control" onKeyPress="return checkNumber(event)">-->
                                    <input type="text" id="txtSortCode2" maxlength="2" placeholder="" value="" class="form-control">
                                </div>
                                <div class="col-xs-1 tc">-</div>
                                <div class="col-xs-3">
                                    <!--<input type="text" id="txtSortCode3" maxlength="2" placeholder="" value="" class="form-control" onKeyPress="return checkNumber(event)">-->
                                    <input type="text" id="txtSortCode3" maxlength="2" placeholder="" value="" class="form-control">
                                </div>
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
                                    <input type="text" id="txtBankHolderName" class="form-control" value="<?php echo $_REQUEST['Acc_name']; ?>" placeholder="Enter Bank Holder Name">
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
                        </div>
                        <div class="col-sm-1 col-xs-2 form-group tr">
                            <img src="http://lottosocial.s3.amazonaws.com/cms2/wp-content/uploads/2014/06/search-icon.png" width="31px;" height="34px;" alt="lotto-icon" onClick="javascript:fetchAddress();"/>
                        </div>
                        <span id="prepoaddress" 
                              style="
                              font-style: italic;
                              font-size: smaller;
                              position: absolute;
                              margin-left: -10;
                              margin-top: 35px;
                              margin-left: 15px;
                              "
                              ></span>
                        <label class="col-xs-12 control-label" for="lblAddress">Address</label>
                        <div class="col-xs-11 spacetwofieldvertical">
                            <select class="form-control" onChange="return OpenStep3()" id="drpAddress">
                                <option>Select Address</option>
                            </select>
                        </div>
                    </div>
                </div>
                <div style="display: none;" id="Step3">
                    <label class="col-lg-12 control-label label-left" for="lblPostalAdd" >Postal Address</label>
                    <div class="row">
                        <label class="col-lg-12 control-label label-left" for="lblPostCode" >Address Line 1</label>
                        <div class="col-xs-12 form-group ">
                            <input type="text" class="form-control" id="txtbankAddLine1" name="txtbankAddLine1" placeholder="Enter Address Line 1" value="">
                        </div>
                        <label class="col-lg-12 control-label label-left" for="inputBankpostCode" >Address Line 2</label>
                        <div class="col-xs-12 form-group " >
                            <input type="text" class="form-control" id="txtbankAddLine2" name="txtbankAddLine2" placeholder="Enter Address Line 2" value="">
                        </div>
                        <label class="col-lg-12  control-label label-left" for="lblPostCode">Town</label>
                        <div class="col-xs-12 form-group">
                            <input type="text" class="form-control" id="txtBankTown" name="txtBankTown" placeholder="Enter Town" value="">
                        </div>
                        <label class="col-lg-12  control-label label-left" for="inputBankpostCode">Post Code</label>
                        <div class="col-xs-12 form-group">
                            <input type="text" class="form-control" id="txtBankPostCode" name="txtBankPostCode" placeholder="Enter Postal Code" value="">
                        </div>
                    </div>
                    <div class="form-group">
                        <div class="col-lg-11">
                            <div class="checkbox smallText">
                                <label>
                                    <input type="checkbox" name="terms_and_condition" id="chkConfirm">
                                    I confirm that my details are correct, I have read the <a href="#" onClick="javascript:showDDInfo();" data-toggle="modal" data-target="#directdebit">Direct Finance Collection Guarantee</a> and I am the sole account holder. Click here if you are you a joint account holder?
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


<script src="http://www.ecommerce.lotto-social.com/wp-content/themes/bishop-child/js/dfc-payment-validation.js"></script>
