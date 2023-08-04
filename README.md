# topbutton
This button has a back to top function.<br>
When the window scrolls down and the distance is greater than 20 from the scroll top, the button will be visible and back to the top while clicking the button.<br>
&lt;button onclick="Afunction()" id="myId" &gt;&lt;/button&gt;<br>
var VALUE = document.getElementById('valueId');<br>
window.onscroll = function(){scrollFunction()};<br>
function scrollFunction(){ if ( document.body.scrollTop >20 ||document.documentElement.scrollTop>20){VALUE.style.display="block";}else{VALUE.style.display="none";}}
function Afunction(){
document.body.scrollTop=0;
document.documentElement.scrollTop=0;
}
Some training and effects for jQuery.
    
