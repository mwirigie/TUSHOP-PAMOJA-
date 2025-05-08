<!doctype html>
<html lang="en"> 
 <head> 
  <meta charset="UTF-8"> 
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
  <title>Tushop Pamoja</title> 
  <link rel="stylesheet" href="style.css"> 
 </head> 
 <body> 
  <header> 
   <h1>Tushop Pamoja</h1> 
   <nav> 
    <ul> 
     <li><a href="#">Shop</a></li> 
     <li><a href="#">About</a></li> 
     <li><a href="#" id="cart-btn">Cart (<span id="cart-count">0</span>)</a></li> 
    </ul> 
   </nav> 
  </header> 
  <main class="products"> 
   <div class="product"> 
    <h2>Wireless Earbuds</h2> 
    <p>KSh 2,500</p> <button onclick="addToCart('Wireless Earbuds', 2500)">Add to Cart</button> 
   </div> 
   <div class="product"> 
    <h2>Bluetooth Speaker</h2> 
    <p>KSh 3,200</p> <button onclick="addToCart('Bluetooth Speaker', 3200)">Add to Cart</button> 
   </div> 
   <div class="product"> 
    <h2>Power Bank</h2> 
    <p>KSh 1,800</p> <button onclick="addToCart('Power Bank', 1800)">Add to Cart</button> 
   </div> 
  </main> 
  <section class="about"> 
   <h2>About Tushop Pamoja</h2> 
   <p> Tushop Pamoja is a trusted Kenyan online shop offering quality electronics, fashion, and accessories at affordable prices. Our mission is to make online shopping easy, secure, and accessible to everyone. We pride ourselves on fast delivery and excellent customer service. </p> 
  </section> 
  <footer> 
   <p>© 2025 Tushop Pamoja. All rights reserved.</p> 
   <p>Email: info@tushoppamoja.co.ke</p> 
  </footer> 
  <section class="cart hidden" id="cart-section"> 
   <h2>Your Cart</h2> 
   <ul id="cart-items"></ul> 
   <p>Total: KSh <span id="cart-total">0</span></p> <button onclick="checkout()">Checkout</button> 
  </section> 
  <div class="popup hidden" id="popup"> 
   <p>Payment Successful! Thank you for shopping with Tushop Pamoja.</p> <button onclick="closePopup()">Close</button> 
  </div> 
  <script src="script.js"></script> 
 </body>
</html>
