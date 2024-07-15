# contact.html
```
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Contact Us Page</title>
    <style type="text/css">
      * {
        margin: 0;
        padding: 0;
        font-family: Arial, Helvetica, sans-serif;
      }
      .banner {
        width: 100%;
        height: 95vh;
        background-image: linear-gradient(
            rgba(0, 0, 0, 0.75),
            rgba(0, 0, 0, 0.75)
          ),
          url('/static/background.jpg');
        background-size: cover;
        background-position: center;
      }
      .navbar {
        width: 85%;
        margin: auto;
        padding: 35px 0;
        display: flex;
        align-items: center;
        justify-content: space-between;
      }
      .bg-contact {
        border: 1px;
        padding: 10px;
        color: white;
        background-color: #00d5ff;
        border-radius: 30px;
      }
      .logo {
        color: #3b0bfb;
        font-size: 40px;
        font-weight: 700;
        letter-spacing: 3px;
      }
      span {
        color: white;
      }
      .navbar form {
        width: 300px;
        height: 40px;
        display: flex;
        background: rgba(255, 255, 255, 0.2);
        padding: 1px 1px;
        font-size: 15px;
        border-radius: 10px;
        backdrop-filter: blur(4px) saturate(180%);
      }
      .navbar form input {
        background: transparent;
        flex: 1;
        border: 0;
        outline: none;
        padding: 12px 20px;
        font-size: 15px;
        color: white;
      }
      ::placeholder {
        color: white;
      }
      .navbar form button {
        border: 0;
        outline: none;
        padding: 5px 20px;
        color: white;
        border-radius: 10px;
        background: #00d5ff;
        cursor: pointer;
      }
      .navbar li {
        list-style: none;
        display: inline-block;
        margin: 0 20px;
        position: relative;
      }
      .navbar li a {
        text-decoration: none;
        color: white;
        text-transform: uppercase;
      }
      .navbar li:hover {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: #0ef;
        color: #081b29;
        box-shadow: 0 0 20px #0ef;
      }
      .box {
        display: flex;
        column-gap: 40px;
        background: transparent;
        position: relative;
        top: 50px;
      }
      .box-1 {
        height: 400px;
        width: 400px;
        border: 3px solid white;
        border-radius: 20px;
        background: transparent;
        position: relative;
        left: 250px;
      }
      .box-2 {
        height: 400px;
        width: 400px;
        border: 3px solid #7300ff;
        border-radius: 20px;
        background: transparent;
        position: relative;
        left: 300px;
      }
      .box-1 form {
        display: flex;
        color: white;
        background: transparent;
        padding: 10px;
        font-size: 15px;
        position: relative;
        top: 15px;
      }
      .box-1 form input {
        background: transparent;
        display: flex;
        border: 1px solid white;
        border-radius: 10px;
        padding: 15px 30px;
        font-size: 15px;
        color: white;
        position: relative;
        top: 30px;
      }
      .box-1 form textarea {
        background: transparent;
        color: white;
        padding: 15px 10px;
        position: relative;
        top: 30px;
        left: 20px;
        border: 1px solid white;
        border-radius: 10px;
        width: 300px;
      }
      .box-1 form button {
        border: 0;
        outline: none;
        padding: 10px 20px;
        color: white;
        border-radius: 30px;
        background: #00d5ff;
        cursor: pointer;
        position: relative;
        top: 50px;
      }
      .box-2 h2 {
        color: white;
        position: relative;
        top: 25px;
        left: 50px;
        font-size: 30px;
      }
      .box-2 p {
        color: white;
        position: relative;
        top: 50px;
        padding: 10px 80px;
      }
      .box-2 span {
        color: #00d5ff;
        font-size: 20px;
      }
      footer {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: #0ef;
        color: #081b29;
        box-shadow: 0 0 20px #0ef;
      }
    </style>
  </head>
  <body>
    <div class="banner">
      <br />
      <div class="navbar">
        <h1 class="logo">L<span>EARN</span>C<span>RAZE</span></h1>
        <ul>
          <li><a href="home.html">Home</a></li>
          <li><a href="product.html">Product</a></li>
          <li><a href="people.html">People</a></li>
          <li><a href="contacts.html" class="bg-contact"> Contacts </a></li>
        </ul>
        <form action="" method="get">
          <input type="text" placeholder="Enter to Search" />
          <button type="submit">Search</button>
        </form>
      </div>
      <div class="box">
        <div class="box-1">
          <form>
            <center>
              <h1>Contact Us</h1>
              <input type="text" placeholder="Your Name" />
              <br />
              <input type="email" placeholder="Your Email" />
              <br />
              <textarea rows="4" cols="40" placeholder="Your Message">
              </textarea>
              <br />
              <button type="submit">Submit</button>
            </center>
          </form>
        </div>
        <div class="box-2">
          <h2>Contact Information</h2>
          <p>
            <span>Address</span> : 123,Main Street, Andheri West, Mumbai, Maharashtra, India
          </p>
          <p><span>Email</span> : official_crazylearn@gmail.com</p>
          <p><span>Follow us On Facebook</span> : https://www.facebook.com/official_crazylearn</p>
        </div>
      </div>
    </div>
    <footer>
      <center>Designed and Developed by YUVARAJ B (212221040187)</center>
    </footer>
  </body>
</html>
```
# home.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LearnCraze - Education That Fits Your Lifestyle</title>
    <style type="text/css">
        * {
            margin: 0;
            padding: 0;
            font-family: Arial, Helvetica, sans-serif;
        }
        .banner {
            width: 100%;
            height: 95vh;
            background-image: linear-gradient(
                rgba(0, 0, 0, 0.75),
                rgba(0, 0, 0, 0.75)
            ),
            url('/static/background.jpg');
            background-size: cover;
            background-position: center;
            color: #fff; 
        }
        .navbar {
            width: 85%;
            margin: auto;
            padding: 35px 0;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }
        .logo {
            color: #0b0bfb;
            font-size: 40px;
            font-weight: 700;
            letter-spacing: 3px;
        }
        span {
            color: white;
        }
        form {
            width: 300px;
            height: 40px;
            display: flex;
            background: rgba(255, 255, 255, 0.2);
            padding: 1px 1px;
            font-size: 15px;
            border-radius: 10px;
            backdrop-filter: blur(4px) saturate(180%);
        }
        form input {
            background: transparent;
            flex: 1;
            border: 0;
            outline: none;
            padding: 12px 20px;
            font-size: 15px;
            color: white;
        }
        ::placeholder {
            color: white;
        }
        form button {
            border: 0;
            outline: none;
            padding: 5px 20px;
            color: white;
            border-radius: 10px;
            background: #00d5ff;
            cursor: pointer;
        }
        #search.hover {
            border: 1px;
            padding: 10px;

            transition: 0.5s;
            cursor: pointer;
            border-radius: 30px;
            background: #0ef;
            color: #081b29;
            box-shadow: 0 0 20px #0ef;
        }
        .navbar li {
            list-style: none;
            display: inline-block;
            margin: 0 20px;
            position: relative;
        }
        .navbar li a {
            text-decoration: none;
            color: white;
            text-transform: uppercase;
        }
        .navbar li:hover {
            border: 1px;
            padding: 10px;

            transition: 0.5s;
            cursor: pointer;
            border-radius: 30px;
            background: #0ef;
            color: #081b29;
            box-shadow: 0 0 20px #0ef;
        }
        .content {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            text-align: center;
        }
        .text h2 {
            color: #fb0be3;
            font-weight: 800;
            font-size: 40px; 
            letter-spacing: 3px;
        }
        .text p {
            color: white;
            text-transform: capitalize;
            font-size: 15px;
            margin-bottom: 30px;
            word-spacing: 2px;
            letter-spacing: 1px;
        }
        .login {
            margin: 0px 10px;
            border: 2px solid #00d5ff;
            padding: 13px 35px;
            letter-spacing: 1px;
            color: white;
            border-radius: 30px;
            background-color: #00d5ff;
            text-decoration: none;
        }
        .login:hover {
            border: 2px solid #00d5ff;
            color: #00d5ff;
            background-color: white;
            transition: 0.5s;
            cursor: pointer;
        }
        .signup {
            margin: 0px 10px;
            border: 2px solid #00d5ff;
            padding: 13px 35px;
            letter-spacing: 1px;
            color: white;
            border-radius: 30px;
            background-color: #00d5ff;
            text-decoration: none;
        }
        .signup:hover {
            border: 2px solid #f60b0b;
            color: #00d5ff;
            background-color: white;
            transition: 0.5s;
            cursor: pointer;
        }
        footer {
            border: 1px;
            padding: 10px;

            transition: 0.5s;
            cursor: pointer;
            border-radius: 30px;
            background: #0ef;
            color: #081b29;
            box-shadow: 0 0 20px #0ef;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
<div class="banner">
    <br />
    <div class="navbar">
        <h1 class="logo">L<span>EARN</span>C<span>RAZE</span></h1>
        <ul>
            <li><a href="home.html">Home</a></li>
          <li><a href="product.html">Product</a></li>
          <li><a href="people.html">People</a></li>
          <li><a href="contacts.html"> Contacts </a></li>
        </ul>
        <form action="" method="get">
            <input type="text" placeholder="Enter to Search" />
            <button id="search" type="submit">Search</button>
        </form>
    </div>
    <div class="content">
        <div class="text">
            <h2>
                Education That Fits Your Lifestyle: Anytime, Anywhere Learning.
            </h2>
            <br />

            <br />
            <div>
                <a href="#" class="login"> Log In </a>
                <a href="#" class="signup"> Sign Up </a>
            </div>
        </div>
    </div>
</div>
<footer>
    <center>Designed and Developed by YUVARAJ B (212221040187)</center>
</footer>
</body>
</html>
```
# people.html
```
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>people page</title>
    <style type="text/css">
      * {
        margin: 0;
        padding: 0;
        font-family: Arial, Helvetica, sans-serif;
      }
      .banner {
        width: 100%;
        height: 95vh;
        background-image: linear-gradient(
            rgba(0, 0, 0, 0.75),
            rgba(0, 0, 0, 0.75)
          ),
          url('/static/background.jpg');
        background-size: cover;
        background-position: center;
      }
      .navbar {
        width: 85%;
        margin: auto;
        padding: 35px 0;
        display: flex;
        align-items: center;
        justify-content: space-between;
      }
      .bg-people {
        border: 1px;
        padding: 10px;
        color: white;
        background-color: #00d5ff;
        border-radius: 30px;
      }
      .logo {
        color: #0b13fb;
        font-size: 40px;
        font-weight: 700;
        letter-spacing: 3px;
      }
      span {
        color: white;
      }
      form {
        width: 300px;
        height: 40px;
        display: flex;
        background: rgba(255, 255, 255, 0.2);
        padding: 1px 1px;
        font-size: 15px;
        border-radius: 10px;
        backdrop-filter: blur(4px) saturate(180%);
      }
      form input {
        background: transparent;
        flex: 1;
        border: 0;
        outline: none;
        padding: 12px 20px;
        font-size: 15px;
        color: white;
      }
      ::placeholder {
        color: white;
      }
      form button {
        border: 0;
        outline: none;
        padding: 5px 20px;
        color: white;
        border-radius: 10px;
        background: #00d5ff;
        cursor: pointer;
      }
      .navbar li {
        list-style: none;
        display: inline-block;
        margin: 0 20px;
        position: relative;
      }
      .navbar li a {
        text-decoration: none;
        color: white;
        text-transform: uppercase;
      }
      .navbar li:hover {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: #0ef;
        color: #081b29;
        box-shadow: 0 0 20px #0ef;
      }
      .image {
        position: relative;
        border: 0;
        top: 150px;

        background: transparent;
      }
      .image table {
        border: 0;
        color: white;
        position: relative;
        left: 200px;
      }
      .image table img {
        height: 140px;
        width: 140px;
        border: 2px solid white;
        padding: 5px;
        border-radius: 50%;
      }
      .image table td {
        color: #00d5ff;
      }
      footer {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: #0ef;
        color: #081b29;
        box-shadow: 0 0 20px #0ef;
      }
    </style>
  </head>
  <body>
    <div class="banner">
      <br />
      <div class="navbar">
        <h1 class="logo">L<span>EARN</span>C<span>RAZE</span></h1>
        <ul>
          <li><a href="home.html">Home</a></li>
          <li><a href="product.html">Product</a></li>
          <li><a href="people.html"  class="bg-people">People</a></li>
          <li><a href="contacts.html"> Contacts </a></li>
        </ul>
        <form action="" method="get">
          <input type="text" placeholder="Enter to Search" />
          <button type="submit">Search</button>
        </form>
      </div>
      <div class="image">
        <table cellspacing="20">
          <tr align="center">
            <td><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTjLO9GJgJ-ZtK_i-C_12IswFWpfNEw4ygycg&s" /></td>
            <td><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcToFj_7asxijTyYWjMpC2JIyjf8Drt3EwzokQ&s" /></td>
            <td><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSWc3yzXGWOzSuDibM5xkF5V5b1LephwF9Bdg&s" /></td>
            <td><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ6tz0HBNbebwB-C3bG4lG7fwoF2jOLIOrAOg&s" /></td>
            <td><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT6QxDlkbf95OX-SGFfcc21w2MH9FueTBGNMw&s" /></td>
            <td><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTNe4x30q7chs1edJb43YDmNnUNBXb7qdxYxA&s" /></td>
          </tr>
          <tr align="center">
            <th>Assistant Professor</th>
            <th>Dean</th>
            <th>Head of Department</th>
            <th>Principal</th>
            <th>Director</th>
            <th>chancellor</th>
          </tr>
          <tr align="center">
            <td>cricket player</td>
            <td>politician</td>
            <td>cricket player</td>
            <td>chess player</td>
            <td>Actor</td>
            <td>Doctor</td>
          </tr>
        </table>
      </div>
    </div>
    <footer>
      <center>Designed and Developed by YUVARAJ B (212221040187)</center>
    </footer>
  </body>
</html>
```
# product.html
```
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Product Page</title>
    <style type="text/css">
      * {
        margin: 0;
        padding: 0;
        font-family: Arial, Helvetica, sans-serif;
      }
      .banner {
        width: 100%;
        height: 95vh;
        background-image: linear-gradient(
            rgba(0, 0, 0, 0.75),
            rgba(0, 0, 0, 0.75)
          ),
          url('/static/background.jpg');
        background-size: cover;
        background-position: center;
      }
      .navbar {
        width: 85%;
        margin: auto;
        padding: 35px 0;
        display: flex;
        align-items: center;
        justify-content: space-between;
      }
      .bg-product {
        border: 1px;
        padding: 10px;
        color: white;
        background-color: #00d5ff;
        border-radius: 30px;
      }
      .logo {
        color: #3b0bfb;
        font-size: 40px;
        font-weight: 700;
        letter-spacing: 3px;
      }
      span {
        color: white;
      }
      form {
        width: 300px;
        height: 40px;
        display: flex;
        background: rgba(255, 255, 255, 0.2);
        padding: 1px 1px;
        font-size: 15px;
        border-radius: 10px;
        backdrop-filter: blur(4px) saturate(180%);
      }
      form input {
        background: transparent;
        flex: 1;
        border: 0;
        outline: none;
        padding: 12px 20px;
        font-size: 15px;
        color: white;
      }
      ::placeholder {
        color: white;
      }
      form button {
        border: 0;
        outline: none;
        padding: 5px 20px;
        color: white;
        border-radius: 10px;
        background: #00d5ff;
        cursor: pointer;
      }
      .navbar li {
        list-style: none;
        display: inline-block;
        margin: 0 20px;
        position: relative;
      }
      .navbar li a {
        text-decoration: none;
        color: white;
        text-transform: uppercase;
      }
      .navbar li:hover {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: #0ef;
        color: #081b29;
        box-shadow: 0 0 20px #0ef;
      }
      .container {
        background: transparent;
        padding: 10px 5%;
        padding-bottom: 100px;
      }
      .container .box-container {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
        gap: 100px;
      }
      .container .box-container .box {
        color: white;
        box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
        border-radius: 20px;
        background: transparent;
        border: 1px solid white;
        padding: 30px 20px;
      }
      .container .box-container .box img {
        height: 70px;
        border-radius: 20px;
      }
      .container .box-container .box h3 {
        color: #00d5ff;
        font-size: large;
        padding: 20px 0;
      }
      .container .box-container .box p {
        color: white;
        font-size: small;
        line-height: 1.5;
      }
      footer {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: #0ef;
        color: #081b29;
        box-shadow: 0 0 20px #0ef;
      }
    </style>
  </head>
  <body>
    <div class="banner">
      <br />
      <div class="navbar">
        <h1 class="logo">L<span>EARN</span>C<span>RAZE</span></h1>
        <ul>
          <li><a href="home.html">Home</a></li>
          <li><a href="product.html"  class="bg-product">Product</a></li>
          <li><a href="people.html">People</a></li>
          <li><a href="contacts.html"> Contacts </a></li>
        </ul>
        <form action="" method="get">
          <input type="text" placeholder="Enter to Search" />
          <button type="submit">Search</button>
        </form>
      </div>
      <div class="container">
        <div class="box-container">
          <div class="box">
            <h3>Programming Languages</h3>
            <p>
              Front end and back end programming languages such as Java, Python, PHP, CSS, JavaScript. </p>
          </div>
          <div class="box">
            <h3>GATE,CAT Preparation</h3>
            <p>
              Coaching to face competitive exams like GATE,CAT,NEET.</p>
          </div>
          <div class="box">
            <h3>Engineering Mathematics</h3>
            <p>
              Engineering Mathematics subjects such as discrete mathematics,graphs,combinatorics.
            </p>
          </div>
          <div class="box">
            <h3>Computational Algorithms and Data Structures</h3>
            <p>
               Basic algorithms used for computation such as dynamic programming,time and space complexity.           </p>
          </div>
          <div class="box">
            <h3>Aerospace Engineering</h3>
            <p>
              Aerospace engineering is the primary field of engineering concerned with the development of aircraft and spacecraft.            </p>
          </div>
          <div class="box">
            <h3>Biomedical Engineering</h3>
            <p>
              Biomedical engineering (BME) focuses on the advances that improve human health and health care at all levels and is the application of the principles and problem-solving techniques of engineering to biology and medicine.            </p>
          </div>
          <div class="box">
            <h3>Chemical Engineering</h3>
            <p>
              Chemical engineering is a multi-disciplinary branch of engineering that combines natural and experimental sciences  along with life sciences to design, develop, produce, transform, transport, operate and manage the industrial processes that turn raw materials into valuable products.            </p>
          </div>
          <div class="box">
            <h3>Biotechnology</h3>
            <p>
              Biotechnology is technology that utilizes biological systems, living organisms or parts of this to develop or create different products.            </p>
          </div>
          <div class="box">
            <h3>Electronics and Communication Engineering</h3>
            <p>
              Electronics and Communications Engineering (ECE) course is a branch of engineering that covers the study, design, development, and application of electrical circuits, electronics, and communication systems.            </p>
          </div>
          <div class="box">
            <h3>Electrical Engineering</h3>
            <p>
              Electrical engineering is an engineering discipline concerned with the study, design, and application of equipment, devices, and systems which use electricity, electronics, and electromagnetism.            </p>
          </div>
        </div>
      </div>
    </div>
    <footer>
      <center>Designed and Developed by SRIVARSHAN S (212221040163)</center>
    </footer>
  </body>
</html>
```
