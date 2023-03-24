let stars = document.getElementById('star');
let moon = document.getElementById('moon');
let mountains3 = document.getElementById('mountains3');
let mountains4 = document.getElementById('mountains4');
let river5 = document.getElementById('river5');
let boat6 = document.getElementById('boat6');
let mountains7 = document.getElementById('mountains7');
let nouvil = document.querySelector('.nouvil');
window.onscroll = function (){
    let value =scrollY;
    stars.style. left = value +'px';
    moon.style.top=value * 3 +'px';
    mountains3.style.top=value * 2 +'px';
    mountains4.style.top=value * 1.5 +'px';
    river5.style.top=value *  +'px';
    boat6.style.top=value   +'px';
    boat6.style.left=value * 3 +'px';
   nouvil.style.fontSize =value  +'px';
   if (scrollY >= 67) {
   nouvil.style.fontSize = 67 +'px';
   nouvil.style.position = 'fixed';
   
   if (scrollY >= 478) {
    nouvil.style.display = 'none';
   
   } else {
    nouvil.style.display = 'block';
   }
   if (scrollY >= 127) {
    document.querySelector('.mian').style.background = 'linear-gradient(#376281,#10001f  )'  ;
   } else {
    document.querySelector('.mian').style.background = 'linear-gradient(#200016,#10001f  )'  ;
   }
}
}