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
### sample.html
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>AMAZON</title>
    <link rel="stylesheet" href= "./css/layout.css" />
    <link rel="icon" href="/static/img/amazon.jpg" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"><b>AMAZON</b></div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/sample.html">Home</a></div>
        <div class="menuitem"><a href="/static/product.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="/static/img/amazon.jpg" alt="LOGO" />
          <div class="contenttext">
            Amazon.com is an ecommerce platform that sells many product lines, including media (books, movies, music, and software), apparel, baby products, consumer electronics, beauty products, gourmet food, groceries, health and personal care products, industrial & scientific supplies, kitchen items, jewelry, watches, lawn and garden items, musical instruments, sporting goods, tools, automotive items, toys and games, and farm supplies and consulting services.
            Amazon websites are country-specific (for example, amazon.com for the U.S. and amazon.fr for France), though some offer international shipping.
            <br />
            
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 AMAZON DEVELOPED BY J.NETHRAA.
      </div>
    </div>
  </body>
</html>
```

### people.html
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>AMAZON</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="/static/img/logo.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"><b>AMAZON</b></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/sample.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/product.html">Products</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1><b>OUR PREMIUM PRODUCTS</b></h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/ipad.jpeg" alt="product image">
                  </div>
                  <div class="itemname">IPAD PRO</div>
                  <div class="itemprice">Price: Rs:1,80,000 </div>
              </div>
          <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/watches.jpg"  alt="product image">
                  </div>
                  <div class="itemname">SMART WATCH</div>
                  <div class="itemprice">Price: Rs:7,000</div>
              </div>
          <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/glasses.webp" alt="product image">
                  </div>
                  <div class="itemname">SPECS</div>
                  <div class="itemprice">Price: Rs:2,000</div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/footwear.webp" alt="product image">
                </div>
                <div class="itemname">SHOES</div>
                <div class="itemprice">Price: Rs:4,000</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/furniture.jpg" alt="product image">
                </div>
                <div class="itemname">DINNING TABLE</div>
                <div class="itemprice">Price: Rs:1,98,000</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/machine.png" alt="product image">
                </div>
                <div class="itemname">WASHING MACHINE</div>
                <div class="itemprice">Price: Rs:3,00,000</div>
            
            </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2023 AMAZEN DEVELOPED BY J.NETHRAA.
      </div>
    </div>
  </body>
</html>
```

### people.html
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>AMAZON</title>
    <link rel="stylesheet" href="./css/contact.css" />
    <link rel="icon" href="/static/img/amazon.jpg" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"><b>AMAZON</b></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/sample.html">Home</a></div>
        <div class="menuitem"><a href="/static/product.html">Products</a></div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <body>
          <div class="content">
              <h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Our Proud Management Crew!!!</h2>
              <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/hari.jpg" height="600" width="600"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                    Hariharan Ashok (Chairman)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/shanmathi.jpg" height="600" width="600"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                    Shanmathi Shanmugam (Head Executive)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/kothai.jpg" height="600" width="600"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                    Kothai Kumar (Head Executive)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/ragul.jpg" height="600" width="600"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                    Ragul (Manager)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/mithra.png" height="600" width="600"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                    Mithra Mukunda (Manager)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/prithvi.jpg" height="600" width="600"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                    Prithvi Raj(Deputy Manager)</h2></centre>
      </div>
      <div class="footer">
        Copyright &#169; 2023 AMAZON DEVELOPED BY J.NETHRAA.
      </div>
    </div>
  </body>
