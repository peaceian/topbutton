# topbutton
This button has a back to top function.
&lt;button onclick="Afunction()" id="myId" &gt;&lt;/button&gt;<br>
var VALUE = document.getElementById('valueId');<br>
window.onscroll = function(){scrollFunction()};<br>
function scrollFunction(){ if ( document.body.scrollTop >20 ||document.documentElement.scrollTop>20){VALUE.style.display="block";}else{VALUE.style.display="none";}}
function Afunction(){
document.body.scrollTop=0;
document.documentElement.scrollTop=0;
}
    
