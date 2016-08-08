# TechnoTutorial
INATECH Project

custom.css
@font-face {
    font-family: 'latobold';
    src: url('lato-bold-webfont.eot');
    src: url('lato-bold-webfont.eot?#iefix') format('embedded-opentype'),
         url('lato-bold-webfont.woff2') format('woff2'),
         url('lato-bold-webfont.woff') format('woff'),
         url('lato-bold-webfont.ttf') format('truetype'),
         url('lato-bold-webfont.svg#latobold') format('svg');
    font-weight: normal;
    font-style: normal;

}




@font-face {
    font-family: 'latolight';
    src: url('lato-light-webfont.eot');
    src: url('lato-light-webfont.eot?#iefix') format('embedded-opentype'),
         url('lato-light-webfont.woff2') format('woff2'),
         url('lato-light-webfont.woff') format('woff'),
         url('lato-light-webfont.ttf') format('truetype'),
         url('lato-light-webfont.svg#latolight') format('svg');
    font-weight: normal;
    font-style: normal;

}




@font-face {
    font-family: 'latomedium';
    src: url('lato-medium-webfont.eot');
    src: url('lato-medium-webfont.eot?#iefix') format('embedded-opentype'),
         url('lato-medium-webfont.woff2') format('woff2'),
         url('lato-medium-webfont.woff') format('woff'),
         url('lato-medium-webfont.ttf') format('truetype'),
         url('lato-medium-webfont.svg#latomedium') format('svg');
    font-weight: normal;
    font-style: normal;

}




@font-face {
    font-family: 'latoregular';
    src: url('lato-regular-webfont.eot');
    src: url('lato-regular-webfont.eot?#iefix') format('embedded-opentype'),
         url('lato-regular-webfont.woff2') format('woff2'),
         url('lato-regular-webfont.woff') format('woff'),
         url('lato-regular-webfont.ttf') format('truetype'),
         url('lato-regular-webfont.svg#latoregular') format('svg');
    font-weight: normal;
    font-style: normal;

}





body,
html {
    width: 100%;
    height: 100%;
}

body,
h1,
h2,
h3,
h4,
h5,
h6 {
    font-family: "Lato","Helvetica Neue",Helvetica,Arial,sans-serif;
    font-weight: 700;
}


#logo
{
    padding: 15px 0px 15px 0px;
    margin: 0px;    
}
.navbar-inverse
{ 
    border-radius:0px;
}
item,
.active,
.carousel-inner {
    height: 100%;
}
.navbar
{
    margin-bottom: 0px;
    background-color: #000;
    border-radius : 0px;
    border:none;
}
.navbar a
{
    color:#FFFFFF!important;
}

.navbar a:hover
{
    color:#838383 !important;
}
.dropdown-menu
{
    background-color:#000;
    color:#FFFFFF;
}

.intro-header
{
    padding-top: 50px; /* If you're making other pages, make sure there is 50px of padding to make sure the navbar doesn't overlap content! */
    padding-bottom: 50px;
    text-align: center;
    color: #f8f8f8;
    background: url('../images/clocklanding.jpg') no-repeat center center;
    background-size: cover;
}

.intro-message {
    position: relative;
    padding-top: 5%;
    padding-bottom: 10%;
}

.intro-message > h1
{
    margin: 0;
    text-shadow: 1px 1px 2px rgba(0,0,0,0.6);
    font-size: 5em;
    color: #CC0000;
    font-family: latobold, 'Helvetica Neue' , Helvetica, Arial, 'sans-serif !important';
    font-weight: bold;
}


.intro-message > h2
{
    margin: 0;
    text-shadow: 1px 1px 2px rgba(0,0,0,0.6);
    font-size: 4em;
    color: #000000;
    font-family: latobold, 'Helvetica Neue' , Helvetica, Arial, 'sans-serif !important';
    font-weight: bold;
}
.intro-divider
{
    width:90%;
    border-top: 1px solid #f8f8f8;
    border-bottom: 1px solid rgba(0,0,0,0.2);
    border-top-color: #000000;
    
}

.intro-message > h3
{
    color: #A40000;
}

.modal-content
{
    border-style: none;
    padding: 0px;
    margin: 0px;
    background-color: #FFFFFF;
    -webkit-border-radius: 6px 6px 0px 0px;
    -moz-border-radius: 6px 6px 0px 0px;
    border-radius: 6px 6px 0px 0px;
}

.modal-header
{
    border-style: none;
    background-color: #FF9933;
    -webkit-border-radius: 5px 5px 0px 0px;
    -moz-border-radius: 5px 5px 0px 0px;
    border-radius: 5px 5px 0px 0px;
}
.carousel
{
    border-style: ridge none none none;
    border-width: 1px;
    border-color: #669999;
}




.section-title {
padding-bottom:70px;
padding-top:30px;
}

.section-title h1
{
    position: relative;
    font-size: 36px;
    margin-bottom: 24px;
    padding-bottom: 22px;
    text-transform: capitalize;
    color: #009900;
}

.section-title h1 span {
font-weight: 300;
}

.section-title h1:before, .section-title h1:after
{
    content: "";
    position: absolute;
    left: 50%;
}

