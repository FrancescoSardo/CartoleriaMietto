<script lang="ts" >
 import { onMount } from "svelte";
 import phone from "../assets/phone.png";
 import profile from "../assets/profile.png";
 import facebook from "../assets/Facebook.png";
 import whatsapp from "../assets/WhatsApp.png";
 import maps from "../assets/maps.png";
 import fax from "../assets/fax.png";
 
 import gmail from "../assets/gmail.png";
 import amazon from "../assets/amazon.png";
 import pay from "../assets/pay.png";
 import box from "../assets/box.png";
 import fotocopie from "../assets/fax2.png";
 import gradient from "../assets/gradient.png";

</script>
<div class="content">
 <div class="profile">
   <img src={profile} class="img" alt="." />
 </div>
 <div class="info">
   <div class="name" style="font-size: xx-large; color: white">
     Cartoleria Mietto
   </div>
   <div class="subname" style="text-align: center; color: white">Cartoleria Edicola
    Giocattoli</div>
 </div>

 <div class="element phone">
   <img src={phone} class="img" alt="" />
   <div class="text"><a href="tel:0183 651376">0183 651376</a></div>
 </div>
 <div class="element facebook">
   <img src={facebook} class="img" alt="" />
   <div class="text"><a href="https://www.facebook.com/CartoleriaMietto/?locale=it_IT">Cartoleria Mietto</a></div>
 </div>
 <div class="element whatsapp">
  <img src={whatsapp} class="img" alt="" />
  <div class="text"><a href= "tel:3277663329">327 76 63 329</a></div>
</div><div class="element maps">
 <img src={maps}  class="img" alt="" />
 <div class="text"><a  href="https://maps.app.goo.gl/sgQYb6ysN7HBm5cr5">Via Felice Cascione, 87</a></div>
</div><div class="element fax"> 
<img src={fax} class="img" alt="" />
<div class="text">Trasmissione e ricezione Fax</div>
</div>
<div class="element gmail">
<img src={gmail}   class="img" alt="" />
<div class="text"><a target="_top" href="mailto:miettocart@gmail.com" >miettocart@gmail.com</a></div>
</div>
<div class="element amazon">
<img src={amazon} class="img" alt="" />
<div class="text">punto di ritiro amazon</div>
</div>
<div class="element pay">
<img src={pay} class="img" alt="" />
<div class="text">
pagare bollettini: <br>
postali <br>
mav<br>
rav<br>
pagopa
</div>
</div>
<div class="element box">
<img src={box} class="img" alt="" />
<div class="text">Fare spedizioni con i migliori corrieri</div>
</div>
<div class="element fotocopie">
<img src={fotocopie} class="img" alt="" />
<div class="text">Trasmissione e ricezione Fax, Fotocopie colori e B/N Digitali
Timbri, Biglietti da visita, Rilegature e riparazioni Libri, Spiralature, Brossure, Plastificazioni a caldo A/3 - A/4
Stampe da Chiavetta da CD</div>
</div>
</div>
<style lang="scss">
*{
font-family: "Montserrat", sans-serif;
margin: 0;
border-radius: 0%;
}
img{
overflow: none;
}
.profile{
/* height: 100px; */
display: flex;
align-items: center;
justify-content: center;

}
a:visited {
text-decoration: none;
text-decoration-line: none;
color: inherit;
} 
a {
text-decoration: none;
text-decoration-line: none;
color: inherit;
}
.content {
padding-top: 1rem;
width: 100%;
height: 100vh;
background-color: #fec014;
display: flex;
flex-direction: column;
align-items: center;
gap: 1rem;
height: 120vh;

align-items: center;
}
.element {

box-sizing: border-box;
overflow-y: hidden;
width: 95%;
display: flex;
padding: 0.2rem;
align-items: center;
-webkit-box-shadow: 5px 5px 0px 0px #000000;
box-shadow: 5px 5px 0px 0px #000000;
color: white;

.text {
 text-align: center;
}
.img{
margin-left: 20px;
width: 40px;
height: 40px;
}
.text{
flex: 1;
}
height: fit-content;
}
.phone {
background-color: white;
.text {
 text-decoration: none;
 color: black;
}
} 
.box{
background: #7EB900;

}
.facebook {
background-color: #3f02ff;
}
.whatsapp{
background: #25B900;
}
.maps{
background-image:url("../assets/gradient.png");
}
.fax{
background-color: #88C7CC;
}
.gmail{
background-image: url("../assets/gradient.png") ;
}
.amazon{
background: #FE9901;

}
.pay{
background: #EC63D0;

}
.fotocopie{
background: #9EC8C1;

}


</style>
