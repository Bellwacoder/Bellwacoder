<html>
<head>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" />
  <style>
    .navbar {
      background-color: lightblue;
      overflow: hidden;
    }

    .navbar a {
      float: left;
      display: block;
      color: black;
      text-align: center;
      padding: 14px 16px;
      text-decoration: none;
      font-size: 18px;
    }

    .navbar a:hover {
      background-color: transparent;
      color: #000;
    }

    .navbar .icon {
      display: none;
    }

    @media screen and (max-width: 600px) {
      .navbar a:not(:first-child) {
        display: none;
      }
      .navbar a.icon {
        float: right;
        display: block;
      }
    }

    @media screen and (max-width: 600px) {
      .navbar.responsive {
        position: relative;
      }
      .navbar.responsive .icon {
        position: absolute;
        right: 0;
        top: 0;
      }
      .navbar.responsive a {
        float: none;
        display: block;
        text-align: left;
      }
    }
  </style>




<!DOCTYPE html>
<html>
<head>
  <title>Bottom Bar Example</title>
  <style>
    body {
      margin: 0;
      padding: 0;
    }

    #bottom-bar {
      position: fixed;
      bottom: 0;
      left: 0;
      width: 100%;
      height: 50px;
      background-color: #f1f1f1;
      display: flex;
      justify-content: space-around;
      align-items: center;
    }

    .bottom-bar-icon {
      display: flex;
      flex-direction: column;
      align-items: center;
      cursor: pointer;
    }

    .bottom-bar-icon img {
      width: 28px;
      height: 28px;
    }
  </style>
</head>
<body>
  <div id="bottom-bar">
    <div class="bottom-bar-icon" onclick="window.location.href='home.html'">

     <img src='https://i.postimg.cc/85HbQTw4/25694-1.png' border='0' alt='25694-1'/></a>

     
      <span></span>
    </div>
    <div class="bottom-bar-icon" onclick="window.location.href='new.html'">

<img src='https://i.postimg.cc/br6xFLLw/images-3.png' border='0' alt='images-3'/></a> 


      
      <span></span>
    </div>
    <div class="bottom-bar-icon" onclick="window.location.href='help.html'">

     
<img src='https://i.postimg.cc/T3VLHCtq/more-106.png' border='0' alt='more-106'/></a>

     
      <span></span>
    </div>
    <div class="bottom-bar-icon" onclick="window.location.href='add.html'">

     
     <img src='https://i.postimg.cc/QMM79cqQ/images.png' border='0' alt='images'/></a>
     
      <span></span>
    </div>
  </div>
</body>
</html>

<div class="navbar" id="myNavbar">
  <a href="#home"><i class="fas fa-home"></i> Home</a>
  <a href="#new"><i class="fas fa-plus"></i> New</a>
  <a href="#trending"><i class="fas fa-fire"></i> Trending</a>
  <a href="javascript:void(0);" class="icon" onclick="myFunction()">
    <i class="fas fa-bars"></i>
  </a>
</div>

<script>
  function myFunction() {
    var x = document.getElementById("myNavbar");
    if (x.className === "navbar") {
      x.className += " responsive";
    } else {
      x.className = "navbar";
    }
  }
</script>

</body>
</html>
<html>

<head>
  <title>Online Selling App</title>
  <style>
    /* Body styles */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f2f2f2;
    }
    
    /* Header styles */
    header {
      background-color: #333;
      color: #fff;
      padding: 10px;
      text-align: center;
    }
    
    header h1 {
      margin: 0;
      font-size: 24px;
    }
    
    /* Main content styles */
    .container {
      max-width: 960px;
      margin: 20px auto;
      padding: 20px;
      background-color: #fff;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
    
    /* Product list styles */
    .product-list {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      grid-gap: 20px;
    }
    
    .product-card {
      border: 1px solid #ccc;
      padding: 10px;
      text-align: center;
      background-color: #fff;
    }
    
    .product-card img {
      max-width: 100%;
      height: auto;
    }
    
    .product-card h2 {
      font-size: 15px;
      margin: 10px 0;
    }
    
    .product-card p {
      margin: 0;
    }
    
    /* Footer styles */
    footer {
      background-color: #333;
      color: #fff;
      padding: 10px;
      text-align: center;
    }
  </style>
</head>

<body>

  
  <div class="container">
    <div class="product-list">
      <div class="product-card">

   <img src='https://i.postimg.cc/XJhTBK7D/355421230-1330517914231948-439652852102692988-n.jpg' border='0' alt='355421230-1330517914231948-439652852102692988-n'/></img>
      
        <h2>Product </h2>
        <p>$19.99</p>
         
            <form action="mailto:flapzon.contact@gmail.com" method="post" enctype="text/plain">
   
           <button href="#" class="button">GET</button>
     
      </div>
      <div class="product-card">

   <img src='https://i.postimg.cc/XJhTBK7D/355421230-1330517914231948-439652852102692988-n.jpg' border='0' alt='355421230-1330517914231948-439652852102692988-n'/></img>
       
        <h2>Product </h2>
        <p>$29.99</p>
           <button href="#" class="button">GET</button>
    
      </div>
      <div class="product-card">
    
      
         <img src='https://i.postimg.cc/XJhTBK7D/355421230-1330517914231948-439652852102692988-n.jpg' border='0' alt='355421230-1330517914231948-439652852102692988-n'/></img>
      
        <h2>Product </h2>
        <p>$39.99</p>
      
                 <button href="#" class="button">GET</button>
      </div>
      <!-- Add more product cards here -->
    </div>
  </div>
  
<html>
<head>
  <title>Product Page</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    
    header {
      background-color: #333;
      color: #fff;
      padding: 2px;
      text-align: center;
    }
    
    h1 {
      margin: 0;
    }
    
    main {
      padding: 20px;
    }
    
    .product {
      display: flex;
      align-items: center;
      margin-bottom: 20px;
    }
    
    .product img {
      width: 150px;
      margin-right: 30px;
      padding:10px;
    }
    
    .product-info {
      flex: 1;
    }
    
    .product-title {
      font-size: 24px;
      font-weight: italic;
      margin-bottom: 10px;
    }
    
    .product-description {
      font-size: 16px;
      margin-bottom: 10px;
    }
    
    .product-price {
      font-size: 20px;
      color: black;
      font-weight: bold;
    }

      .button {
            display: inline-block;
            background-color: #4CAF50;
            color: #fff;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 10px;
        }
 
 
 
  </style>
</head>
<body>
  <header>

  </header>
  
  <main>


    <div class="product">
    
   <img src='https://i.postimg.cc/XJhTBK7D/355421230-1330517914231948-439652852102692988-n.jpg' border='0' alt='355421230-1330517914231948-439652852102692988-n'/></img>  
     
     
      <div class="product-info">
        <h2 class="product-title">Product Title</h2>

        <p class="product-price">₹99.99</p>
           <button href="#" class="button">GET</button>
     
      </div>
    </div>
    
    <div class="product">
    
   <img src='https://i.postimg.cc/XJhTBK7D/355421230-1330517914231948-439652852102692988-n.jpg' border='0' alt='355421230-1330517914231948-439652852102692988-n'/></img>  
     
     
      <div class="product-info">
        <h2 class="product-title">Product Title</h2>

        <p class="product-price">₹99.99</p>
           <button href="#" class="button">GET</button>
     
      </div>
    </div> 
 
 
    <!-- Add more product divs as needed -->
  </main>
</body>
</html>