.section-title h1:before
{
    background-color: #e2e2e2;
    bottom: 0;
    height: 1px;
    margin-left: -51px;
    width: 102px;
}

.section-title h1:after {
width: 5px;
height: 5px;
bottom: -2px;
border-radius: 50%;

}


/*========================
====== Our Services ======
==========================*/

#our-services .col-sm-6.col-md-3
{
    border-right: 1px solid #e2e2e2;
    position: relative;
}

#our-services .col-sm-6.col-md-3:nth-of-type(4n)
{
    border-right: none;
}

#our-services .col-sm-6.col-md-3:nth-of-type(1), #our-services .col-sm-6.col-md-3:nth-of-type(2), #our-services .col-sm-6.col-md-3:nth-of-type(3), #our-services .col-sm-6.col-md-3:nth-of-type(4)
{
    border-bottom: 1px solid #e2e2e2;
}

#our-services .col-sm-6.col-md-3:nth-of-type(1):before, #our-services .col-sm-6.col-md-3:nth-of-type(2):before, #our-services .col-sm-6.col-md-3:nth-of-type(3):before
{
    position: absolute;
    content: "";
    right: -3px;
    bottom: -3px;
    width: 5px;
    height: 5px;
    z-index: 99;
    border-radius: 50%;
}

.service-content {
padding: 45px 0 30px;
}


.service-content i
{
    font-size: 36px;
    color: #009933;
}

.service-content h2 {
font-size: 18px;
font-weight: 500;
margin: 34px 0 18px;
}

.height
{
    height : 40px;
   
}

/*========================
=======our-clients ======
==========================*/
.our-clients
{
    border: 1px solid #339966;
    padding: 45px 0;
    margin-bottom: 25px;
}

.our-clients ul li {
display:inline-block;
width:17.5%;
}

.our-clients ul li a img{
filter: url("data:image/svg+xml;utf8,<svg xmlns=\'http://www.w3.org/2000/svg\'><filter id=\'grayscale\'><feColorMatrix type=\'matrix\' values=\'0.3333 0.3333 0.3333 0 0 0.3333 0.3333 0.3333 0 0 0.3333 0.3333 0.3333 0 0 0 0 0 1 0\'/></filter></svg>#grayscale"); /* Firefox 10+, Firefox on Android */
    filter: gray;
    -webkit-filter: grayscale(100%);
-webkit-transition: all 0.3s ease-in-out;
-moz-transition: all 0.3s ease-in-out;
-ms-transition: all 0.3s ease-in-out;
-o-transition: all 0.3s ease-in-out;
transition: all 0.3s ease-in-out;
display:inline-block;
opacity:0.6;
}

.our-clients ul li a img:hover{
filter: url("data:image/svg+xml;utf8,<svg xmlns=\'http://www.w3.org/2000/svg\'><filter id=\'grayscale\'><feColorMatrix type=\'matrix\' values=\'1 0 0 0 0, 0 1 0 0 0, 0 0 1 0 0, 0 0 0 1 0\'/></filter></svg>#grayscale");
    -webkit-filter: grayscale(0%);
opacity:1;
}


/*========================
==== Contact Section =====
==========================*/
#contact {
padding-bottom: 62px;
}

#gmap {
height:458px;
margin-bottom: 67px;
}

.contact-info i {
font-size: 36px;
}

.contact-info h2 {
font-size: 14px;
color: #838383;
font-weight: 700;
}

.contact-info a,
.contact-info span {
color: #838383;
font-size: 16px;
font-weight: 300;
}

.contact-info span {}

#contact-form {
margin-top: 86px;
}

#contact-form h2 {
font-size: 22px;
color: #323232;
margin-bottom: 32px;
}

#contact-form h2 span {
font-weight: 300;
}

#contact-form input,
#contact-form textarea {
border: 1px solid #e0e0e0;
box-shadow: none;
margin-bottom: 25px;
height: 38px;
font-size: 16px;
}

#contact-form textarea {
height: 196px;
}

#contact-form button {
height: 40px;
width: 145px;
line-height: 40px;
padding: 0;
}

.form-control:focus, 
#contact-form input:focus,
#contact-form textarea:focus {
border-color:#9d5468;
box-shadow:none;
}


/*========================
==== Footer Section ======
==========================*/

.footer-widget-wrapper
{
    padding: 57px 0 20px;
    border-top: 1px solid #dfdfdf;
    position: relative;
    background-size: cover;
}

.footer-widget-wrapper:before {
position: absolute;
top: -4.5px;
left: 50%;
margin-left: -4.5px;
content: "";
width: 9px;
height: 9px;
border-radius: 50%;
box-shadow: 0 0 0 6px #f0f0f0;
}

.footer-widget {
margin-bottom: 30px;
}

.footer-widget h1
{
    font-size: 18px;
    position: relative;
    margin-bottom: 30px;
    margin: 3px 0 30px;
    color: #009900;
}

.footer-widget h1:before,
.footer-widget h1:after {
position: absolute;
content: "";
}

.footer-widget h1:before
{
    top: 9px;
    right: 0;
    width: 40%;
    height: 1px;
    background: #009900;
}

