# UIUX
**COMPANY**: CODTECH IT SOLUTIONS
**NAME**: S.DHANARAKSHANA
**INTERN ID**:CTO4WT166
**DOMAIN**: UIUX
**DURATION**: 4 WEEKS
**MENTOR**: NEELA SANTHOSH

#DESCRIPTION OF TASK 
Objective:
To redesign the landing page of eBay.com with a focus on enhancing both usability and visual appeal, making the interface cleaner, more modern, and user-friendly.

Tasks Performed:
Analysis of Current Design:

Reviewed the existing eBay homepage.

Identified usability pain points such as cluttered layout, inconsistent spacing, and overwhelming information density.

Took note of key features that needed to be retained (search bar, categories, deals, etc.).

Wireframing and Layout Planning:

Created low-fidelity wireframes to establish a cleaner structure.

Focused on better visual hierarchy, simplified navigation, and clear call-to-action areas.

UI Redesign:

Designed a new visual style using a modern, minimalistic aesthetic.

Used consistent spacing, intuitive icons, and more whitespace for a clean look.

Redesigned the header with a fixed search bar, clear sign-in/cart buttons, and a dropdown for categories.

Improved the product highlights section with larger images, simplified text, and a focus on current deals.

Final Touches:

Refined typography and color palette for accessibility and consistency.

Ensured the layout is responsive and mobile-friendly.

##OUTPUT

