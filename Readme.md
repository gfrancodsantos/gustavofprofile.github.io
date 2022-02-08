#iniciando meu primeiro portfolio profissional.

*{
    margin: 0;
    padding: 0;
    list-style: none;
    transition: all 1.2s;    
    text-decoration: none;
}

body{
    background-color: rgb(9, 0, 36);
    width: 100%;
}

.containertopo {
   position: fixed;
   width: 100%;
   height: auto;
   z-index: 1000;
}

.containertopo img {
    width: 75px;
    height: auto;
    float: left;
    margin-left: 17rem;  
    margin-top: 0.6rem;
    cursor: pointer;
}

.rotate-icon {
    -webkit-transition: -webkit-transform 0.3s ease-out;
    -moz-transition: -moz-transform 0.3s ease-out;
    -transition: -transform 0.3s ease-out;
}

.rotate-icon:hover {
   -webkit-transform: rotate(360deg);
   -moz-transform: rotate(360deg);   
    transform: rotate(360deg);
}

.menu ul {  
    text-align: right;    
    width: 100%;
    height: 5rem;
    background: linear-gradient(0deg, #002E59 -124.61%, rgba(36, 40, 44, 0) 100%);
    margin-top: 1rem;
}

.menu ul li {
    display: inline-block;
    position: relative;
    margin-top: 2rem;
    right: 17rem;
}


.menu li a {
    color: rgb(120, 127, 156);
    font-family:'Lucida Sans';   
    text-decoration: none;
    padding-right: 4rem;
}

.menu li a:hover {
    color: rgb(250, 245, 202);
    transition: 0.1s ease-in;
}

section {
    margin: 0px auto;
    padding: 100px 0px;
    max-width: 1000px;
}

.hero {
    display: flex;
    -webkit-box-pack: center;
    justify-content: center;
    -webkit-box-align: center;
    flex-direction: column;
    align-items: flex-start;
    min-height: 100vh;
    padding: 0px;
}
 
h1 {
    color: #D2D2D2;
    font-size: 5rem;
    margin-bottom: 25px;
    font-style: normal;
    font-weight:400px ;
    font-family: SeoulNamsan CB;
    margin-top: 15rem;
}

h2 {
  color: #717890;
  font-size: 5rem;
  margin-bottom: 30px;
  font-weight:400px ;
  font-style: normal;
  font-family: SeoulNamsan CB;
}

@font-face {
    font-family: Thabit;
    src: url('./FONTS/Thabit.ttf');
}

@font-face {
    font-family: SeoulNamsan CB;
    src: url('./FONTS/seoulnamsan-cb.ttf'); 
}

@font-face {
    font-family: Thabit;
    src: url('./FONTS/Thabit.ttf');
}

.sectionh p{
   color: #FFFFFF;
   font-size: 1rem; 
   font-family: Thabit;
   font-style: normal;
   width: 618px;
   margin-bottom: 15rem;
   position: relative;
}

.section1h1 {
    color: #676a75;
    font-size: 1.4375rem; 
    font-family: Thabit;
    font-style: normal;
    width: 618px;
    margin-bottom: 26px;
    max-width: 25rem;
}

#horizontal-line {
   margin-left: 10rem;
   width: 20rem;
   margin-bottom: -3.2rem;
}

#horizontal-line hr {
   border: solid 1px rgb(175, 175, 175, 13%);
}


.section1h2 { 
    color: #FFFFFF;
    font-size: 0,9375rem; 
    font-family: Thabit;
    font-style: normal;
    width: 618px;
    margin-bottom: 2rem;
 }

 .slang {
    color: #FFFFFF;
    font-size: 0,9375rem; 
    font-family: Thabit;
    font-style: normal;
    padding-top: 2rem;
 }

 .langs {
    color: #FFFFFF;
    font-size: 0,9375rem; 
    font-family: Thabit;
    font-style: normal;
    margin-bottom: 5rem;
    line-height: 2rem;
    display: flex;
 }


#containerlangs1 {
    display: inline-block;
    margin-right: 1rem;
}

#containerlangs2 {
    display: inline-block;
    margin-right: 1rem;
}

#containerlangs3 {
    display: inline-block;
    margin-right: 1rem;
}

#containerlangs4 {
    display: inline-block;
    margin-right: 1rem;
}

