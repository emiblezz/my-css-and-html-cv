
<html lang="en">
<!-- my in-line css code-->
<style>
<!-- the main div -->
   .container{
   width: 100%;
   height: auto;
   display: flex;
   flex-direction:row;
   flex-wrap:wrap;
   justify-content:flow-start;
  
   
} 
.bio {
background-size:0 auto;
background-color: red;
color:blue;
padding:15px 20px;
margin-top:5px;
margin-bottom:5px;
margin-left=12px;
width:33.33%;
height:333px;
flex-direction: row;
box-shadow:0px 10px 10px rgba(0,0,0,0.6);
} 
.bio:hover{
background-color:green;
}
.education{
background-size:33.33px;
background-color: #fff000;
color:#00ff00;
padding:15px 25px;
margin-top:15px;
margin-bottom:15px;
margin-left:575px;
width:33.33%;
height:333px;
flex-direction: row;
box-shadow:0px 10px 10px rgba(0,0,0,0.6);
}
.education:hover{
background-color:pink;
}
.hobbies{
background-size: 0 auto;
background-color: gray;
color:#fff000;
padding:15px 25px;
margin-top:0px;
margin-bottom:5px;
margin-left:0px;
width:33.33%;
height:333px;
flex-direction: column;
box-shadow:0px 10px 10px rgba(0,0,0,0.6);
}
.hobbies:hover{
background-color:chocolate;
}
.contact{
background-size: 15px;
background-color: purple;
color:green;
padding:15px 20px;
margin-top:0px;
margin-bottom:5px;
margin-left:500px;
width:33.33%;
height:333px;
flex-direction: row;
box-shadow:0px 10px 10px rgba(0,0,0,0.6);
}
.contact:hover{
background-color:#000;
}
.photo{
background-size: 0;
background: linear-gradient(pink,blue);
color:green;
padding:15px 20px;
margin-top:5px;
margin-bottom:0px;
margin-left:500px;
width:33.33%;
height:333px;
flex-direction: row;
box-shadow:0px 10px 10px rgba(0,0,0,0.6);
}
.photo:hover{
background:gray;
}

</style>
<!-- the heading -->
<head>
   <meta charset="UTF-8">
   <link rel="shortcut icon" type="image/png" href="https://media-exp2.licdn.com/dms/image/C5603AQEjlsgLPej7wA/profile-displayphoto-shrink_200_200/0/1624454506617?e=2147483647&v=beta&t=0vVF6Jpprc4wJWm1BXVWp_OyJB-Kv1D9eGKx4Pd_big">
</head>
<!-- the body -->
<body>
<!-- this div is the main div container -->
<div class="container">
<!-- the children div begin from here -->
<a href="https://emiblezz.github.io/my-Bio-Data/">
<div class="bio">
<h>MY PERSONAL INFORMATION</h>
</div>
</a>

   <a href="https://emiblezz.github.io/my-photo/">
   <div class="photo">
   <h>MY PHOTO</h>
   </div>
   </a>
   
   <a href="https://emiblezz.github.io/my-education/">
      <div class="education">
      <h>MY EDUCATION BACKGROUND</h>
      </div>
      </a>
      
      <a href="https://emiblezz.github.io/hobbies/">
         <div class="hobbies">
         <h>MY HOBBIES</h>
          </div>
         </a>
        
         <a href="https://emiblezz.github.io/CONTACTS-FORM/">
            <div class="contact">
            <h>CONTACT US</h>
            </div>
         </a>
            
</div>
</body>
</html>
