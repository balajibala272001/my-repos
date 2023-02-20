<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Grocery Website</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@8/swiper-bundle.min.css" />
  <link rel="stylesheet" href="style.css">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
  <link href="https://fonts.googleapis.com/css2?family=Roboto+Slab:wght@300&family=Rubik:wght@300&display=swap"
    rel="stylesheet">
</head> 
 
<body>
  <!-- header section start -->
  <header class="header">
    <a href="#" class="logo"><i class="fas fa-shopping-basket"></i>Vivekananda stores</a>
<link href="style.css" rel="stylesheet">
    <nav class= "navbar">
      <a href="index.html">Home</a>
      <a href="features.html">Features</a>
      <a href="products.html">Products</a>
      <a href="categories.html">Categories</a>
      
    </nav>
    <div class="icons">
      <div class="fas fa-bars" id="menu-btn"></div>
      <div class="fas fa-search" id="search-btn"></div>
      <div class="fas fa-shopping-cart" id="cart-btn"></div>
      <div class="fas fa-user" id="login-btn"></div>
    </div>

    <form action="" class="search-form">
      <input type="search" id="search-box" placeholder="search here...">
      <label for="search-box" class="fas fa-search"></label>
    </form>
    <div class="shopping-cart">
      <div class="box">
        <i class="fas fa-trash"></i>
        <img src="/assets/img/cart-img-1.png" alt="">
        <div class="content">
          <h3>watermelon</h3>
          <span class="price">$4.99/-</span>
          <span class="quantity">qty : 1</span>
        </div>
      </div>
      <div class="box">
        <i class="fas fa-trash"></i>
        <img src="/assets/img/cart-img-2.jpg" alt="">
        <div class="content">
          <h3>onion</h3>
          <span class="price">$4.99/-</span>
          <span class="quantity">qty : 1</span>
        </div>
      </div>
      <div class="box">
        <i class="fas fa-trash"></i>
        <img src="/assets/img/cart-img-3.jpg" alt="">
        <div class="content">
          <h3>chicken</h3>
          <span class="price">$4.99/-</span>
          <span class="quantity">qty : 1</span>
        </div>
      </div>
      <div class="total"> total : $19.69/-</div>
      <a href="#" class="btn">checkout</a>
    </div>

    <form action="" class="login-form">
      <h3>login now</h3>
      <input type="email" placeholder="your email" class="box">
      <input type="password" placeholder="your password" class="box">
      <p>forget your password <a href="#">click here</a></p>
      <p>don't have an account <a href="#">create now</a></p>
      <input type="submit" value="login now" class="btn">
    </form>
  </header>
  <!-- header section ends  -->
  <!-- home section start -->

  <section class="home" id="home">


    <div class="content">
      <h3>fresh and <span>organic</span> products for your</h3>
      <p>To Deliver a Good product in Good Quality At a reasonable price.</p>
      <a href="#" class="btn">shop now</a>

    </div>
  </section>

  <!-- home section end -->

  

  <!-- footer section start -->

  <section class="footer">

    <div class="box-container">

      <div class="box">

        <h3> groco <i class="fas fa-shopping-basket"></i></h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloribus, aliquid.</p>
        <div class="share">
          <a href="#" class="fab fa-facebook-f"></a>
          <a href="#" class="fab fa-twitter"></a>
          <a href="#" class="fab fa-instagram"></a>
          <a href="#" class="fab fa-linkedin"></a>
        </div>
      </div>
      <div class="box">

        <h3>contact info</h3>
        <a href="#" class="links"> <i class="fas fa-phone"></i> +123-456-7890 </a>
        <a href="#" class="links"> <i class="fas fa-phone"></i> +123-222-3333 </a>
        <a href="#" class="links"> <i class="fas fa-envelope"></i> raoashu9305@gmail.com </a>
        <a href="#" class="links"> <i class="fas fa-map-marker-alt"></i> jhajjar, india - 124104 </a>
        
        

      </div>
      <div class="box">

        <h3>quick links</h3>
        <a href="index.html" class="links"> <i class="fas fa-arrow-right"></i> home </a>
        <a href="features.html" class="links"> <i class="fas fa-arrow-right"></i> features </a>
        <a href="products.html" class="links"> <i class="fas fa-arrow-right"></i> products </a>
        <a href="categories.html" class="links"> <i class="fas fa-arrow-right"></i> categories </a>
       
        

      </div>
      <div class="box">

        <h3>Newsletter</h3>
        <p>Subscribe for latest updates</p>
        <input type="email" placeholder="your email" class="email">
        <input type="submit" value="subscribe" class="btn">

      </div>



    </div>

    <div class="credit"> created by <span>MR. R.Balaji</span> || All rights reserved</div>

  </section>

  <!-- footer section end -->


  <script src="https://cdn.jsdelivr.net/npm/swiper@8/swiper-bundle.min.js"></script>
  <script src="main.js"></script>
  <script src="https://kit.fontawesome.com/406443c753.js" crossorigin="anonymous"></script>
</body>

</html>