#containerlangs5 {
    display: inline-block;
    margin-right: 1rem;
}

#containerlangs6 {
    display: inline-block;
    margin-right: 1rem;
}

 #container-a1  {
    width: 10px;
    height: 10px;
    background: #fff500;
    display: inline-block;
 }

 #container-b1 {
    width: 10px;
    height: 10px;
    background: #fff500;
    display: inline-block;
 }
 
 #container-c1 {
    width: 10px;
    height: 10px;
    background: #fff500;
    display: inline-block;
 }
 
 #container-d1 {
    width: 10px;
    height: 10px;
    background: #fff500;
    display: inline-block;
 }

 #container-e1 {
    width: 10px;
    height: 10px;
    background: #fff500;
    display: inline-block;
 }

 #container-a2 {
    width: 10px;
    height: 10px;
    background: #fff500;  
    display: inline-block;
 }

 #container-b2 {
    width: 10px;
    height: 10px;
    background: #fff500;  
    display: inline-block;
 }

 #container-c2 {
    width: 10px;
    height: 10px;
    background: #fff500; 
    display: inline-block;
 }

 #container-d2 {
    width: 10px;
    height: 10px;
    background: #fff500; 
    display: inline-block;
 }

 #container-e2 {
    width: 10px;
    height: 10px;
    background: #fff500; 
    display: inline-block;
 }


 #container-a3 {
    width: 10px;
    height: 10px;
    background: #fff500;
    display: inline-block;
 }

 #container-b3 {
    width: 10px;
    height: 10px;
    background: #fff500;  
    display: inline-block;
 }

 #container-c3 {
    width: 10px;
    height: 10px;
    background: #ffffff;  
    display: inline-block;
 }

 #container-d3 {
    width: 10px;
    height: 10px;
    background: #ffffff; 
    display: inline-block;
 }

 #container-e3 {
    width: 10px;
    height: 10px;
    background: #ffffff; 
    display: inline-block;
 }

 #container-a4 {
    width: 10px;
    height: 10px;
    background: #fff500;  
    display: inline-block;
 }

 #container-b4 {
    width: 10px;
    height: 10px;
    background: #fff500;  
    display: inline-block;
 }

 #container-c4 {
    width: 10px;
    height: 10px;
    background: #ffffff; 
    display: inline-block;
 }

 #container-d4 {
    width: 10px;
    height: 10px;
    background: #ffffff; 
    display: inline-block;
 }

 #container-e4 {
    width: 10px;
    height: 10px;
    background: #ffffff; 
    display: inline-block;
 }

 #container-a5 {
    width: 10px;
    height: 10px;
    background: #fff500;
    display: inline-block;
 }

 #container-b5 {
    width: 10px;
    height: 10px;
    background: #fff500;   
    display: inline-block;
 }

 #container-c5 {
    width: 10px;
    height: 10px;
    background: #ffffff;   
    display: inline-block;
 }

 #container-d5 {
    width: 10px;
    height: 10px;
    background: #ffffff;   
    display: inline-block;
 }

 #container-e5 {
    width: 10px;
    height: 10px;
    background: #ffffff;   
    display: inline-block;
 }

 .container-la {
    margin-top: 3rem;
    width: 4.8rem;
    display: inline-block;
    line-height: 2rem;
 }
 

 .container-qq {
    margin-left: 10rem;
    margin-top: 50px;
    max-width: 8rem;
    line-height: 2rem;
    
 }

