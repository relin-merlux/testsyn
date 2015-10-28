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
    <body style="background-color:white;background-image:none">
        <form action="IframepaymentDFC" method="post" name="IframepaymentDFC" id="IframepaymentDFC">
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
        <script type="text/javascript">
            //--------------------Ad ded By Mukesh Patil Podia task 446 ------------ --- -----
            function showDDInfo()
            {

                $(window.parent.document).find("#directdebit").slideDown("slow");
                $(window.parent.document).find("#directdebit").css({'opacity': 1.0});
            }
            //--------------------------------------END--------------------------------------
            $(document).ready(function()
                    {
                    /* added by kamlesh savaliya 13/07/2015
                     * Task :- https://podio.com/marketingcrazecom/project/apps/p-jobs/items/356
                     */
                    populatepostcode();
                            /* -- Changes END --- */
                            if (document.getElementById("Step1").style.display === 'block')
                            {
                            $('#txtSortCode1').blur(function() {
                            if ($('#txtSortCode1').val() != "" && (validate_SortCode($('#txtSortCode1').val()))) {
                            $('#txtSortCode1').parent().removeClass('has-error');
                                    $('#txtSortCode1').parent().addClass('has-success');
                                    }
                            else if ($('#txtSortCode1').val() != "" && (!validate_SortCode($('#txtSortCode1').val()))) {
                            $('#txtSortCode1').parent().removeClass('has-success');
                                    $('#txtSortCode1').parent().addClass('has-error');
                                    }
                            else {
                            $('#txtSortCode1').parent().removeClass('has-success');
                                    $('#txtSortCode1').parent().addClass('has-error');
                                    }
                            });
                                    $('#txtSortCode2').blur(function() {
                            if ($('#txtSortCode2').val() != "" && (validate_SortCode($('#txtSortCode2').val()))) {
                            $('#txtSortCode2').parent().removeClass('has-error');
                                    $('#txtSortCode2').parent().addClass('has-success');
                                    }
                            else if ($('#txtSortCode2').val() != "" && (!validate_SortCode($('#txtSortCode2').val()))) {
                            $('#txtSortCode2').parent().removeClass('has-success');
                                    $('#txtSortCode2').parent().addClass('has-error');
                                    }
                            else {
                                    $('#txtSortCode2').parent().removeClass('has-success');
                                    $('#txtSortCode2').parent().addClass('has-error');
                            }
                            });
                                    $('#txtSortCode3').blur(function() {
                                    if ($('#txtSortCode3').val() != "" && (validate_SortCode($('#txtSortCode3').val()))) {
                                            $('#txtSortCode3').parent().removeClass('has-error');
                                            $('#txtSortCode3').parent().addClass('has-success');
                                            }
                                            else if ($('#txtSortCode3').val() != "" && (!validate_SortCode($('#txtSortCode3').val()))) {
                                            $('#txtSortCode3').parent().removeClass('has-success');
                                            $('#txtSortCode3').parent().addClass('has-error');
                                    }
                                                    else {
                                            $('#txtSortCode3').parent().removeClass('has-success');
                                            $('#txtSortCode3').parent().addClass('has-error');
                                                    }
                                            });
                                            $('#txtBankHolderName').blur(function() {
                                                    if ($('#txtBankHolderName').val() != "") {
                                                    $('#txtBankHolderName').parent().removeClass('has-error');
                                            $('#txtBankHolderName').parent().addClass('has-success');
                                    }
                                            else {
                                            $('#txtBankHolderName').parent().removeClass('has-success');
                                            $('#txtBankHolderName').parent().addClass('has-error');
                                                    }
                                                    });
                                            $('#txtAccountNumber').blur(function() {
                                                    if ($('#txtAccountNumber').val() != "") {
                                                    $('#txtAccountNumber').parent().removeClass('has-error');                                                 $('#txtAccountNumber').parent().addClass('has-success');
                                            }
                            else {
                                                    $('#txtAccountNumber').parent().removeClass('has-success');
                                            $('#txtAccountNumber').parent().addClass('has-error');
                                                    }
                                            });
                                    }
                                    if (document.getElementById("Step2").style.display === 'block')
                                            {
//	<!-- Step 2 page validation-->
                                            $('#txtBankPostalCode').blur(function() {
                                            if ($('#txtBankPostalCode').val() != "") {
                                            $('#txtBankPostalCode').parent().removeClass('has-error');
                                                    $('#txtBankPostalCode').parent().addClass('has-success');
                                                    }
                                            else {
                                            $('#txtBankPostalCode').parent().removeClass('has-success');
                                                    $('#txtBankPostalCode').parent().addClass('has-error');
                                                    }
                                            });
                                                    }
                                    if (document.getElementById("Step3").style.display === 'block')
                                            {
                                            $('#txtbankAddLine1').blur(function() {
                                            if ($('#txtbankAddLine1').val() != "") {
                                            $('#txtbankAddLine1').parent().removeClass('has-error');
                                                    $('#txtbankAddLine1').parent().addClass('has-success');
                                                    }
                                            else {
                                            $('#txtbankAddLine1').parent().removeClass('has-success');
                                                    $('#txtbankAddLine1').parent().addClass('has-error');
                                                    }
                                            });
                                                    $('#txtBankTown').blur(function() {
                                            if ($('#txtBankTown').val() != "") {
                                            $('#txtBankTown').parent().removeClass('has-error');
                                                    $('#txtBankTown').parent().addClass('has-success');
                                                    }
                                            else {
                                            $('#txtBankTown').parent().removeClass('has-success');
                                                    $('#txtBankTown').parent().addClass('has-error');
                                                    }
                                            });
                                                    $('#txtBankPostCode').blur(function() {
                                            if ($('#txtBankPostCode').val() != "") {
                                            $('#txtBankPostCode').parent().removeClass('has-error');
                                                    $('#txtBankPostCode').parent().addClass('has-success');
                                                    }
                                            else {
                                            $('#txtBankPostCode').parent().removeClass('has-success');
                                                    $('#txtBankPostCode').parent().addClass('has-error');
                                                    }
                                            });
                                                    }

                                    /*----------------------- Added by kamlesh savaliya Date :- 18/02/2015------*/

                                    if (window.parent.location.href.split('?')[0] == document.location.origin + '/payment-1/')
                                            {
                                            var UrlFName = "<?php echo $_GET['firstname'] ?>";
                                                    var UrllastName = "<?php echo $_GET['lastname'] ?>";
                                                    var accountholdername = UrlFName + " " + UrllastName;
                                                    var account_holdername = decodeURI(accountholdername);
                                                    document.getElementById("txtBankHolderName").value = account_holdername;
                                                    }
                                    /* -- Added by kamlesh savaliya (16/07/2015)
                                     * Task :- DFC registation issue -- */

                                    else if (window.parent.location.href.split('?')[0] == document.location.origin + '/make-payment-for-lottery-syndicate-membership')
                                            {
                                            var UrlFName = "<?php echo $_GET['firstname'] ?>";
                                                    var UrllastName = "<?php echo $_GET['lastname'] ?>";
                                                    var accountholdername = UrlFName + " " + UrllastName;
                                                    var account_holdername = decodeURI(accountholdername);
                                                    document.getElementById("txtBankHolderName").value = account_holdername;
                                                    }
                                    /* -- END -- */
                                    else
                                            {
                                            var params1 = getUrlVars();
                                                    var UrlFName = decodeURI(params1.firstName);
                                                    var UrllastName = decodeURI(params1.surname);
                                                    var accountholdername = UrlFName + " " + UrllastName;
                                                    document.getElementById("txtBankHolderName").value = accountholdername;
                                                    }

                                    /* ------------------------------------ END -----------------------------------------*/


                                    });
                                    function validate_SortCode(sort_value) {
                                    var nameRegex = /^[A-Za-z0-9]{2}$/;
                                            var valid_name = sort_value.match(nameRegex)
                                            return valid_name;
                                    }

                            function checkNumber(evt) {
                            key = '';
                                    if (window.event) // IE
                                    {
                                    key = evt.keyCode
                                            }
                            else if (evt.which) // Netscape/Firefox/Opera
                                    {
                                    key = evt.which
                                            }
                            if ((key) && !((key >= 48 && key <= 57) || (key == 8) || (key == 13)))
                                    evt.preventDefault();
                                    }

                            function fetchAddress(){
                            $.ajax({
                            type: "GET",
                                    url: "addressPaymentFinder",
                                    data: {postcode : $('#txtBankPostalCode').val(), banksortcode:$('#txtSortCode1').val() + $('#txtSortCode2').val() + $('#txtSortCode3').val(), accno:$('#txtAccountNumber').val()},
                                    success: function(response)
                                    {
                                    /* Added / Modified by Mukesh for  for blocking derick's account on 16th June 2015 - Start */
                                    if ($.trim(response) == 'BlockedBankdetails'){
                                    alert('Please Enter valid Banksortcode/AccountNo.');
                                            $('#txtSortCode1').attr('readonly', '')[0].readOnly = false;
                                            $('#txtSortCode2').attr('readonly', '')[0].readOnly = false;
                                            $('#txtSortCode3').attr('readonly', '')[0].readOnly = false;
                                            $('#txtSortCode1').val(''); $('#txtSortCode1').parent().removeClass('has-success'); $('#txtSortCode1').parent().addClass('has-error');
                                            $('#txtSortCode2').val(''); $('#txtSortCode2').parent().removeClass('has-success'); $('#txtSortCode2').parent().addClass('has-error');
                                            $('#txtSortCode3').val(''); $('#txtSortCode3').parent().removeClass('has-success'); $('#txtSortCode3').parent().addClass('has-error');
                                            $('#txtAccountNumber').val(''); $('#txtAccountNumber').parent().removeClass('has-success'); $('#txtAccountNumber').parent().addClass('has-error');
                                    }
                                    else{
                                    if (response != "no records found")
                                    {
                                    $('#drpAddress').html(response);
                                    }
                                    /* added by kamlesh savaliya
                                     * podio :- https://podio.com/marketingcrazecom/pid/apps/mc-jobs/items/1176
                                     * Date :- 07/07/2015
                                     */
                                    else
                                    {
                                    alert('Postcode not found.');
                                            $('#txtBankPostalCode').val('');
                                    }
                                    /* --- Chnages Done ----- */
                                    }
                                    }
                            });
                                    }
                            function OpenStep2() {
                            if (ValidatePaymentFormStep1())
                                    {
                                    $("#LoadingDiv").show();
                                            $('#txtBankHolderName').attr('readonly', 'readonly');
                                            //$('#txtAccountNumber').attr('readonly','readonly');
                                            $('#txtSortCode1').attr('readonly', 'readonly');
                                            $('#txtSortCode2').attr('readonly', 'readonly');
                                            $('#txtSortCode3').attr('readonly', 'readonly');
                                            document.getElementById("dvProceed").style.display = "none";
                                            document.getElementById("Step1").style.display = "block";
                                            document.getElementById("Step2").style.display = "block";
                                            $("#LoadingDiv").hide();
                                            }
                            }
                            function OpenStep3() {
                            $.ajax({
                            type: "POST",
                                    url: "addressSplitter",
                                    data: {address : $('#drpAddress').val()},
                                    success: function(response)
                                    {
                                    var res = eval("(" + response + ")");
                                            $('#txtbankAddLine1').val(res["line1"]);
                                            $('#txtbankAddLine2').val(res["line2"]);
                                            $('#txtBankTown').val(res["city"]);
                                            $('#txtBankPostCode').val($('#txtBankPostalCode').val());
                                            document.getElementById("Step2").style.display = "block";
                                            document.getElementById("Step3").style.display = "block";
                                    }
                            });
                                    }
