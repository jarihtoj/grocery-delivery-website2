# grocery-delivery-website jocart
<!--Create A Responsive Grocery Store Website Design Using HTML - CSS - JavaScript -->
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Grocery Website Design</title>

    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/npm/swiper@8/swiper-bundle.min.css"
    />

    <!--Font awesome cdn link-->
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css"
    />

    <!--custom css file link-->
    <link rel="stylesheet" href="css/style.css" />
  </head>
  <body>
    <!--Header section Starts-->
    <header class="header">
      <a href="#" class="logo"><i class="fas fa-shopping-basket"></i>jocart</a>
      <nav class="navbar">
        <a href="#home">home</a>
        <a href="#features">features</a>
        <a href="#products">products</a>
      </nav>

      <div class="icons">
        <div class="fas fa-bars" id="menu-btn"></div>
        <div class="fas fa-search" id="search-btn"></div>
        <div class="fas fa-shopping-cart" id="cart-btn"></div>
        <div class="fas fa-user" id="login-btn"></div>
      </div>

      <form action="" class="search-form">
        <input type="search" id="serach-box" placeholder="search here..." />
        <label for="search-box" class="fas fa-search"></label>
      </form>

      <div class="shopping-cart">
        <div class="box">
          <i class="fas fa-trash"></i>
          <img src="image/cart-img-1.png" alt="" />
          <div class="content">
            <h3>Watermelon</h3>
            <span class="price">$4.99/-</span>
            <span class="quantity">qty:1</span>
          </div>
        </div>
        <div class="box">
          <i class="fas fa-trash"></i>
          <img src="image/cart-img-2.png" alt="" />
          <div class="content">
            <h3>Onion</h3>
            <span class="price">$4.99/-</span>
            <span class="quantity">qty:1</span>
          </div>
        </div>
        <div class="box">
          <i class="fas fa-trash"></i>
          <img src="image/cart-img-3.png" alt="" />
          <div class="content">
            <h3>Chicken</h3>
            <span class="price">$4.99/-</span>
            <span class="quantity">qty:1</span>
          </div>
        </div>
        <div class="total">total:$19.69/-</div>
        <a href="#" class="btn">checkout</a>
      </div>

      <form action="" class="login-form">
        <h3>login now</h3>
        <input type="email" placeholder="your mail" class="box" />
        <input type="password" placeholder="your password" class="box" />
        <p>forget your password<a href="#">click here</a></p>
        <p>don't have an account<a href="#">create now</a></p>
        <input type="submit" value="login now" class="btn" />
      </form>
    </header>

    <!--Header section Ends-->

    <!-- home section starts-->
    <section class="home" id="home">
      <div class="content">
        <h3><span>Grocery</span> products and Fresh fruits/vegetables for your</h3>
        <p>
          all the vegetables at an affordable price and Grocery products in best quality.
          [tomato,cabbage,orange,carrot ect...]
        </p>
        <a href="#" class="btn">shop now</a>
      </div>
    </section>
    <!-- home section Ends-->

    <!-- features section starts-->
    <section class="features" id="features">
      <h1 class="heading">our <span> features</span></h1>

      <div class="box-container">
        <div class="box">
          <img src="image/feature-img-1.png" alt="" />
          <h3>fresh and organic</h3>
          <p>
            should be clean...
          </p>
          <a href="#" class="btn">read more</a>
        </div>

        <div class="box">
          <img src="image/feature-img-2.png" alt="" />
          <h3>free delivery</h3>
          <p>
            fast delivery supports.
          </p>
          <a href="#" class="btn">read more</a>
        </div>

        <div class="box">
          <img src="image/feature-img-3.png" alt="" />
          <h3>easy payments</h3>
          <p>
        
          </p>
          <a href="#" class="btn">read more</a>
        </div>
      </div>
    </section>
  </body>
</html>