.footer-widget h1:after {
width: 5px;
height: 5px;
right: 40%;
top: 6.5px;
margin-right: -2.5px;
border-radius: 50%;
}

.footer-widget h1 span {
font-weight: 300;
}

.contact-widget i, .twitter-widget i {
font-size: 24px;
margin-right: 12px;
}

.footer-logo {
margin-bottom: 25px;
display: block;
background-repeat: no-repeat;
background-position: left top;
height: 30px;
width: 130px;
}

.text-widget p {
margin-bottom: 22px;
}

.social {}

.social li {
margin: 0 10px;
}

.social li:first-child {
margin-left: 0;
}

.social li:last-child {
margin-right: 0;
}

.social li a
{
    color: #FFFFFF;
    font-size: 20px;
}
.social li a:hover
{
    color:#669999 !important;
}

.twitter-widget p:first-child {
margin-bottom: 15px;
}

.instagram-widget i {
font-size: 24px;
margin-right: 12px;
}

.instagram-widget p:first-child {
margin-bottom: 15px;
}

.instagram {
    margin: 0 -8px;
}

.instagram li {
display: inline-block;
margin: 0 7.5px 20px;
}

.instagram li a {
    display: block;
}

.instagram li a img {
width: 75px;
height: 75px;
border-radius: 50%;
}

.instagram li a {
position: relative;
}

.instagram li a:before {
position: absolute;
top: 0;
left: 0;
content: "";
z-index: 99;
width: 100%;
height: 100%;
border-radius: 50%;
-webkit-transform: scale(0);
-moz-transform: scale(0);
-ms-transform: scale(0);
-o-transform: scale(0);
transform: scale(0);
-webkit-transition: all 300ms ease;
-moz-transition: all 300ms ease;
-ms-transition: all 300ms ease;
-o-transition: all 300ms ease;
transition: all 300ms ease;
}

.instagram li a:hover:before {
-webkit-transform: scale(1);
-moz-transform: scale(1);
-ms-transform: scale(1);
-o-transform: scale(1);
transform: scale(1);
}

.footer-bottom
{
    padding: 25px 0 15px;
    background-color:#000;
}

.footer-bottom a, .footer-bottom p {
color: #fff;
}

.footer-bottom a:hover {
color: #000;
}

.footer-menu li {
padding: 0 20px;
}

.footer-menu li:first-child {
padding-left: 0;
}

.footer-menu li:last-child {
padding-right: 0;
}

.footer-menu li a {
font-size: 14px;
-webkit-transition: all 0.3s ease-in-out;
-moz-transition: all 0.3s ease-in-out;
-ms-transition: all 0.3s ease-in-out;
-o-transition: all 0.3s ease-in-out;
transition: all 0.3s ease-in-out;
}

.footer-menu li a:hover {}

.copy-right p strong {
font-weight: 500;
}

.copy-right a {
color: #000;
-webkit-transition: all 0.3s ease-in-out;
-moz-transition: all 0.3s ease-in-out;
-ms-transition: all 0.3s ease-in-out;
-o-transition: all 0.3s ease-in-out;
transition: all 0.3s ease-in-out;
}

.copy-right a:hover {
color: #fff;
}

@media(max-width:767px) {
    .intro-message {
        padding-bottom: 15%;
    }

    .intro-message > h1 {
        font-size: 3em;
    }
   .intro-message > h2
   {  
    font-size: 3em;
   }   

    ul.intro-social-buttons > li {
        display: block;
        margin-bottom: 20px;
        padding: 0;
    }

    ul.intro-social-buttons > li:last-child {
        margin-bottom: 0;
    }

    .intro-divider {
        width: 100%;
    }    
    #logo
    {
    text-align:center;   
    }
}

/* Html chapter*/
.htmlmenu
{
    align-content:center;
}
.htmlmenu a{
    background-color:#000;
    color: white;
    padding: 25px 25px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    text-decoration-style: solid;
}

/*Html content*/
.htmlcontent1
{    text-align:justify;
     padding-left:50px;
     padding-right:50px;
    font-family:'Times New Roman';
    color:#000;
}
/*Registration*/
.signuptable {
    position:relative;
    border:double;
    height:80%;
    width:50%;
    margin:auto;
    padding:10px;
    padding-left:30%;
    margin-top:5%;
    
}
.titleone {
border-bottom:double;
font-size:30px;
background-color:rgb(204, 102, 0);
    
}
.signuptitle {
    position:relative;
    text-align:center;
    padding-top:0.7%;
    margin:auto;
    margin-top:125px;
    width:350px;
    min-width:30%;
    font: 30px  Georgia, serif;
    color:white;
    background-color:#000;
    
    border-radius:20px 20px 0px 0px;
    border:solid;
    border-color:#838383;
    /*border-bottom:none;*/
    
}
.signupcontent {
    position:relative;
    text-align:center;
    margin:auto;
    /*margin-top:30px;*/
    width:350px;
    min-width:30%;
    border:solid;
    border-top:none;
    border-color:#838383;
    border-radius:0px 0px 20px 20px ; 
}

.spacer{
    margin-top:1em;
}