//--------------- Added By Mukesh Patil -------
                            function getParameterByName1(name)
                                    {
                                    name = name.replace(/[\[]/, "\\[").replace(/[\]]/, "\\]");
                                            var regex = new RegExp("[\\?&]" + name + "=([^&#]*)"),
                                            results = regex.exec(window.top.document.URL.search);
                                            return results == null ? "" : decodeURIComponent(results[1].replace(/\+/g, " "));
                                            }
//-----------------------END ------------
                            function makePayment()
                                    {
                                    $("#LoadingDiv").show();
                                            var Postelcode = $('#txtBankPostalCode').val();
                                            var Address1 = $('#txtbankAddLine1').val();
                                            var postcodevalid = "false";
                                            $.ajax({
                                            type: "POST",
                                                    url: "site/ValidatePostelCode",
                                                    data: {Postel_code:Postelcode, Address_1:Address1},
                                                    success: function(response)
                                                    {
                                                    if (response == "True")
                                                    {
                                                    postcodevalid = "True";
                                                    }
                                                    postcodevalid = "True";
                                                            if (postcodevalid == "True")
                                                    {
                                                    if (ValidatePaymentFormStep2() && ValidatePaymentFormStep1())
                                                    {
                                                    /*--------  Added by kamlesh savaliya Date :- 18/03/2015 -------*/
                                                    if (window.parent.location.href.split('?')[0] == document.location.origin + '/payment-1/')
                                                    {
                                                    var UrlTitle = "<?php echo $_GET['title'] ?>";
                                                            var UrlFirstName = "<?php echo $_GET['firstname'] ?>";
                                                            //---------------------------added by mukesh patil -----------------------
                                                            if (UrlTitle == '') {
                                                    $.get('https://gender-api.com/get?name=' + UrlFirstName, function(data) {
                                                    if (data.gender == "male")
                                                    {
                                                    UrlTitle = 'Mr';
                                                    }
                                                    else if (data.gender == "female")
                                                    {
                                                    UrlTitle = 'Ms';
                                                    }
                                                    });
                                                    }
                                                    //------------------------------------------END---------------------------

                                                    var UrlSurName = "<?php echo $_GET['lastname'] ?>";
                                                            var UrlDateOfBirth = "<?php echo $_GET['DOB'] ?>";
                                                            var UrlBankPostalCode = $('#txtBankPostalCode').val();
                                                            var UrlAddressline1 = $('#txtbankAddLine1').val();
                                                            var UrlAddressline2 = $('#txtbankAddLine2').val();
                                                            var UrlAddressline3 = "";
                                                            var UrlAddressline4 = "";
                                                            var UrlHomePhoneNumber = "<?php echo $_GET['phone_number'] ?>";
                                                            var UrlMobilePhoneNumber = "<?php echo $_GET['phone_number'] ?>";
                                                            var UrlEmail = "<?php echo $_GET['pay_from_email'] ?>";
                                                            var UrlCustomerRef = "<?php echo $_GET['web_lead_Id'] ?>";
                                                            var UrlAccountHolderName = $('#txtBankHolderName').val();
                                                            var UrlAccountNumber = $('#txtAccountNumber').val();
                                                            var BankSortCode1 = $('#txtSortCode1').val();
                                                            var BankSortCode2 = $('#txtSortCode2').val();
                                                            var BankSortCode3 = $('#txtSortCode3').val();
                                                            var UrlBankSortCode = BankSortCode1 + BankSortCode2 + BankSortCode3;
                                                            var UrlSessionID = "<?php echo $_GET['session_id'] ?>";
                                                            var UrlProsub_ID = "<?php echo $_GET['prosub_ID'] ?>";
                                                            var UrlCustomerWebLeadID = "<?php echo $_GET['web_lead_Id'] ?>";
                                                            var UrlOfferID = "<?php echo $_GET['offerid'] ?>";
                                                            var UrlAmount = "<?php echo $_GET['amount'] ?>";
                                                            var UrlTown = $('#txtBankTown').val();
                                                            var UrlPostCode = $('#txtBankPostCode').val();
                                                            var checkNew_Old_MemberArea = 'True';
                                                    }
                                                    /* -- Added by kamlesh savaliya (16/07/2015)
                                                     * Task :- DFC registation issue -- */
                                                    else if (window.parent.location.href.split('?')[0] == document.location.origin + '/make-payment-for-lottery-syndicate-membership')
                                                    {
                                                    var UrlTitle = "<?php echo $_GET['title'] ?>";
                                                            var UrlFirstName = "<?php echo $_GET['firstname'] ?>";
                                                            //---------------------------added by mukesh patil -----------------------
                                                            if (UrlTitle == '')
                                                    {
                                                    $.get('https://gender-api.com/get?name=' + UrlFirstName, function(data) {
                                                    if (data.gender == "male")
                                                    {
                                                    UrlTitle = 'Mr';
                                                    }
                                                    else if (data.gender == "female")
                                                    {
                                                    UrlTitle = 'Ms';
                                                    }
                                                    });
                                                    }
                                                    var UrlSurName = "<?php echo $_GET['lastname'] ?>";
                                                            var UrlDateOfBirth = "<?php echo $_GET['dob'] ?>";
                                                            var UrlBankPostalCode = $('#txtBankPostalCode').val();
                                                            var UrlAddressline1 = $('#txtbankAddLine1').val();
                                                            var UrlAddressline2 = $('#txtbankAddLine2').val();
                                                            var UrlAddressline3 = "";
                                                            var UrlAddressline4 = "";
                                                            var UrlHomePhoneNumber = "<?php echo $_GET['phone_number'] ?>";
                                                            var UrlMobilePhoneNumber = "<?php echo $_GET['phone_number'] ?>";
                                                            var UrlEmail = "<?php echo $_GET['pay_from_email'] ?>";
                                                            var UrlCustomerRef = "<?php echo $_GET['webleadid'] ?>";
                                                            var UrlAccountHolderName = $('#txtBankHolderName').val();
                                                            var UrlAccountNumber = $('#txtAccountNumber').val();
                                                            var BankSortCode1 = $('#txtSortCode1').val();
                                                            var BankSortCode2 = $('#txtSortCode2').val();
                                                            var BankSortCode3 = $('#txtSortCode3').val();
                                                            var UrlBankSortCode = BankSortCode1 + BankSortCode2 + BankSortCode3;
                                                            var UrlSessionID = "<?php echo $_GET['session_id'] ?>";
                                                            var UrlProsub_ID = "<?php echo $_GET['prosub_id'] ?>";
                                                            var UrlCustomerWebLeadID = "<?php echo $_GET['webleadid'] ?>";
                                                            var UrlOfferID = "<?php echo $_GET['offerid'] ?>";
                                                            var UrlAmount = "<?php echo $_GET['amount'] ?>";
                                                            var UrlTown = $('#txtBankTown').val();
                                                            var UrlPostCode = $('#txtBankPostCode').val();
                                                            var checkNew_Old_MemberArea = 'False';
                                                    }
                                                    /* -- END -- */
                                                    else
                                                    {

                                                    var params = getUrlVars();
                                                            var UrlTitle = params["title"];
                                                            var UrlFirstName = params["firstName"];
                                                            var UrlSurName = params["surname"];
                                                            var UrlDateOfBirth = params["dateOfBirth"];
                                                            var UrlBankPostalCode = $('#txtBankPostalCode').val();
                                                            var UrlAddressline1 = $('#txtbankAddLine1').val();
                                                            var UrlAddressline2 = $('#txtbankAddLine2').val();
                                                            var UrlAddressline3 = "";
                                                            var UrlAddressline4 = "";
                                                            var UrlHomePhoneNumber = params["homePhoneNumber"];
                                                            var UrlMobilePhoneNumber = params["mobilePhoneNumber"];
                                                            var UrlEmail = params["email"];
                                                            var UrlCustomerRef = params["customerRef"];
                                                            var UrlAccountHolderName = $('#txtBankHolderName').val();
                                                            var UrlAccountNumber = $('#txtAccountNumber').val();
                                                            var BankSortCode1 = $('#txtSortCode1').val();
                                                            var BankSortCode2 = $('#txtSortCode2').val();
                                                            var BankSortCode3 = $('#txtSortCode3').val();
                                                            var UrlBankSortCode = BankSortCode1 + BankSortCode2 + BankSortCode3;
                                                            var UrlSessionID = params["sessionid"];
                                                            var UrlProsub_ID = params["Prosub_ID"];
                                                            var UrlCustomerWebLeadID = params["customerRef"]; ;
                                                            var UrlOfferID = params["offerId"];
                                                            var UrlAmount = params["amount"];
                                                            var UrlTown = $('#txtBankTown').val();
                                                            var UrlPostCode = $('#txtBankPostCode').val();
                                                            var checkNew_Old_MemberArea = 'False';
                                                    }
                                                    var params = getUrlVars();
                                                            if (params.ACTIVITY == "callcenter")
                                                    {
                                                    //----------------------------- Added By Mukesh Patil Podio No - 1001 ------------------
                                                    $.ajax({
                                                    type: "POST",
                                                            url: "validateMSNNo",
                                                            data: {MSNNo: UrlMobilePhoneNumber, getFirstName:UrlFirstName, getSurname:UrlSurName, getEmail:UrlEmail, getAddress1:UrlAddressline1, getAddress2:UrlAddressline2, getTown:UrlTown, getPostCode:UrlPostCode},
                                                            success: function (response) {

                                                            }
                                                    });
                                                            //--------------------------------------------END---------------------------------------
                                                    }
                                                    //--------------------- END--------------------			
                                                    querystring = "?title=" + UrlTitle + "&firstName=" + UrlFirstName + "&surname=" + UrlSurName + "&dateOfBirth=" + UrlDateOfBirth + "&postCode=" + UrlBankPostalCode + "&line1=" + UrlAddressline1 + "&line2=" + UrlAddressline2 + "&line3=" + UrlAddressline3 + "&line4=" + UrlAddressline4 + "&homePhoneNumber=" + UrlHomePhoneNumber + "&mobilePhoneNumber=" + UrlMobilePhoneNumber + "&email=" + UrlEmail + "&customerRef=" + UrlCustomerRef + "&accountHolderName=" + UrlAccountHolderName + "&accountNumber=" + UrlAccountNumber + "&bankSortCode=" + UrlBankSortCode + "&amount=" + UrlAmount + "&CustomerWebLeadID=" + UrlCustomerWebLeadID + "&OfferID=" + UrlOfferID + "&sessionid=" + UrlSessionID + "&Prosub_ID=" + UrlProsub_ID;
                                                            var ACTIVITY = '';
                                                            $("[name='title']").val(UrlTitle);
                                                            $("[name='firstName']").val(UrlFirstName);
                                                            $("[name='surname']").val(UrlSurName);
                                                            $("[name='dateOfBirth']").val(UrlDateOfBirth);
                                                            $("[name='postCode']").val(UrlBankPostalCode);
                                                            $("[name='line1']").val(UrlAddressline1);
                                                            $("[name='line2']").val(UrlAddressline2);
                                                            $("[name='line3']").val(UrlAddressline3);
                                                            $("[name='line4']").val(UrlTown);
                                                            $("[name='homePhoneNumber']").val(UrlHomePhoneNumber);
                                                            $("[name='mobilePhoneNumber']").val(UrlMobilePhoneNumber);
                                                            $("[name='email']").val(UrlEmail);
                                                            $("[name='customerRef']").val(UrlCustomerRef);
                                                            $("[name='accountHolderName']").val(UrlAccountHolderName);
                                                            $("[name='accountNumber']").val(UrlAccountNumber);
                                                            $("[name='bankSortCode']").val(UrlBankSortCode);
                                                            $("[name='amount']").val(UrlAmount);
                                                            $("[name='CustomerWebLeadID']").val(UrlCustomerWebLeadID);
                                                            $("[name='OfferID']").val(UrlOfferID);
                                                            $("[name='sessionid']").val(UrlSessionID);
                                                            $("[name='Prosub_ID']").val(UrlProsub_ID);
                                                            $("[name='New_Old_MemberArea']").val(checkNew_Old_MemberArea);
                                                            if (params.ACTIVITY == "callcenter")
                                                    {
                                                    ACTIVITY = "callcenter";
                                                            $("[name='ACTIVITY']").val(ACTIVITY);
                                                    }
                                                    /* added by kamlesh savaliya
                                                     * task :- Callcentre
                                                     * Date :- 07/07/2015
                                                     */
                                                    else if (params.ACTIVITY == "new_callcenter")
                                                    {
                                                    ACTIVITY = "new_callcenter";
                                                            $("[name='ACTIVITY']").val(ACTIVITY);
                                                    }
                                                    /* ----- changes Done ---- */
                                                    else{
                                                    $("[name='ACTIVITY']").val(ACTIVITY);
                                                    }



                                                    document.IframepaymentDFC.submit();
                                                    }
                                                    }
                                                    else
                                                    {
                                                    alert("Address is already registered.");
                                                    }
                                                    }
                                            });
          <?php // added by kamlesh savaliya (29/09/2015) ?>
          //$("#LoadingDiv").hide();
}
            
            
function getUrlVars() {
var vars = {};
var parts = window.parent.location.href.replace(/[?&]+([^=&]+)=([^&]*)/gi, function(m,key,value) {
vars[key] = value;
});
return vars;
}
            