.containerff img:hover {
   -webkit-transform: scale(1.1);
   -ms-transform: scale(1.1);
    transform: scale(1.1);
 }

 .containerff img {
     margin-top: -11.2rem;
     width: 248px;
     height: 338px;
     margin-left: 20rem;
     display: inline-block;
     border-radius: 7px;   
     display: flex;
     position: relative;
     cursor: pointer;
 }

 .imageprofile {
   -webkit-filter: grayscale(70%);
 }

 .imageprofile:hover{
   -webkit-filter: grayscale(0%);
   transition: 1s;
 }

 .containerborder {   
   border: solid 3px rgb(7, 7, 7);
   border-radius: 7px;
   width: 240px;
   height: 320px;
   margin-left: -14rem;
   margin-top: -9rem;
 }

 .work {
   background: linear-gradient(360deg, #0F0927 18.17%, rgba(0, 33, 51, 0) 100%);
   width: 995px;
   height: 402px;
   margin-left: -2rem;
}
 .sectionwork {
   color: #676a75;
   font-size: 15px; 
   font-family: Thabit;
   font-style: normal;
   line-height: 12rem;
 }

 .work p {
   color: #FFFFFF;
   font-size: 0,9375rem; 
   font-family: Thabit;
   padding-top: 0.2rem;
   margin-left: 12rem;
   line-height: 1.5rem;
 }

 .work img {
    height: 133px;
    width: 133px;
    margin-left: 2rem;  
    padding-bottom: 1rem;
    border-radius: 2px;
    float: left;
    line-height:10rem;
    cursor: pointer;
 }

 .work2 {
   height: 133px;
   padding-top: 6rem;
 }

.work2 img{
   height: 133px;
   width: 133px;
   margin-left: 2rem;  
   padding-bottom: 1rem;
   border-radius: 2px;
   float: left;
   padding-top: 1rem;
   cursor: pointer;
}

.work2 p {
   padding-top: 1rem;
   margin-left: 12rem;
   font-size: 0,9375rem; 
   font-family: Thabit;

}

.fade {
   opacity:0.5;
}

.fade:hover {
   opacity:1;
}

.contact p {
   color: #676a75;
   font-size: 1.4375rem; 
   font-family: Thabit;
   margin-left: 25rem;
   padding-top: 5rem;
}

.contbox {
   margin-left: 23rem;
   max-width: 1rem;
}

.contbox2 {
   margin-right: 0rem;
   margin-bottom: 10rem;
   float: right;
   margin-top: -2.8rem;
}

.fa-github {
   color: rgb(182, 182, 182);
   margin-top: 5rem;
   font-size: 3rem;
  
}

.fa-linkedin {
   max-width: 1rem;
   color:rgb(182, 182, 182);
   font-size: 3rem;
}

.grow {
   position: relative;
   margin-right: 2rem;
   margin-left: 2rem;
}

.grow:hover {
   -webkit-transform: scale(1.1);
   -ms-transform: scale(1.1);
   transform: scale(1.1);
}

footer {
   background-color: #000000;
   width: 100%;
   height: 3rem;
   display: flex;
   position: relative;
}

footer p {
   color: #FFFFFF;
   font-size: 0,9375rem; 
   font-family: Thabit;
   font-style: normal;
   margin-left: 15rem;
   margin-top: 1rem;
   
}

.cel p {
   float: right;
   margin-right: 110rem;
   margin-top: 1rem;
}


@media (max-width: 2560px) {

   .cel p {
      margin-right: -98rem;
   }

   footer p {
      margin-left: 20rem;
   }

   #name {
      color: transparent
   }

   button {
      display: none;
   }

   .work img {
      border-end-start-radius: 50px;
      border-top-right-radius: 40px;
   }
}

@media (max-width: 1920px) {

   .cel p {
      margin-right: -68rem;
   }

   .work img {
      border-end-start-radius: 50px;
      border-top-right-radius: 40px;
   }
}

@media (max-width: 1900px) {
   .cel p {
      margin-right: -54rem;
   }

   .fa-github {
      font-size: 1.8rem;
      margin-top: 4rem;
      margin-left: 1rem;
   }

   .fa-linkedin {
      font-size: 1.8rem;
      margin-top: 1rem;
   }
   .work img {
      border-end-start-radius: 50px;
      border-top-right-radius: 40px;
   }
}

@media (max-width: 1440px) {

   .menu {
      width: 100%;
   }

   .containertopo img {
      float: left;
      margin-left: 5rem;
   }

   .containertopo ul li {
     float: right;
     margin-right: -13rem;
     padding-left: 12rem;
   }
  
   footer p {
      margin-left: 10rem;
   }

   .cel p {
      margin-right: -50rem;
   }

   #name {
      color: transparent;
   }

   .fa-github {
      font-size: 2rem;
      margin-left: 1rem;
   }

   .fa-linkedin {
      font-size: 2rem;
      margin-top: 0.75rem;
   }

   .work img {
      border-end-start-radius: 50px;
      border-top-right-radius: 40px;
   }
   
}