![Image](https://github.com/user-attachments/assets/cac47306-5bb2-4a54-9ccb-f1141f10dd33)





COMPANY: CODTECH IT SOLUTIONS NAME: S.DHANARAKSHANA INTERN ID:CTO4WT166 DOMAIN: UIUX DURATION: 4 WEEKS MENTOR: NEELA SANTHOSH

#DESCRIPTION OF TASK Objective: 

Responsive Cake Ordering Website – Landing Page Description:

The landing page features a clean, responsive layout with a fixed top navigation bar containing five simple links: Home, Buy, Service, About, and Contact.Below the navbar, a grid of cake cards showcases different cake options.The card layout adjusts gracefully across screen sizes for an optimal browsing experience on mobile, tablet, and desktop.

The design is simple, user-friendly, and visually sweet—focused on making cake selection quick, appealing, and effortless.

"I’m building a visually appealing, responsive cake ordering website using HTML, CSS, and JavaScript, with special emphasis on showcasing daily offers and creating an engaging user experience.

<!DOCTYPE html>
<html lang="en">
   <head>
       <meta charset="UTF-8">
       <meta http-equiv="X-CA-compatible" content="IE-edge">
       <meta name="viewport" content="width=device-width" initial-scale="1.0">
       
       <title>Responsive cake website</title>
       <link rel="stylesheet" type="text/css" href="css/style.css">

<style type="text/css">
       *{
        text-decoration:none;
       }
       .navbar{
        background: crimson; font-family: calibri; padding-right: 15px; padding-left: 15px;
       }
       .navdiv{
        display: flex; align-items: center; justify-content: space-between;
       }
       li{
        list-style: none; display: inline-block;
       }
       li a{
        color:green; font-size: 20px; font-weight: bold; margin: 65px;
       }
       button{
        background-color: red; margin-left: 10px; border-radius: 10px; padding: 10px; width: 90px;
       }
       button a{
        color: white; font-weight: bold; font-size: 15px;
       }
       
       /*change the color of the links on hover*/
       .topnav a:hover{
        background-color: #ddd;
        color: red;
    }
    .my_cover{
        width: 100%;
        height: 550px;
        object-fit: cover;
    }

    .container{
        width: 100%;
        height: 550px;
        position: relative;
    }
    
    *{
        margin: 0px;
        padding: 5px;
        box-sizing: border-box;
        font-family: sans-serif;
    }
    body{
        background-color:rgb(250, 249, 248);
    }
    .card-container{
        display: flex;
        justify-content: center;
        flex-wrap: wrap;
        margin-top: 50px;
    }
    .card{
        inline-size: 20px;
        width: 200px;
        margin: 10px;
        background-color: rgba(245, 222, 179, 0.685);
        border-radius: 20px;
        overflow: hidden;
        box-shadow: 0px 2px 4px rgba(0,0,0,0.2);
    }
    .card img{
        width: 100%;
        height: auto;
        border-radius: 4px;
    }
    .card.content h3{
        font-size: 28px;
        margin-bottom: 8px;
    }
    .card.content p{
        font-size: 15px;
        line-height: 1.3;
    }
    .card.content .button{
        border: #666;
        display: inline-block;
        padding: 8px 16px;
        background-color: #333;
        text-decoration:none;
        border-radius: 4px;
        margin-top: 16px;
        color: #b1afaf;
    }
   
    *{
        box-sizing: border-box;
    }
   .column{
         float: left;
         width: 33.33%;
         padding: 5px;
   }
  .row::after{
       content:"";
       display: table;
       clear: both;
  }
    </style>
       <!--navbar-->
       <div class="topnav" id="mytopnav">
        <ul>
            <li><a href="active" style="color: rgb(20, 133, 69);">Cake Bake</a></li>
        <li><a href="active">Home</a></li>
        <li><a href="#service">Service</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#contact">Contact</a></li>
        <button><a href="#buy">Buy</a></button>
    </ul>
  </div> <br>
   </head>
  
   <body>
    <div class="container">
        <img class="my_cover" src="cake cover.png"  >
    </div>
<div class="card-container">
    <div class="card">
        <img src="canvacake1.png">
        <div class="card-content">
            <h3>Card 1</h3>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. </p>
        <a href="" class="button">Read More</a>
    </div>
    </div>

    <div class="card">
        <img src="canvacake2.png">
        <div class="card-content">
            <h3>Card 2</h3>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. </p>
        <a href="" class="button">Read More</a>
    </div>
    </div>

    <div class="card">
        <img src="canvacake3.png">
        <div class="card-content">
            <h3>Card 3</h3>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. </p>
        <a href="" class="button">Read More</a>
    </div>
    </div>

    <div class="card">
        <img src="newcake.png">
        <div class="card-content">
            <h3>Card 4</h3>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit.</p>
        <a href="" class="button">Read More</a>
    </div>
    </div>

    <div class="card">
        <img src="newcake2.png">
        <div class="card-content">
            <h3>Card 5</h3>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit.</p>
        <a href="" class="button">Read More</a>
    </div>
    </div>
    
    <div class="card">
        <img src="newcake3.png">
        <div class="card-content">
            <h3>Card 6</h3>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit.</p>
        <a href="" class="button">Read More</a>
    </div>
    </div>
</div>
<br>
     <h1 style="color: red; text-align: center; background-color: gainsboro;">TODAY'S OFFER</h1>
     <br>
     <img src="cookie.png" height="200px" width="185px">
     <img src="cuppie.png"height="200px" width="185px">
     <img src="croissant.png"height="200px" width="185px">
     <img src="sponch cake slice.png"height="200px" width="185px">
     <img src="brownie.png"height="200px" width="185px">
     <img src="cheesecake.png"height="200px" width="185px">
     <img src="fruitcake.png"height="200px" width="185px">
     <br>
     <h2 style="font-size: larger; color: #8f6666; text-align: center; ">We are exicted to bake for you Today! and Everyday</h2>
     <h1 style="color: #6d4a4a; font-size: bold; text-align: center;">Delicious and Tasty Cakes</h1>
     <h3 style="color: #573b3b; font-size: small; text-align: center;">A Party without cake is really just a meeting</h3>
     <h1 style="color:#472e2e; font-size: smaller; text-align: center;">The taste of Home-Baked goodness to enrich every moment. </h1>
     <br>
  <div class="row">
<div class="column">
  <img class="leftside" src="leftside image.png" width="100%">
</div>
<div class="row">
    <div class="column">
      <img class="leftside" src="wedding cake.png" width="100%">
    </div>
    <div class="row">
        <div class="column">
          <img class="leftside" src="cupcakes grp.png" width="100%">
        </div>   
</div> 
 
   </body>
   <h1 style="color: green; text-align: center;">CAKE BAKE</h1>
   <h2 style="color: green; text-align: center;">12/32, ABC Road, Mumbai, India</h2>
   <h2 style="color: green; text-align: center;">Email: cakebakeindia@gmail.com</h2>
   <h2 style="color: green; text-align: center;">+91 1234567891</h2>
   <h2 style="color: green; text-align: center;">Insta:Cake Bake India</h2>
   <h2 style="color: green; text-align: center;">Whatsapp:+91 0987654321</h2>
   <script src="main.js"></script>
</html>


 ##OUTPUT

![Image](https://github.com/user-attachments/assets/94aadd4e-5091-40bd-a5aa-a01e358fe184)

![Image](https://github.com/user-attachments/assets/48b2203d-251c-4ebc-bb21-e2d17a8dfa0b)

![Image](https://github.com/user-attachments/assets/0fb208cc-09a6-41c0-89db-ed4a3a9e1018)

![Image](https://github.com/user-attachments/assets/cee533c1-1f2a-4323-9f87-c253bd9ca3d0)

![Image](https://github.com/user-attachments/assets/d680c06e-1512-4e15-a20d-4afa25e71941)










