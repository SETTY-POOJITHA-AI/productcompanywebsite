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

### Home Page:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">MS OFFICE SOFTWARE.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/bg2.jpg" alt="Building" />
          <div class="contenttext">
            Microsoft runs six major business units representing our entire product cycle to serve customers, 
           from consumers to corporations, from gamers to governments.
            Individual but connected, our businesses are responsible 
            for their growth while also contributing to each other’s success.
            <br />
            Microsoft Research India conducts research across a wide spectrum of topics spanning foundations
             of computer science, systems, security, machine learning and artificial intelligence, human computer interaction,
              and the role of technology in solving societal problems.

Our researchers are curious and bold, with a track record of pushing the frontiers of knowledge in theory as well as real-world systems.
 We collaborate freely with academia and play an active role in mentoring and training young researchers.

More
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 EduSoft Private Limited, Developed by POOJITHA SETTY.
      </div>
    </div>
  </body>
</html>

### PRODUCT PAGE:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">MS OFFICE SOFTWARE</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/w1.png" alt="product image">
                  </div>
                  <div class="itemname">MS Office 2021 Professional Plus License key</div>
                  <div class="itemprice">Price: Rs.750 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/w2.png"  alt="product image">
                  </div>
                  <div class="itemname">Windows or Mac + 5TB Cloud</div>
                  <div class="itemprice">Price: Rs.549</div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="./img/w3.jpg"  alt="product image">
                </div>
                <div class="itemname">Microsoft Office Home & Student 2019 for Windows – 1 PC</div>
                </div>
                <div class="itemprice">Price: Rs.1999 </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="./img/w4.jpg"  alt="product image">
              </div>
              <div class="itemname">WINDOWS SERVER 2019 STANDARD</div>
              <div class="itemprice">Price: Rs.445 </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="./img/w5.jpg"  alt="product image">
            </div>
            <div class="itemname">Microsoft office 365 pro</div>
            <div class="itemprice">Price: Rs.670 </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="./img/w6.jpg"  alt="product image">
          </div>
          <div class="itemname">PROJECT PRO 2019 DOWNLOAD</div>
          <div class="itemprice">Price: Rs.750</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="./img/w7.jpg"  alt="product image">
        </div>
        <div class="itemname">Excel Home </div>
        <div class="itemprice">Price: Rs.5999 </div>
    </div>
    <div class="productitem"> 
      <div class="itemimage">
      <img src="./img/w8.jpg"  alt="product image">
      </div>
      <div class="itemname">Microsoft® Office Professional 2021</div>
      <div class="itemprice">Price: Rs.38,000 </div>
  </div>
  <div class="productitem"> 
    <div class="itemimage">
    <img src="./img/w9.jpg"  alt="product image">
    </div>
    <div class="itemname">Microsoft Office 2019</div>
    <div class="itemprice">Price: Rs.950 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="./img/w10.jpg"  alt="product image">
  </div>
  <div class="itemname">Microsoft Office 2019 Professional Plus 5 PC</div>
  <div class="itemprice">Price: Rs.1999 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="./img/w11.jpg"  alt="product image">
  </div>
  <div class="itemname">Microsoft Office 2016 Professional Plus 32/64-bit License Key</div>
  <div class="itemprice">Price: Rs.850 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="./img/w12.jpg"  alt="product image">
  </div>
  <div class="itemname">VISIO PROFESSIONAL 2019</div>
  <div class="itemprice">Price: Rs.1555 </div>
</div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 EduSoft Private Limited, Developed by POOJITHASETTY.
      </div>
    </div>
  </body>
</html>

### PEOPLE PAGE:

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>WeCraft</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">MS OFFICE SOFTWARE</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Meet Our Team</h1>
          <table>
            <tr> 
            <td>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/w01.jpg" alt="product image">
                  </div>
                  <div class="itemname">Lisa Su </div> <br>
                  <div class="itemprice"> CEO  </div> 
                </td>
            <td>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="./img/w02.jpg" alt="product image">
                    </div>
                    <div class="itemname"> Karen Lynch </div> <br>
                    <div class="itemprice">Managing Director</div>
                </td>
                <td>
                    <div class="productitem"> 
                        <div class="itemimage">
                        <img src="./img/m3.jpg" alt="product image">
                        </div>
                        <div class="itemname">Dilip</div> <br>
                        <div class="itemprice">Project Director</div>

                </td>  
            </tr>
            <tr>
                <td>
                    <div class="productitem"> 
                        <div class="itemimage">
                        <img src="./img/m2.jpg" alt="product image">
                        </div>
                        <div class="itemname">Barry Leo</div> <br>
                        <div class="itemprice">Senior Manager</div>
                    </td>
                    <td>
                        <div class="productitem"> 
                            <div class="itemimage">
                            <img src="./img/w03.jpg" alt="product image">
                            </div>
                            <div class="itemname">Safra Catz</div><br>
                            <div class="itemprice"> Manager</div>

                    </td>
                    <td>
                        <div class="productitem"> 
                            <div class="itemimage">
                            <img src="./img/m1.jpg" alt="product image">
                            </div>
                            <div class="itemname">David Hason</div> <br>
                            <div class="itemprice">Senior Team Leader</div>
                    </td>

            </tr>    
            </table>
            </div>
            </div>
        </body>
        </html>

### CONTACT US PAGE:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>WeCraft</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">WeCraft</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="contactus" background-image="url(/static/img/cbg.jpg")>
          OFFICE ADDRESS <br>
          <hr style="height:2px;border-width:5px;color:#e6752f;background-color: #e6752f">
          
          806v, 
          Marque Estate,<br>
          Chennai,<br>
          76009,<br>
          India<br>

          CONTACT ADDRESS<br>
          <hr style="height:2px;border-width:5px;color:#e6752f;background-color: #e6752f">
          
          Tel: 044-87635421
               044-87635422
          Fax: 0091-67-6784890
          E-mail: Wcrft4528@manufav.com
          <br>
           For Service Queries or Complaints: sales.wc@Service.com
        
        </div>
        <div class="footer">
            Copyright &#169; 2021 WeCraft, Developed by Poojitha Setty.
          </div>

      </div>
      </body>
      </html>
### OUTPUT:
```
### HOME PAGE:
![output](./SS1.jpg)
### PRODUCT PAGE:
![output](./SS2.jpg)
### PEOPLE PAGE:
![output](./SS3.jpg)
### CONTACT PAGE
![output](./SS4.jpg)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