@media (max-width: 1280px) {

   .menu {
      width: 100%;
   }

   .containertopo img {
      float: left;
      margin-left: 5rem;
   }

   .containertopo ul li {
     float: right;
     margin-right: -13rem;
     padding-left: 12rem;
   }
   
   .hero h1 {
      margin-left: 10rem;
      font-size: 3.5rem;
   }

   .hero h2 {
      margin-left: 10rem;
      font-size: 3.5rem;
   }

   .sectionh {
      margin-left: 10rem;
      font-size: 1rem;
   }

   #horizontal-line {
      margin-left: 19rem;
      margin-bottom: -3rem;
      width: 12rem;
   }

   .section1h1 {
      margin-left: 10rem;
   }

   .section1h2 {
      margin-left: 10rem;
      font-size: 1rem;
      width: 23rem;
   }

   .slang {
      margin-left: 10rem;
      width: 23rem;
      font-size: 1rem;
   }

   .container-la {
      margin-left: 10rem;
      font-size: 1rem;
      width: 4.8rem;
   }
   .container-qq {
      line-height: 2rem;
      margin-top: 2.98rem;
   }

   .containerff {
      margin-left: -15rem;
      margin-top: -7rem;
   }

   .containerff img {
      width: 228px;
      height: 318px;
   }

   .containerborder {
      margin-top: -16rem;
      margin-left: -13rem;
      width: 220px;
      height: 300px;
   }

   .sectionwork {
      margin-left: 10rem;
   }

   .work {
      margin-left: 8rem;
      font-size: 1rem;
      width: 750px;
   }

   .work2 {
      font-size: 1rem;
   }

   .work p {
      width: 28rem;
   }

   .contact {
      margin-top: 2rem;
   }

   .contact p {
      text-align: right;
      margin-left: 26rem;
   }

   .contbox {
      margin-left: 25rem;
   }

   .contbox2 {
      margin-right: -0.70rem;
   }

   .fa-github {
      font-size: 2rem;
      margin-top: 5rem;
   }

   .fa-linkedin {
      font-size: 2rem;
      margin-top: 0.8rem;
   }

   footer p {
      margin-left: 6rem;
      font-size: 0.9rem;
   }

   .cel p {
      margin-right: -49rem;
      font-size: 0.9rem;
   }

   #btn-mobile {
   display: none;
   }

   #name {
      color: transparent;
   }

   .work img {
      border-end-start-radius: 50px;
      border-top-right-radius: 40px;
   }
}

@media (max-width: 1024px) {

   .fa-github {
      margin-left: -0.3rem;
   }

   .fa-linkedin {
      margin-left: -1.5rem;
   }

   .cel p {
      margin-right: -34rem;
   }

   .work img {
      border-end-start-radius: 50px;
      border-top-right-radius: 40px;
   }
}

