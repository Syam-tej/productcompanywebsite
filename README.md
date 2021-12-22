# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
### home page
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>PraSan Sof Info Pvt Lmtd</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">PraSan Sof Info Pvt Lmtd</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contacts.html">Contact us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/logo.png" alt="Building" />
          <div class="contenttext">
            At Tally, we believe in the power of technology to make business
            owners efficient, empowered and happier, so they can focus on what
            matters most for their business. We design our products to focus on
            just that to make our products work for you, and not the other way
            around.
            <br />
            Our new product TallyPrime takes this to a new level, making your
            start to automation, or your switch to Tally simpler than ever
            before. You can now discover the product much more easily and make
            the product do more for you, without learning anything new. There is
            greater flexibility as the product adapts to your business and your
            way of working. And the transformed look and feel will only make you
            love the product even more.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 EduSoft Private Limited, Developed by Syam Kumar.
      </div>
    </div>
  </body>
</html>
~~~
### Products Page
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">PraSan Sof Info Pvt Lmtd</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contacts.html">Contact us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://m.media-amazon.com/images/I/61odhriZovL._SL1306_.jpg" alt="product image">
                  </div>
                  <div class="itemname">Fresh Desk Customer Software</div>
                  <div class="itemprice">Price: Rs.500 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://m.media-amazon.com/images/I/61tUB2uBVtS._SL1132_.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Vyaapar Billing Software</div>
                  <div class="itemprice">Price: Rs.200 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="https://m.media-amazon.com/images/I/41HIgGTcI5L.jpg"  alt="product image">
                </div>
                <div class="itemname">Linux installation drive</div>
                <div class="itemprice">Price: Rs.400</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="https://m.media-amazon.com/images/I/71yVflZyOYL._SL1500_.jpg"  alt="product image">
              </div>
              <div class="itemname">Windows 10</div>
              <div class="itemprice">Price: Rs.10,000.00 </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="https://m.media-amazon.com/images/I/61tAfyBWIrS._SL1500_.jpg"  alt="product image">
            </div>
            <div class="itemname">Microsoft office 365</div>
            <div class="itemprice">Price: Rs.5,510</div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="https://m.media-amazon.com/images/I/71HpEfZSgkL._SL1500_.jpg"  alt="product image">
          </div>
          <div class="itemname">Office 365 personal</div>
          <div class="itemprice">Price: Rs.3,365 </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="https://m.media-amazon.com/images/I/61jaIhpn07L._SL1500_.jpg"  alt="product image">
        </div>
        <div class="itemname">Windows 10 proffessional</div>
        <div class="itemprice">Price: Rs.11,550</div>
    </div>
    <div class="productitem"> 
      <div class="itemimage">
      <img src="https://m.media-amazon.com/images/I/41-XPb2+0qL.jpg"  alt="product image">
      </div>
      <div class="itemname">Ubuntu Installation Drive</div>
      <div class="itemprice">Price: Rs.400</div>
  </div>
  <div class="productitem"> 
    <div class="itemimage">
    <img src="https://images-eu.ssl-images-amazon.com/images/I/41UHOGZVjcL._SY264_BO1,204,203,200_QL40_FMwebp_.jpg"  alt="product image">
    </div>
    <div class="itemname">Accounting software</div>
    <div class="itemprice">Price: Rs.4,356</div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="https://m.media-amazon.com/images/I/71uDYRKaXKS._SL1500_.jpg"  alt="product image">
  </div>
  <div class="itemname">Kali linux</div>
  <div class="itemprice">Price: Rs.500</div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="https://m.media-amazon.com/images/I/31Zm+quTpiL.jpg"  alt="product image">
  </div>
  <div class="itemname">Bulk Messager</div>
  <div class="itemprice">Price: Rs.3,500</div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="https://m.media-amazon.com/images/I/61ZL4eixRpL._SL1072_.jpg"  alt="product image">
  </div>
  <div class="itemname">MacFee AntiVirus</div>
  <div class="itemprice">Price: Rs.1500</div>
</div>
</div>
</div>        
</div>
<div class="footer">
        Copyright &#169; 2021 EduSoft Private Limited, Developed by Syam Tej.
      </div>
    </div>
  </body>
</html>


~~~
### Peoples page
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">PraSan Sof Info Pvt Lmtd</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contacts.html">Contact us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Crew</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://static.toiimg.com/thumb/msid-73204368,width-400,resizemode-4/73204368.jpg" alt="product image">
                  </div>
                  <div class="itemname">Sundar Pichai</div>
                  <div class="itemprice">CEO</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage"> 
                  <img src="https://thumbor.forbes.com/thumbor/960x0/https%3A%2F%2Fspecials-images.forbesimg.com%2Fimageserve%2F60cbfa276389f09f98133343%2FFacebook-CEO-Mark-Zuckerberg-Testifies-At-Joint-Senate-Commerce-Judiciary-Hearing%2F960x0.jpg%3Ffit%3Dscale"  alt="product image">
                  </div>
                  <div class="itemname">Mr. Mark</div>
                  <div class="itemprice">Branch Manager </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="https://www.theladders.com/wp-content/uploads/jeff-bezos-ceo-profile.jpg"  alt="product image">
                </div>
                <div class="itemname">Mr. Jeff</div>
                <div class="itemprice">Capital Manager</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="https://4a7efb2d53317100f611-1d7064c4f7b6de25658a4199efb34975.ssl.cf1.rackcdn.com/marissa-mayer-bids-adieu-to-yahoo-showcase_image-8-p-2497.jpg"  alt="product image">
              </div>
              <div class="itemname">Marissa</div>
              <div class="itemprice">Technical Lead</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="https://static.dezeen.com/uploads/2021/06/elon-musk-architect_dezeen_1704_col_1.jpg"  alt="product image">
            </div>
            <div class="itemname">Mr. Elon Musk</div>
            <div class="itemprice">Team Lead</div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="https://www.deccanherald.com/sites/dh/files/styles/article_detail/public/articleimages/2021/11/30/parags-1055950-1638246491-1056177-1638272241.jpg?itok=Z2RopzRG"  alt="product image">
          </div>
          <div class="itemname">Mr. Parag</div>
          <div class="itemprice">Senior Engineer </div>
      </div>

</div>
</div>
</div>        
</div>
<div class="footer">
        Copyright &#169; 2021 EduSoft Private Limited, Developed by Syam Tej.
      </div>
    </div>
  </body>
</html>


~~~
### Contact Us
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>PraSan Sof Info Pvt Lmtd</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">PraSan Sof Info Pvt Lmtd</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contacts.html">Contact us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
       
          <div class="contenttext">
           Mail us at  PraSanSofInfo@gmail.com
           <br>
           Contact us at 2233445566
           <br>
           Our main office is at 4-199 opposite to clock tower,chaurastha building 5th floor.
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 EduSoft Private Limited, Developed by Syam Kumar.
      </div>
    </div>
  </body>
</html>


~~~
## OUTPUT:

### Home Page:

![output](./images/homepage.jpg)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
