<!DOCTYPE html> 
<html dir="rtl" lang="ar">
<head> 
   <title>Examples</title>
   <meta charset="utf-8">  
</head> 
<body> 
<div class="menu">
    <ul>
        <li><a href="#who am i?">من انا ؟</a></li>
        <li><a href="#my hobbies">هواياتي</a></li>
        <li><a href="#my photography">من تصويري</a></li>
        <li><a href="#my favorite site">روابط</a></li>
    </ul>
</div>
<div class="main">
   
   <h1 id="who am i?">من انا؟</h1>
   <h2>محمد السويلم</h2>
  <h4>معلم حاسب<br></h4>
  <h4>معلم خبير من شركة مايكروسوفت<br></h4>
  <h4>هدفي نشر الوعي التقني في المجتمع <br></h4>
</div>

<div class="main">
   <h1 id="my hobbies"><p>هواياتي</p></h1>
<ul>
<h4>1- التصميم<br></h4>
<h4>2- القراءة<br></h4>
<h4>3- التصوير<br></h4>
</ul></div>
<div class="photos">
   <h1 id="my photography"><p>من تصويري</p></h1>
   <img src="https://th.bing.com/th?id=OIP.IpFfAH1dgDJcnTbDZvXhowHaFj&w=288&h=216&c=8&rs=1&qlt=90&o=6&dpr=1.5&pid=3.1&rm=2" width="250" height="150">
   <img src="https://th.bing.com/th/id/R.59b938cc034f0a8f13ea5346b494a9a3?rik=hL1tE2bL%2bIeSbw&riu=http%3a%2f%2fwww.parisnajd.com%2fbackgd%2fdata%2fmedia%2f2%2fAutumn-Brook-1024.jpg&ehk=0OD2UMRBTU%2biuw6j7VFjqZUt%2fBfHy8SyNQuKi9fOLWM%3d&risl=&pid=ImgRaw&r=0" width="250" height="150">
   <img src="https://media.istockphoto.com/photos/laptop-computer-on-a-table-defocused-apartment-living-room-picture-id539269297?k=6&m=539269297&s=170667a&w=0&h=oGRLceCKXPqn1AU9zk_ZGngUaFYPDnyNlR8QMNcdkCs=" width="250" height="150">
</div>

<div class="footer">
   <ul>
   <h1 id="my favorite site"><p>روابط</p></h1>
   <li><a href="https://www.youtube.com/">موقعي المفضل</a></li>
   <li><h3 id="contact-from.html"><a href="mailto:t836612@rb.moe.gov.sa">بريدي الاكتروني</a></h3></li>
   </ul></div>

   <style>
.menu {
   background-color: #6c3f23;
   overflow:auto; }

.main {
   overflow:auto;
    background-color: #fcfcfc; }

.photos {
   overflow:auto;
   background-color:#eee1bf; }

.footer { 
   overflow:auto;
background-color: #613a22; }   
   </style>
   <style>
      .main {
         overflow: auto;
         text-align: center;
         background-color: #f5f5f5;
         padding-bottom: 20px;
         padding-bottom: 2px;
      }

      .photos {
         overflow-y: auto;
         padding-top: 2px;
         text-align: center;
         background-color: #F0EDE4;
      }

      .footer {
         overflow-y: auto;
         padding-top: 2px;
         text-align: center;
         background-color: #6c3f23;
      }
   </style>

   <style>
      .photos img {
         border-style: solid;
         border-width: 2PX;
         border-color: #426C35;
         border-radius: 6PX;
         margin: 2px;
         object-fit: cover;
         object-position: top;
      }
   </style>
   <style>
      .menu UL {
         text-align: center;
         padding-top: 20PX;
         padding-bottom: 20PX;
         text-decoration: none;
      }
      .menu LI {
         display: inline-block;
         text-align: center;
      }
      .menu LI A {
         display: inline-block;
         height: auto;
         width: 150PX;
         color: #333333;
         background-color: #f5f5f5;
         padding: 10PX;
         margin: 4PX;
         text-align: center;
         font-size: 18PX;
         font-weight: bold;
         text-decoration: none;
         border-radius: 4PX;
      }
      .menu LI a:hover {
         background-color: #D6D599;
      }
   </style>
   <style>
      .footer ul {
         text-align: center;
         padding-top: 10px;
         padding-bottom: 10px;
         text-decoration: none;
      }
      .footer li {
         display: inline-block;
         text-align: center;
      }
      .footer li a {
         display: inline-block;
         height: auto;
         width: auto;
         color: #333333;
         background-color: #f5f5f5;
         padding: 10PX;
         margin: 4PX;
         text-align: center;
         font-size: 16px;
         font-weight: bold;
         text-decoration: none;
      }
      .footer li a:hover {
         background-color: #D6D599;
      }
   </style>
   <style>
      h1 {
         color: #426C35;
         font-weight: bold;
         font-size: 36px;
      }
      .main h2 {
         overflow: auto;
         margin-top: 4px;
         margin-left: auto;
         margin-right: auto;
         width: 200px;
         padding: 10px;
         background-color: #D6D599;
         color: #426C35;
         font-weight: bold;
         text-align: center;
         border-radius: 30px;
      }
      .photos h2 {
         color: #426C35;
         font-size: 28px;
      }
      .footer h2 {
         color: #D6D599;
      }
      .footer p {
         color: #f5f5f5;
      }
   </style>

</body>
</html>
