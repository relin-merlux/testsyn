---
ID: 4497
post_title: My Profile
author: Olu
post_date: 2013-11-21 07:00:44
post_excerpt: ""
layout: page
permalink: >
  http://www.ecommerce.lotto-social.com/my-profile/
published: true
---
<!--:en-->
<div id="postcode" class="modal fade" tabindex="-1">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-body"><button class="closePopup" type="button" data-dismiss="modal">Close</button>
<h3 class="blueLogin">Postcode</h3>
<div class="col-lg-12 loginoptions">
<div class="option" style="margin-top: 18px; height: 293px; overflow-y: scroll; -webkit-overflow-scrolling: touch;"></div>
<div style="clear: both; height: 10px;"></div>
<button class="jq_submitpop" type="button" data-dismiss="">Submit</button></div>
</div>
</div>
</div>
</div>
<form id="profile-form" class="form-horizontal signup col-lg-10 col-lg-offset-1 col-md-10 col-md-offset-1 bgDashboard paddingtb form-horizontal" action="{%action_url%}" method="post" name="profile_form">
<h3 class="blue tc"><strong>My Profile</strong></h3>
<div class="form-group"><label class="col-lg-3 col-md-3 col-sm-3 col-xs-12 control-label" for="inputMobile">Name<span class="imp">*</span>:</label>
<div class="col-lg-8 col-md-8 col-sm-8 col-xs-12"><input id="ProfileForm_name" class="form-control" name="ProfileForm[name]" type="tel" value="{%name%}" />
<div id="ProfileForm_name_em_" class="help-inline error">{%name_em%}</div>
</div>
</div>
<div class="form-group"><label class="col-lg-3 col-md-3 col-sm-3 col-xs-12 control-label" for="inputMobile">Surname<span class="imp">*</span>:</label>
<div class="col-lg-8 col-md-8 col-sm-8 col-xs-12"><input id="ProfileForm_surname" class="form-control" name="ProfileForm[surname]" type="tel" value="{%Surname%}" />
<div id="ProfileForm_surname_em_" class="help-inline error">{%surname_em%}</div>
</div>
</div>
<div id="enter_email_pop" class="form-group"><label class="col-lg-3 col-md-3 col-sm-3 col-xs-12 control-label" for="inputMobile">Email<span class="imp">*</span>:</label>
<div class="col-lg-8 col-md-8 col-sm-8 col-xs-12"><input id="ProfileForm_email" class="form-control" name="ProfileForm[email]" type="tel" value="{%Email%}" />
<div id="ProfileForm_email_em_" class="alert-danger help-inline error">{%email_em%}</div>
</div>
</div>
<div id="reenter_email_pop" class="form-group" style="display: none;"><label class="col-lg-3 col-md-3 col-sm-3 col-xs-12 control-label" for="inputEmail2">Re-enter Email<span class="imp">*</span>:</label>
<div class="col-lg-8 col-md-8 col-sm-8 col-xs-12"><input id="inputEmail2" class="form-control" name="pay_from_email_reenter" type="email" value="" placeholder="Re-enter Email Address" />
<div id="inputEmail1_em" class="error" style="color: red; display: none;"></div>
<div class="formtip alert-danger help-inline error hidden">This is the tooltip about this field</div>
</div>
</div>
<div class="form-group"><label class="col-lg-3 col-md-3 col-sm-3 col-xs-12 control-label">Date of Birth<span class="imp">*</span>:</label>
<div class="col-lg-8 col-md-8 col-sm-8 col-xs-12 dob_class">
<div class="row">
<div class="col-lg-4 col-md-4 col-sm-4 col-xs-12"><select id="dob_date" class="form-control" name="ProfileForm[date]">
<option selected="selected" value="">DD</option>
<option value="01">01</option>
<option value="02">02</option>
<option value="03">03</option>
<option value="04">04</option>
<option value="05">05</option>
<option value="06">06</option>
<option value="07">07</option>
<option value="08">08</option>
<option value="09">09</option>
<option value="10">10</option>
<option value="11">11</option>
<option value="12">12</option>
<option value="13">13</option>
<option value="14">14</option>
<option value="15">15</option>
<option value="16">16</option>
<option value="17">17</option>
<option value="18">18</option>
<option value="19">19</option>
<option value="20">20</option>
<option value="21">21</option>
<option value="22">22</option>
<option value="23">23</option>
<option value="24">24</option>
<option value="25">25</option>
<option value="26">26</option>
<option value="27">27</option>
<option value="28">28</option>
<option value="29">29</option>
<option value="30">30</option>
<option value="31">31</option>
</select></div>
<div class="col-lg-4 col-md-4 col-sm-4 col-xs-12"><select id="dob_month" class="form-control" name="ProfileForm[month]">
<option selected="selected" value="">MM</option>
<option value="01">January</option>
<option value="02">February</option>
<option value="03">March</option>
<option value="04">April</option>
<option value="05">May</option>
<option value="06">June</option>
<option value="07">July</option>
<option value="08">August</option>
<option value="09">September</option>
<option value="10">October</option>
<option value="11">November</option>
<option value="12">December</option>
</select></div>
<div class="col-lg-4 col-md-4 col-sm-4 col-xs-12"><select id="dob_year" class="form-control" name="ProfileForm[year]">
<option selected="selected" value="">YYYY</option>{%YearDropDown%}
</select></div>
<input id="ProfileForm_dob" name="ProfileForm[dob]" type="hidden" value="" /> <input id="ProfileForm_update_ac" name="ProfileForm[update_ac]" type="hidden" value="UPDATE_ACTION" />
<div class="col-lg-8 col-md-8 col-sm-8 col-xs-12">
<div id="ProfileForm_dob_em_" class="help-inline error">{%dob_em%}</div>
</div>
</div>
<div class="row"></div>
</div>
</div>
<div class="form-group"><label class="col-lg-3 col-md-3 col-sm-3 col-xs-12 control-label" for="inputMobile">Postcode<span class="imp">*</span>:</label>
<div class="col-lg-8 col-md-7 col-sm-7 col-xs-12"><input id="ProfileForm_postcode" class="form-control" name="ProfileForm[postcode]" type="tel" value="{%Postcode%}" />
<div id="ProfileForm_postcode_em_" class="help-inline error">{%postcode_em%}</div>
</div>
<!--
<div class="col-lg-1 col-sm-2 col-xs-12"><button class="jq_postcode" type="button" data-toggle="modal" data-target="#postcode"><img alt="" src="http://lottosocial.s3.amazonaws.com/cms2/wp-content/uploads/2013/11/search_code.png" /></button></div>
--></div>
<div class="form-group"><label class="col-lg-3 col-md-3 col-sm-3 col-xs-12 control-label" for="inputMobile">Address 1<span class="imp">*</span>:</label>
<div class="col-lg-8 col-md-8 col-sm-8 col-xs-12"><input id="ProfileForm_address" class="form-control" name="ProfileForm[address]" type="tel" value="{%Address%}" />
<div id="ProfileForm_address_em_" class="help-inline error">{%address_em%}</div>
</div>
</div>
<div class="form-group"><label class="col-lg-3 col-md-3 col-sm-3 col-xs-12 control-label" for="inputMobile">Address 2:</label>
<div class="col-lg-8 col-md-8 col-sm-8 col-xs-12"><input id="ProfileForm_address_2" class="form-control" name="ProfileForm[address_2]" type="tel" value="{%Address_2%}" />
<div id="ProfileForm_address_2_em_" class="help-inline error">{%address_2_em%}</div>
</div>
</div>
<div class="form-group"><label class="col-lg-3 col-md-3 col-sm-3 col-xs-12 control-label" for="inputMobile">Town<span class="imp">*</span>:</label>
<div class="col-lg-8 col-md-8 col-sm-8 col-xs-12"><input id="ProfileForm_town" class="form-control" name="ProfileForm[town]" type="tel" value="{%Town%}" />
<div id="ProfileForm_town_em_" class="help-inline error">{%town_em%}</div>
</div>
</div>
<div class="form-group"><label class="col-lg-3 col-md-3 col-sm-3 col-xs-12 control-label" for="inputMobile">Telephone<span class="imp">*</span>:</label>
<div class="col-lg-8 col-md-8 col-sm-8 col-xs-12"><input id="ProfileForm_hometelephone" class="form-control" maxlength="11" name="ProfileForm[hometelephone]" type="tel" value="{%Telephone%}" />
<div id="ProfileForm_hometelephone_em_" class="help-inline error">{%hometelephone_em%}</div>
</div>
</div>
<div class="form-group"><label class="col-lg-3 col-md-3 col-sm-3 col-xs-12 control-label" for="inputMobile">Password:</label>
<div class="col-lg-8 col-md-8 col-sm-8 col-xs-12"><input id="ProfileForm_password" class="form-control" name="ProfileForm[password]" type="password" value="{%Password%}" /> <input id="ProfileForm_password" class="form-control" name="ProfileForm[password_hdn]" type="hidden" value="{%Password_hdn%}" />
<div id="ProfileForm_password_em_" class="help-inline error">{%password_em%}</div>
</div>
</div>
<div class="form-group"><label class="col-lg-3 col-md-3 col-sm-3 col-xs-12 control-label" for="inputMobile">Repeat Password:</label>
<div class="col-lg-8 col-md-8 col-sm-8 col-xs-12"><input id="ProfileForm_repeatpasswrod" class="form-control" name="ProfileForm[repeatpasswrod]" type="password" value="{%RepeatPassword%}" />
<div id="ProfileForm_repeatpasswrod_em_" class="help-inline error">{%repeatpasswrod_em%}</div>
</div>
</div>
<div class="form-group"><label class="col-lg-3 col-md-3 col-sm-3 col-xs-12 control-label" for="inputMobile"></label>
<div class="col-lg-5 col-md-5 col-sm-5 col-xs-12"><button id="jq_cancel_btn" class="btn btn-default login" type="button">Cancel</button> <button id="submit_btn" class="btn btn-default login" type="submit">Update</button></div>
</div>
<div class="col-lg-3"></div>
<div class="col-lg-5 col-lg-offset-1 tc cancelForm"><a class="paddingtb block" href="{%LinkForMySynticate%}/?stplnk=yes">Cancel My Syndicate Subscription</a></div>
</form><!--:--><!--:de-->
<div id="postcode" class="modal fade" tabindex="-1">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-body"><button class="closePopup" type="button" data-dismiss="modal">Close</button>
<h3 class="blueLogin">Postcode</h3>
<div class="col-lg-12 loginoptions">
<div class="option" style="margin-top: 18px; height: 293px; overflow-y: scroll; -webkit-overflow-scrolling: touch;"></div>
<div style="clear: both; height: 10px;"></div>
<button class="jq_submitpop" type="button" data-dismiss="">Submit</button></div>
</div>
</div>
</div>
</div>