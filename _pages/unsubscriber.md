---
ID: 4355
post_title: Unsubscriber
author: Olu
post_date: 2015-05-14 10:51:48
post_excerpt: ""
layout: page
permalink: >
  http://www.ecommerce.lotto-social.com/unsubscriber/
published: true
slide_template:
  - default
vc_teaser:
  - 'a:2:{s:4:"data";s:115:"[{"name":"title","link":"post"},{"name":"image","image":"featured","link":"none"},{"name":"text","mode":"excerpt"}]";s:7:"bgcolor";s:0:"";}'
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
lotto_reg_form:
  - 'no'
---
<div class="whitePaper"><h2 class="bold blue">Unsubscriber</h2><div class="col-lg-12 bgDashboard"><div class="col-sm-12 unsubscribe"><form class="form-horizontal" id="josFormunsubs" method="post" name="josFormunsubs"><br/><div class="form-group"><label class="col-sm-6 control-label">Please enter your mobile number to unsubscribe for texts:</label><div class="col-sm-6"><input class="form-control" id="mobile_no" type="text" maxlength="11" name="mobile_no"><div class="error_red_text" id="mobile_no_em" style="display: none;"></div></div></div><div class="form-group"><label class="col-sm-6 control-label">Please enter your email address to unsubscribe from emails:</label><div class="col-sm-6"><input class="form-control" id="email_unsubs" type="text" name="email_unsubs"><div class="error_red_text" id="email_unsubs_em" style="display: none;"></div></div></div><div class="form-group"><label class="col-sm-6 control-label"> Please give us a reason why you want to unsubscribe: </label><div class="col-sm-6"><div class="radio"><label><input id="unsub_radio_1" type="radio" name="unsub_radio" value="1">I would like to unsubscribe</label></div><div class="radio"><label><input id="unsub_radio_2" type="radio" name="unsub_radio" value="2">Please contact me less frequently</label></div><div class="radio"><label><input id="unsub_radio_3" type="radio" name="unsub_radio" value="3">I am getting emailed too frequently</label></div><div class="radio"><label><input id="unsub_radio_4" type="radio" name="unsub_radio" value="4">I am getting irrelevant emails</label></div><div style="" id="unsub_radio_em" class="error_red_text"></div></div></div><div class="form-group"><label class="col-sm-6 control-label">Please add any further comments you would like us to know about:</label><div class="col-sm-6"><textarea class="form-control" id="txt_comment" cols="35" name="txt_comment" rows="5"></textarea></div></div><div class="form-group">&nbsp;<div class="col-sm-6 col-sm-offset-6"><label class="control-label"> </label><button class="btn btn-danger" id="subscribebutton" onclick="ValidateUnsubForm('josFormunsubs');" type="button">Submit</button></div></div><input type="hidden" name="option" value="com_contactus"><input type="hidden" name="controller" value="unsubscriber"><input type="hidden" name="task" value="saveUnsubcribers"><input id="hdn_submitval" type="hidden" name="hdn_submitval" value=""></form></div></div></div>


<script>
function ValidateUnsubForm(formname){
	var phone = $('#mobile_no').val();
	var new_mob_num_1 = phone.substr(0,1);
	var new_mob_num_2 = phone.substr(0,2);
	var new_mob_num_3 = phone.substr(2);
	$('#mobile_no_em').hide();
	$('#email_unsubs_em').hide();
	$('#unsub_radio_em').hide();
	with(document.forms[formname])
	{
		if($('#mobile_no').val()=='' && $('#email_unsubs').val()=='')
		{
			$('#mobile_no_em').show().html("Please enter either phone number or email address.");
			mobile_no.focus();
			return false;
		}else if(phone!='' && !validateNumeric($('#mobile_no').val())){
			$('#mobile_no_em').show().html("Mobile Number should be numeric.");
			$('#mobile_no').val('');
			$('#mobile_no').focus();
			return false;
		}else if(phone != '' && ((new_mob_num_2 != '07' && new_mob_num_2 != '08' && new_mob_num_2 != '88' && new_mob_num_2 != '80' && new_mob_num_2 != '89') && (new_mob_num_1 != '7' && new_mob_num_2 != '8') )){
			$('#mobile_no_em').show().html("Please make sure you are entering a valid UK number starting with 07xxxxx");
			$('#mobile_no').focus();
			return false;
		}else if(phone != '' && (new_mob_num_2 == '07' && new_mob_num_2 == '08' && new_mob_num_2 == '88' && new_mob_num_2 != '80' && new_mob_num_2 != '89') && phone.length != '11'){
			$('#mobile_no_em').show().html("Please make sure you are entering a valid UK number starting with 07xxxxx");
			$('#mobile_no').focus();
			return false;
		}
		else if(phone != '' && (new_mob_num_1 == '7' || new_mob_num_1 == '8'))
		{
			$('#mobile_no_em').show().html("Please make sure you are entering a valid UK number starting with 07xxxxx");
			$('#mobile_no').focus();
			return false;
		}
		else if(phone != '' && (phone.length <11 || phone.length >12))
		{
			$('#mobile_no_em').show().html("Mobile number must be 11 digits long");
			$('#mobile_no').focus();
			return false;
		}
		else if($('#email_unsubs').val()!="" && echeck($('#email_unsubs').val())==false)
		{
			$('#email_unsubs_em').show().html("Please enter a valid email address");
			$('#email_unsubs').focus();
			return false;
		}
		else if($('input[name="unsub_radio"]:checked').length<=0) {
			$('#unsub_radio_em').show().html("Please select any one reason for unsubscribe.");
			return false;
		}
		else
		{
			$('#mobile_no_em').hide();
			$('#email_unsubs_em').hide();
			$('#unsub_radio_em').hide();
			var frm=document.josFormunsubs;
			frm.submit();
			document.getElementById("hdn_submitval").value="1";
		}
	}
}

</script>
