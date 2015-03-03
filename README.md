# NHL-Draft-Slider
JavaScript written for NHL Draft Slider

<script>
function tick(){
    $('#ticker li:first').slideUp( function () { $(this).appendTo($('#ticker')).slideDown(); });
}
setInterval(function(){ tick () }, 8000);

</script>

<link href='http://fonts.googleapis.com/css?family=Oswald' rel='stylesheet' type='text/css'>
<!--<script src="http://www.sportsnetwork.com/includes/events/nhl/tradedeadline/tickerjQuery.js"></script>-->
<style type="text/css">
<!--
.bottomwhite {
border-bottom: 2px solid #FFFFFF;
}
#ticker {
    height: 220px;
	width:300px;
    overflow: hidden;
	margin: 0; padding: 0;
	list-style: none;
	vertical-align: middle;
}
#ticker li {
    height: 220px;
	width:300px;
	vertical-align: top;

}

#ticker li span {
	font-family: Oswald;
	vertical-align: top;

	}
-->
</style>


<table cellpadding="0" cellspacing="0" border="0" align="center" width="300" bgcolor="#232323">
<tr>
<td align="center" width="300" height="28">
<img src="http://images.sportsnetwork.com/snetwork/home700/events/homepage/right/tradetracker/banner1.jpg" width="300" height="28" class="bottomwhite">
</td>
</tr>
<tr>
<td align="center" width="300" height="220" class="bottomwhite">
<ul id="ticker">

<li><img src="http://images.sportsnetwork.com/nhl/specialevents/trade_deadline/wisniewski_ducks.jpg"></li>
<li><img src="http://images.sportsnetwork.com/nhl/specialevents/trade_deadline/stewart_wild.jpg"></li>
<li><img src="http://images.sportsnetwork.com/nhl/specialevents/trade_deadline/talbot_bruins.jpg"></li>
<li><img src="http://images.sportsnetwork.com/nhl/specialevents/trade_deadline/mitchell_habs.jpg"></li>
<li><img src="http://images.sportsnetwork.com/nhl/specialevents/trade_deadline/brewer_leafs.jpg"></li>
<li><img src="http://images.sportsnetwork.com/nhl/specialevents/trade_deadline/knight_wild.jpg"></li>
<li><img src="http://images.sportsnetwork.com/nhl/specialevents/trade_deadline/lovejoy_penguins.jpg"></li>
<li><img src="http://images.sportsnetwork.com/nhl/specialevents/trade_deadline/jokinen_blues.jpg"></li>
<li><img src="http://images.sportsnetwork.com/nhl/specialevents/trade_deadline/baertschi_canucks.jpg"></li>
<li><img src="http://images.sportsnetwork.com/nhl/specialevents/trade_deadline/clark_avs.jpg"></li>
<li><img src="http://images.sportsnetwork.com/nhl/specialevents/trade_deadline/neurvirth_islanders.jpg"></li>
<li><img src="http://images.sportsnetwork.com/nhl/specialevents/trade_deadline/leggio_coyotes.jpg"></li>
<li><img src="http://images.sportsnetwork.com/nhl/specialevents/trade_deadline/leopold_wild.jpg"></li>
<li><img src="http://images.sportsnetwork.com/nhl/specialevents/trade_deadline/zidlicky_wings.jpg"></li>
<li><img src="http://images.sportsnetwork.com/nhl/specialevents/trade_deadline/kennedy_islanders.jpg"></li>
<li><img src="http://images.sportsnetwork.com/nhl/specialevents/trade_deadline/conacher_canucks.jpg"></li>
<li><img src="http://images.sportsnetwork.com/nhl/specialevents/trade_deadline/smith_blackhawks.jpg"></li>
<li><img src="http://images.sportsnetwork.com/nhl/specialevents/trade_deadline/cole_penguins.jpg"></li>
<li><img src="http://images.sportsnetwork.com/nhl/specialevents/trade_deadline/hamilton_avs.jpg"></li>
<li><img src="http://images.sportsnetwork.com/nhl/specialevents/trade_deadline/michalek_blues.jpg"></li>
<li><img src="http://images.sportsnetwork.com/nhl/specialevents/trade_deadline/flynn_canadiens.jpg"></li>
<li><img src="http://images.sportsnetwork.com/nhl/specialevents/trade_deadline/petry_canadiens.jpg"></li>
<li><img src="http://images.sportsnetwork.com/nhl/specialevents/trade_deadline/coburn_gudas.jpg"></li>
<li><img src="http://images.sportsnetwork.com/nhl/specialevents/trade_deadline/connolly_bruins.jpg"></li>
<li><img src="http://images.sportsnetwork.com/nhl/specialevents/trade_deadline/cole_wings.jpg"></li>
<li><img src="http://images.sportsnetwork.com/nhl/specialevents/trade_deadline/yandle_rangers.jpg"></li>
<li><img src="http://images.sportsnetwork.com/nhl/specialevents/trade_deadline/glencross_capitals.jpg"></li>
<li><img src="http://images.sportsnetwork.com/nhl/specialevents/trade_deadline/vermette_blackhawks.jpg"></li>
</ul>
</td>
</tr>
</table>