@media (max-width: 768px) {

   * {
      max-width: 768px;
   }

   body {
      width: 768px;
   }

   section {
      overflow-x: hidden;
   }

   .containertopo {
      width: 100%;
      position: absolute;
   }

   .containertopo img {
      margin-left: 2rem;
   }

   #btn-mobile {
      position: absolute;
      display: block;
      margin-left: 40rem;
      width: 5rem;
      justify-content: center;
      align-items: center;
      margin-top: 1.2rem;   
      z-index: 10;
      color: white;
   }
   
   #btn-mobile {
      display: flex;
      padding: .5rem 1rem;
      font-size: 1rem;
      border: none;
      background: none;
      cursor: pointer;
      gap: .5rem;
      position: fixed;
      z-index: 180;
   }

   #hamburger {
      width: 20px;
      border-top: 2px solid;
      color: white;
      cursor: pointer;
      z-index: 180;      
   }

   #hamburger::after, #hamburger::before {
      content: '';
      display: block;
      width: 20px;
      height: 2px;
      background-color: currentColor;
      margin-top: 5px;
      transition: .3s;
      position: relative;
   }

   #nav.active #hamburger {
      border-top-color: transparent;
   }

   #nav.active #hamburger::before {
      transform: rotate(135deg);
   }

   #nav.active #hamburger::after {
      transform: rotate(-135deg);
      top: -7px;
   }

   .menu {
      width: 100%;
      display: flex;
   }

   .menu ul {
      background: none;
   }
   
   #menu {
      display: none;
      position: absolute;
      width: 45%;
      height: 100vh;
      top: 5rem;
      right: 0px;    
      flex-direction: column;
      text-align: center;
   }

   #nav {
      margin-top: 1rem;
      width: 768px;
      height: 5rem;
   }

   #menu li a {
      font-size: 1.1rem;
      display: flex; 
      margin-left: 9.5rem;
      align-items: center;
      justify-content: center;
      width: 10rem;
      margin-top: 5rem;
      text-decoration: none;
     }

   #nav.active #menu {
      display: flex;
      margin-right: -2rem;
      background-color: #101724;
      box-shadow: -10px 0px 30px -15px ;
      z-index: 150;
      position: fixed;
      height: 100%;
      margin-top: -5rem;  
   }

   .work img {
      border-end-start-radius: 60px;
      border-top-right-radius: 40px;
   }

   .containertopo img {
      width: 65px;
      height: auto;
      margin-top: 1rem;
   }

   .hero {
      margin-left: -4.3rem;
      width: auto;
   }

   .hero h1 {
      font-size: 3rem;
   }

   .hero h2 {
      font-size: 3rem;
   }

   .sectionh p {
      width: 35rem;
   }

   .section1h2 p {
      width: 22rem;
      text-align: justify;
   }

   .containerff img {
      width: 198px;
      height: 288px;
      margin-left: 16rem;
   }

   .containerborder {
      margin-left: -12rem;
      margin-top: -16rem;
      width: 210px;
      height: 270px;
   }

   .contact p {
      margin-left: 23.6rem;
      
   }

   .contbox {
      margin-left: 22.5rem;
   }

   .cel p {
      margin-right: -18rem;
   }

   #name {
      color: transparent;
   }

   footer {
      width: 100%;
   }
}

   @media (max-width: 720px) {
      .menu {
         width: 100%;
      }

      footer p {
         margin-left: 2rem;
      }

      section {
         overflow-x: hidden;
      }

      .cel p {
       margin-right: -22rem;
      }

      .contact p {
         margin-left: 23rem;
         
      }
   
      .containertopo {
         position: fixed;
      }

      .contbox {
         margin-left: 21.2rem;
      }
   
      .hero {
         margin-left: -6rem;
      }
   
      .hero h1 {
         font-size: 2.5rem;
      }
   
      .hero h2 {
         font-size: 2.5rem;
      }
   
      .sectionh p {
         width: 30rem;
         font-size: 0.8rem;
      }
   
      .section1h2 p {
         width: 22rem;
         text-align: justify;
         font-size: 0.8rem;
      }

      .slang p {
         font-size: 0.8rem;
      }
      
      .container-la p {
         font-size: 0.8rem;
      }

      .langs {
         width: 40rem;
         height: auto;
         
      }

      .work {
         width: 40.8rem;
      }

      .work p {
         font-size: 0.8rem;
      }

      .work img {
         border-end-start-radius: 80px;
         border-top-right-radius: 50px;
      }
      
      .containerff img {
         width: 168px;
         height: 230px;
         margin-left: 16rem;
         margin-top: -6rem;
      }
   
      .containerborder {
         margin-right: -33rem;
         margin-top: -12rem;
         width: 168px;
         height: 228px;
      }

      #nav.active #menu  {
         width: 25rem;
      }

      .fa-github {
         margin-left: 0.5rem;
      }
   }

   @media (max-width: 425px) {

      * {
         margin: 0;
         padding: 0;
         max-width: 425px;
         max-height: auto;
      }

      .menu ul {
         max-width: 425px;
         position: relative;
         margin-left: 0;
      }

      .containertopo {
         position: absolute;
      }

      .containertopo img {
         margin-left: 2rem;
         position: absolute;
      }

      section {
         overflow-x: hidden;
      }

      #btn-mobile {
         margin-left: 22.3rem;
      }

      .hero {
         margin-left: -7rem;
      }
   
      .hero h1 {
         font-size: 2.3rem;
         margin-top: 12rem;
      }
   
      .hero h2 {
         font-size: 2.3rem;
      }

      .sectionh p {
         width: 20rem;
      }

      .section1h1 {
         margin-top: -12rem;
      }

      #horizontal-line {
         margin-left: 18rem;
         width: 13rem;
         margin-top: -85rem;
         position: absolute;
      }

      .section1h2 p {
         width: 21rem;
         text-align: justify;
         text-justify: auto;
      }

      .containerff img {
         width: 180px;
         height: 240px;
         margin-left: -3rem;
         margin-top: -13rem;
       
      }
   
      .slang {
         margin-top: 18rem;
      }

      .slang p {
         width: 21rem;
      }

      .containerborder {
         margin-right: -20rem;
         margin-top: -21rem;
         width: 180px;
         height: 208px;
      }

      .work {
         width: 24rem;
         margin-left: 8.2rem;
      }

      .work p {
         display: none;
      }

      .work img {
         width: 200px;
         height: 200px;
         margin-left: 5.5rem;
         margin-top: -3rem;
         border-end-start-radius: 80px;
         border-top-right-radius: 60px;

      }

      .work2 img {
         width: 200px;
         height: 200px;
         margin-top: 4rem;
         margin-left: -12.5rem;
      }

      .sectionwork {
         margin-top: -5rem;
      }

      .fa-github {
         margin-left: 0.5rem;
      }

      .contact p {
         margin-left: 16.5rem;
         font-size: 1.2rem;
      
      }
   
      .contbox {
         margin-left: 14.9rem;
      }
   
      footer p {
         margin-left: 4rem;
      }

      footer {
         display: none;
      }

      #name {
         color: #717890;
         font-family: Thabit;
         justify-content: center;
         align-items: center;
         display: flex;
         margin-top: -5rem;
         font-size: 0.8rem;
      }

      #nav.active #menu  {
         width: 20rem;
      }
   }

   @media (max-width: 375px) {

      * {
         max-width: 375px;
         max-height: auto;
      }

      .menu {
         width: 100%;
      }

      body {
         margin-left: -1rem;
      }

      section {
         overflow-x: hidden;
      }
      
      #nav {
         width: 100%;
         margin-left: 1rem;
      }

      .containertopo {
         width: 375px;
         position: absolute;
      }

      .containertopo img {
         margin-left: 3rem;
      }

      #btn-mobile {
         margin-left: 18rem;
      }

      .hero {
         margin-left: -7rem;
      }
   
      .hero h1 {
         font-size: 2rem;
         margin-top: 12rem;
      }
   
      .hero h2 {
         font-size: 2rem;
      }

      .sectionh p {
         width: 19rem;
      }

      .section1h1 {
         margin-top: -12rem;
      }

      #horizontal-line {
         margin-left: 18rem;
         width: 10rem;
         margin-top: -85rem;
      }

      .section1h2 p {
         width: 19rem;
         text-align: justify;
         text-justify: auto;
      }

      .containerff img {
         width: 180px;
         height: 240px;
         margin-left: -4rem;
         margin-top: -13rem;
      }

      #containerlangs1 {
         margin-left: -2rem;
      }

      #containerlangs2 {
         margin-left: -2rem;
      }

      #containerlangs3 {
         margin-left: -2rem;
      }

      #containerlangs4 {
         margin-left: -2rem;
      }

      #containerlangs5 {
         margin-left: -2rem;
      }
   
      .slang {
         margin-top: 18rem;
      }

      .slang p {
         width: 21rem;
      }

      .containerborder {
         margin-right: -20rem;
         margin-top: -21rem;
         width: 180px;
         height: 208px;
      }

      .work {
         width: 20rem;
         margin-left: 9.5rem;
      }

      .work p {
         display: none;
      }

      .work img {
         width: 200px;
         height: 200px;
         margin-left: 4rem;
         margin-top: -3rem;

      }

      .work2 img {
         width: 200px;
         height: 200px;
         margin-top: 4rem;
         margin-left: -12.5rem;
      }

      .sectionwork {
         margin-top: -5rem;
      }

      .sectionwork p {
         font-size: 0.9rem;
         width: 20rem;
      }

      .contact p {
         margin-left: 13.5rem;
         font-size: 1rem;
         width: 10rem;
      }

      .fa-github {
         margin-left: 1.5rem;
      }

      .fa-linkedin {
         margin-left: 18rem;
      }
   
      .contbox {
         margin-left: 13.5rem;
      }
   
      footer p {
         margin-left: 4rem;
      }

      footer {
         display: none;
      }

      #name {
         color: #717890;
         font-family: Thabit;
         margin-left: 2rem;
         display: flex;
         margin-top: -5rem;
         font-size: 0.8rem;
      }
   }