</html>
```

### contact.html
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>AMAZON </title>
    <link rel="stylesheet" href="./css/contact.css" />
    <link rel="icon" href="/static/img/amazon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"><b>AMAZON</b></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/sample.html">Home</a></div>
        <div class="menuitem"><a href="/static/product.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <body>
          <div class="content">
            <h1>&emsp;Contact Us</h1>
                    <p><b>&emsp;Here are the details listed below. Do contact us for any need</b></p>
                    <b><h2>&emsp;Contact Information:</h2></b>
                    <p><b>&emsp;&ensp;Address:</b>
                         No:21 Karukku main road,Chennai,Tamilnadu,India.
                    </p>
                    <ul>
                        <li><b>&emsp;Phone</b>:&emsp;993412437</li>
                        <li><b>&emsp;Shop owner no</b>:&emsp;9586087704</li>
                        <li><b>&emsp;Shop Manager Number:</b>99455373752</li>
                        <li><b>&emsp;Email Id:</b>&emsp;amazen1@gmail.com</li>
                        <li><b>&emsp;Email Id:</b>&emsp;amazen2@gmail.com</li>
                    </ul>
          </div>
          </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 AMAZON DEVELOPED BY J.NETHRAA.
      </div>
    </div>
  </body>
</html>
```
### layout.css
```css
*{
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
  }
  
  body {
    background-color:orange;
    color: brown;
    background-image: url("/static/img/background2.jpg");
    background-repeat: no-repeat;
    background-size: cover;
  }
  .container {
    width: 1080px;
    margin-left: auto;
    margin-right: auto;
    border-width: 1px 1px 1px 1px;
    border-style: solid;
    box-shadow: 15px 15px 8px orangered;
  }
  
  .banner {
    display: block;
    width: 100%;
    height: 250px;
    text-align: center;
    font-size: 60px;
    font-family: inherit;
    background-image: url("/static/img/Hero-banner.jpg");
    background-color: rgba(235, 231, 6, 0.856);
    background-size: 100% 100%;
    margin: 0px 0px 0px 0px;
    padding-top: 150px;
    color: rgb(104, 104, 81);
  }
  
  .menu {
    display: block;
    width: 100%;
    height: 50px;
    font-size: larger;
    background-color:  #c75408;
    text-align: center;
    padding-top: 15px;
    margin: 0px 0px 0px 0px;
    border-width: 1px;
  }
  
  .menuitem {
    display: inline-block;
    margin-left: 10px;
    margin-right: 10px;
  }
  .menuitemselected {
    display: inline-block;
    margin-left: 10px;
    margin-right: 10px;
    color: #c75408 ;
  }
  
  .menuitem a {
    text-decoration: none;
    color: rgb(165, 187, 121);
  }
  
  .content {
    display: block;
    width: 100%;
    background-color: beige;
    min-height: 500px;
    margin: 0px 0px 0px 0px;
    border-width: 1px;
    border-color: rgb(160, 108, 108);
    border-style: solid;
  }
  .homecontent {
    min-height: 500px;
    margin: 10px 10px 10px 10px;
  }
  .homecontent h1 {
    text-align: left;
  }
  .homecontent img {
    float: right;
    width: 400px;
    height: 300px;
    margin-left: 10px;
  }
  
  .contenttext {
    text-align: justify;
  }
  
  .productcontent {
    min-height: 500px;
    margin: 20px 20px 20px 20px;
  }
  
  .productcontent h1 {
    text-align: left;
  }
  
  .productitems {
    display: block;
  }
  
  .productitem {
    display: inline-block;
    width: 40%;
    height: 250px;
    text-align: center;
  }
  
  .productitem img {
    width: 200px;
    height: 200px;
    display: block;
  }
  .productitem .itemimage {
    display: block;
    margin-left: auto;
    margin-right: auto;
    width: 100px;
    margin-bottom: 5px;
  }
  
  .productitem .itemname {
    display: block;
  }
  .productitem .itemprice {
    display: block;
  }
  
  .footer {
    display: block;
    width: 100%;
    height: 40px;
    background-color: #c75408;
    text-align: center;
    padding-top: 10px;
    margin: 0px 0px 0px 0px;
    color: #1b044ce5;
  }
```
### contact.css
```css
* {
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
  }
  body {
    background-color: orange;
    color: brown;
    background-image: url("/static/img/background2.jpg");
    background-repeat: no-repeat;
    background-size: cover;
  }
  .container {
    width: 1080px;
    margin-left: auto;
    margin-right: auto;
    border-width: 1px 1px 1px 1px;
    border-style: solid;
    box-shadow: 15px 15px 8px orangered;
  }
  
  .banner {
    display: block;
    width: 100%;
    height: 250px;
    text-align: center;
    font-size: 60px;
    font-family: inherit;
    background-image: url("/static/img/Hero-banner.jpg");
    background-size: 100% 100%;
    margin: 0px 0px 0px 0px;
    padding-top: 150px;
    color: rgb(104, 104, 81);
  }
  
  .menu {
    display: block;
    width: 100%;
    height: 50px;
    font-size: larger;
    background-color: #c75408;
    text-align: center;
    padding-top: 15px;
    margin: 0px 0px 0px 0px;
    border-width: 1px;
  }
  
  .menuitem {
    display: inline-block;
    margin-left: 10px;
    margin-right: 10px;
  }
  .menuitemselected {
    display: inline-block;
    margin-left: 10px;
    margin-right: 10px;
    color: #c75408;
  }
  
  .menuitem a {
    text-decoration: none;
    color: rgb(165, 187, 121);
  }
  
  .content {
    display: block;
    width: 100%;
    background-color: beige;
    font-size: 20px;
    min-height: 500px;
    margin: 0px 0px 0px 0px;
    border-width: 1px;
    border-color:rgb(160, 108, 108);
    border-style: solid;
  }
  .homecontent {
    min-height: 500px;
    margin: 10px 10px 10px 10px;
  }
  .homecontent h1 {
    text-align: left;
  }
  .homecontent img {
    float: right;
    width: 400px;
    height: 300px;
    margin-left: 10px;
  }
  
  .contenttext {
    text-align: justify;
  }
  
  .productcontent {
    min-height: 500px;
    margin: 10px 10px 10px 10px;
  }
  
  .productcontent h1 {
    text-align: left;
  }
  
  .productitems {
    display: block;
  }
  
  .productitem {
    display: inline-block;
    width: 30%;
    height: 250px;
    text-align: center;
  }
  
  .productitem img {
    width: 100px;
    height: 100px;
    display: block;
  }
  .productitem .itemimage {
    display: block;
    margin-left: auto;
    margin-right: auto;
    width: 100px;
    margin-bottom: 5px;
  }
  
  .productitem .itemname {
    display: block;
  }
  .productitem .itemprice {
    display: block;
  }
  
  .footer {
    display: block;
    width: 100%;
    height: 40px;
    background-color:#c75408;
    text-align: center;
    padding-top: 10px;
    margin: 0px 0px 0px 0px;
    color: darkblue;
  }
  ```


