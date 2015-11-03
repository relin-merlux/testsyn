---
ID: 2080
post_title: Prize summary
author: Olu
post_date: 2014-12-05 10:57:28
post_excerpt: ""
layout: page
permalink: >
  http://www.ecommerce.lotto-social.com/prize-summary/
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
lotto_visible_to_user:
  - all
---
<div id="prizeBreakdownModal" class="modal fade" data-backdrop="static">
  <div class="modal-dialog modal-lg">
    <div class="modal-content borderNone">
      <div id="overlay" class="overlay" style="background-color: #ffffff; height: 100%; opacity: 0.8; position: absolute; z-index: 100000; width: 100%; display: none;"></div>
      <div id="tploader" class="tploader" style="display: none;"></div>
      <div class="col-lg-12">
        <center><br>
          We converted your small wins to Bonus Credit. You can keep it to buy <span class="font14 keepText"> 10</span> more lottery lines or you can swap it to cash.<br><a class="readmore"><i class="fa fa-plus-circle readmore1"></i> <span class="">Read more about Bonus Credit </span></a>
        </center>
        <ul class=" moreinfobnscdr font12 hidden" style="background: #F0F0F0;">
          <li>Bonus Credit is awarded for small winnings on your lottery tickets.</li>
          <li>A small win is 60p or less.</li>
          <li>Bonus Credit cannot be redeemed as cash.</li>
          <li>Once Bonus Credit is issued it cannot be converted back to cash.</li>
          <li>Bonus Credit can only be spent on Lotto Social products.</li>
        </ul>
        </div><br>
      <p class="col-lg-12 tc">What would you like to do?</p>
      <div class="row">
        <div class="col-sm-8 col-sm-offset-2">
          <div class="col-xs-6 tc">
            <div>
              <label class="summaryradioBtn activeRadio" title="Keep as credit.">
                <input class="radiocredit" checked="checked" name="prizeBreakdown" type="radio" value="credit" />
                <span id="creditvalue" class="radioCustomText">&amp;pound;{%bonuscreditbalance%}</span>BONUS CREDIT</label>
            </div>
          </div>
          <div class="col-xs-6 tc">
            <div>
              <label class="summaryradioBtn summarycashBtn" title="Convert to Cash.">
                <input class="radiocash" name="prizeBreakdown" type="radio" value="cash" />
                <span id="cashvalue" class="radioCustomText">&amp;pound;0.00</span>CASH</label>
            </div>
          </div>
        </div>
      </div>
      <div class="modal-footer">
        <div class="row">
          <div class="col-md-8 col-sm-6 tr "></div>
          <div class="tr col-md-4 col-sm-6"><a id="cashtocreditbtn" class="btn btn-success confirm_credit ">I choose credit</a><a class="btn btn-default loadingBtn hidden"><img class="glyphicon" src="https://www.dev.lotto-social.com/cms2/wp-content/themes/textlotto/images/ajaxloader.gif" alt="" />Loading</a></div>
        </div>
      </div>
    </div>
  </div>
</div>
<!-- End modal -->
<div id="prizeCongratulations" class="row memberNew prizeBreakdownContent">
  <div class="col-lg-10 col-lg-offset-1 whiteBg">
    <h1 class="tc">{%winningsTitle%}</h1>
    <div class="row padding-xs">{%prizeSummeryDetails%}</div>
  </div>
</div>
<div id="over30days" class="row memberNew prizeBreakdownContent">
  <div class="col-lg-10 col-lg-offset-1 whiteBg tc">{%bummer2Details%} <a class="btn btn-success btn-lg" href="#">Yes, please!</a>   <a href="#">View Other Offers &gt;</a></div>
</div>
<script>
$( document ).ready(function() { var hash = window.location.hash; var location = window.location; if (hash=="#nowinnings") { $('.prizeBreakdownContent').hide(); $('#nowinning').show(); } else if (hash=="#nothingtocheck") { $('.prizeBreakdownContent').hide(); $('#nothingtocheck').show(); } else if (hash=="#youarenotplaying") { $('.prizeBreakdownContent').hide(); $('#youarenotplaying').show(); } else if (hash=="#over30days") { $('.prizeBreakdownContent').hide(); $('#over30days').show(); } else { $('.prizeBreakdownContent').hide(); $('#prizeCongratulations').show(); } $('.summaryradioBtn').click(function(){ $('.summaryradioBtn').removeClass('activeRadio'); $(this).addClass('activeRadio'); }); });
</script> 
<script>
function checkvalue(){
if($(".radiocash")[0].checked==true){
$(".confirm_credit")[0].innerHTML="I choose cash";
}
else if($(".radiocredit")[0].checked==true){
$(".confirm_credit")[0].innerHTML="I choose credit";
}
}
function displaymoreinfo(){
if($(".moreinfobnscdr").hasClass('hidden')==true){
	$(".moreinfobnscdr").removeClass('hidden');
        $(".readmore1").removeClass('fa-plus-circle');
        $(".readmore1").addClass('fa-minus-circle'); 
       	$(".readtext")[0].innerHTML="Read less about Bonus Credit";	
        

}
else{
	$(".moreinfobnscdr").addClass('hidden');
        $(".readmore1").removeClass('fa-minus-circle');
        $(".readmore1").addClass('fa-plus-circle');         
	$(".readtext")[0].innerHTML="Read more about Bonus Credit";
}
}
</script>