function ValidatePaymentFormStep1() {
if (document.getElementById("txtSortCode1").value === '' || document.getElementById("txtSortCode1").value.length ==1) {
$('#txtSortCode1').parent().addClass('has-error');
$('#txtSortCode1').focus();
return false;
}
else if (document.getElementById("txtSortCode2").value === '' || document.getElementById("txtSortCode2").value.length ==1) {
$('#txtSortCode1').parent().removeClass('has-error');
$('#txtSortCode2').parent().addClass('has-error');
$('#txtSortCode2').focus();
return false;
}
else if (document.getElementById("txtSortCode3").value === '' || document.getElementById("txtSortCode3").value.length ==1) {
$('#txtSortCode1').parent().removeClass('has-error');
$('#txtSortCode2').parent().removeClass('has-error');
$('#txtSortCode3').parent().addClass('has-error');
$('#txtSortCode3').focus();
return false;
}
else if (document.getElementById("txtAccountNumber").value === '') {
$('#txtSortCode1').parent().removeClass('has-error');
$('#txtSortCode2').parent().removeClass('has-error');
$('#txtSortCode3').parent().removeClass('has-error');
$('#txtBankHolderName').parent().removeClass('has-error');
$('#txtAccountNumber').parent().addClass('has-error');
$('#txtAccountNumber').focus();
return false;
}
else if (document.getElementById("txtBankHolderName").value === '') {
$('#txtSortCode1').parent().removeClass('has-error');
$('#txtSortCode2').parent().removeClass('has-error');
$('#txtSortCode3').parent().removeClass('has-error');
$('#txtBankHolderName').parent().addClass('has-error');
$('#txtBankHolderName').focus();
return false;
}
return true;
}
            
function ValidatePaymentFormStep2() {
if (document.getElementById("txtbankAddLine1").value === '') {
$('#txtbankAddLine1').parent().addClass('has-error');
$('#txtbankAddLine1').focus();
return false;
}
else if (document.getElementById("txtBankTown").value === '') {
$('#txtbankAddLine1').parent().removeClass('has-error');
$('#txtBankTown').parent().addClass('has-error');
$('#txtBankTown').focus();
return false;
}
else if (document.getElementById("txtBankPostCode").value === '') {
$('#txtbankAddLine1').parent().removeClass('has-error');
$('#txtBankTown').parent().removeClass('has-error');
$('#txtBankPostCode').parent().addClass('has-error');
$('#txtBankPostCode').focus();
return false;
}
else if (document.getElementById('chkConfirm').checked === false) {
alert('Please tick checkbox to confirm your details and accept  direct finance collection guarantee.');
$('#chkConfirm').focus();
return false;
}
                
return true;
}
        </script>