## OUTPUT:

## HOME :
![image](https://github.com/Nethraa24/productcompanywebsite/assets/121215786/022ff988-05f6-4338-89f6-bbe0e9d28403)

## PRODUCT :
![image](https://github.com/Nethraa24/productcompanywebsite/assets/121215786/6e27a386-a5d6-4364-8d64-7d98ae413021)

## PEOPLE :
![image](https://github.com/Nethraa24/productcompanywebsite/assets/121215786/6a4cabdc-1e1f-48bf-9c88-c49e71bc3a8c)

![image](https://github.com/Nethraa24/productcompanywebsite/assets/121215786/7f3bf2ab-f1b0-471d-a38d-ae771d59d210)

![image](https://github.com/Nethraa24/productcompanywebsite/assets/121215786/a8a50bed-0b3c-422a-bb9b-65a52065ed69)

![image](https://github.com/Nethraa24/productcompanywebsite/assets/121215786/e5c01cb3-8edc-4148-ad76-b5dcb110982d)

![image](https://github.com/Nethraa24/productcompanywebsite/assets/121215786/4d3b6a53-fe47-4fec-b085-d7523f5d6e8a)

![image](https://github.com/Nethraa24/productcompanywebsite/assets/121215786/8f9e8286-50d7-4fcf-a7f6-8d228032eefa)

## CONTACT :
![image](https://github.com/Nethraa24/productcompanywebsite/assets/121215786/3ab0932f-b4c5-4951-9b73-88e7d03addf8)


## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
