<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>replit</title>
  <link href="style.css" rel="stylesheet" type="text/css" />
  <style>
    .nav {
      height: 70px;
      border-bottom: 1px solid black;
      display: flex;
      align-items: center;
    }
     
    .nav-right-items {
      display: flex;
      margin-left: auto;
    }

    .nav-item {
      margin-left: 10px;
    }

    .company-name {
      margin-left: 20px;
    }
      
    .title {
      text-align: center;
      font-size: 3.6rem;
      font-weight: 40px; 
    }
    
    .subtitle{
      font-size: 1.25rem;
      font-weight: 300;
    } 

    .main {
      width: 1000px;
      margin: 0 auto;
      margin-top: 60px;
    }

    .price-item {
      width: 300px;
      height: 350px;
      text-align: center;
      border: 1px solid black;
      margin: 20px;
      border-radius: 4px;
    }

    .prices {
      display: flex;
    }

    .price-item-title {
      font-size: 1.5rem;
      background: rgba(0, 0, 0,.03);
      height: 53px;
      line-height: 53px;
      border-bottom: 1px solid black;
    }

    .price-item-price{
      font-size: 2.5rem;
      font-weight: bold;
      padding: 20px;
    }
    .price-item-buttton{
      padding: .5rem 1rem;
      font-size: 1.25rem;
      line-height: 1.5;
      border-radius: .3rem;
      color: #007bff;
      background-color: transparent;
      background-image: none;
      border-color: #007bff;
      margin-top: 20px;
    }

    .price-item-button-active {
      background-color: #007bff;
      color: white;
    }
  </style>
</head>
<body>
  <div class="nav">
    <div class="company-name">
      IvyFosset Company
    </div>
    <div class="nav-right-items">
      <div class="nav-item">메뉴1</div>
      <div class="nav-item">메뉴2</div>
      <div class="nav-item">메뉴3</div>
      <div class="nav-item">메뉴4</div>
    </div>  
  </div>  
  <div class="main">
    <div class="title">
      Pricing
    </div>
    <div class="subtitle">
     Quickly build an effective pricing table for your potential 
     customers with this Bootstrap example. It's built with default 
     Botstrap components and utilities with little customization.
    </div>
  <div class="prices">
    <div class="price-item">
      <div class="price-item-title">
        free
      </div>
      <div class="price-item-price">
        $0 / mo
      </div>
      <div class="price-item-detail">
        10 users included
      </div>
      <div class="price-item-detail">
        2GB of storage
      </div>
      <div class="price-item-detail">
        Email support
      </div>
      <div class="price-item-detail">
        Help center access
      </div>      
      <button class="price-item-buttton">
        Clike me
      </button>  
    </div>
    
    <div class="price-item">
      <div class="price-item-title">
        Pro
      </div>
      <div class="price-item-price">
        $15 / mo
      </div>
      <div class="price-item-detail">
        20 users included
      </div>
      <div class="price-item-detail">
        10GB of storage
      </div>
      <div class="price-item-detail">
        Priority email support
      </div>
      <div class="price-item-detail">
        Help center access
      </div>      
      <button class="price-item-buttton price-item-button-active">
        Get started
      </button>  
    </div>
    
    <div class="price-item">
      <div class="price-item-title">
        Enterprise
      </div>
      <div class="price-item-price">
        $29 / mo
      </div>
      <div class="price-item-detail">
        30 users included
      </div>
      <div class="price-item-detail">
        15GB of storage
      </div>
      <div class="price-item-detail">
        Phone and email support
      </div>
      <div class="price-item-detail">
        Help center access
      </div>      
      <button class="price-item-buttton price-item-button-active">
        Contact us
      </button>  
    </div>
    
  </div>


  <script src="script.js"></script>

  <!--
  This script places a badge on your repl's full-browser view back to your repl's cover
  page. Try various colors for the theme: dark, light, red, orange, yellow, lime, green,
  teal, blue, blurple, magenta, pink!
  -->
  <script src="https://replit.com/public/js/replit-badge-v2.js" theme="dark" position="bottom-right"></script>
</body>

</html>
