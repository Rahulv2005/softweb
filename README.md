# Ex.07 Software Product Company Website
## Date:

## AIM:
To develop a static company website to display the softwares and services provided by the company.

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

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
HOME.HTML

home.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Softweb Home</title>
    <style>
        *{
            margin:0;
            padding:0;
        }
        #nav{
            background-color:wheat;
            color:#000000;
            padding: 15px;
    
        }
        li,h1,ul{
            display:inline;
        }
        ul{
            margin-left:25%;
        }
        a{
            color:blue;
            text-decoration: none;
        }
        a:hover{
            color:rgb(255, 255, 252);
            cursor:pointer;
 }
        input{
            width: 60%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
        }
      
        .box {
    display: block;
    border-style: solid;
    border-radius: 20px;
    border-color: black;
    width: 400px;
    min-height: 300px;
    font-size: 20px;
    background-color: lightgoldenrodyellow;
    margin: 0 auto; 
    text-align: center;
}

        .heading1{
            color:#000000;
            text-align: center;
            padding-top: 20px;
        }
        .heading2{
            color:rgb(238, 130, 130);
            text-align: justify;
            font-size: 20px;
            margin: 50px auto 20px;
            width:80%
        }
        .edge{
            padding-left: 400px;
        }
        .box{
            text-align: center;
        }
 p{
            color:#000000;
            text-align: center;
        }
    
        .bottomdiv{
 background-color:aqua;
            color:black;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 105px;

        }
        table{
            margin-left: 40px;
        }
    </style>
</head>
<body background="backk.png">
    <div class="header">
        <nav id="nav">
            <h1>
                SELVA DEVELOPMENT
            </h1>
                <ul>
                    <li class="li1"> 
                        <a href="home.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="product.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="people.html" target="_blank">People  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contact.html" target="_blank">Contact</a>
                    </li>
                </ul>
        </nav>
    </div>
    <div class="searchbar">
    <input placeholder="search">
    </div>
        <div><pre class="heading2"><i><b>
" Do You have a problem you can find your solution here."<b></i></pre></div>
        <div class="center">
            <div class="box">
            <h1 class="heading1">LOGIN HERE</h1>
            <br>
            <br>
            <form>
                <table cellpadding="10px" cellspacing="15px">
                    <tr>
                        <td>
                           <p> Username:</p>
                        </td>
                        <td>
                            <input type="email" name="name" placeholder="Enter a Email">
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <p> Password:</p>
                        </td>
                        <td>
                            <input type="password" name="pwd" placeholder="Enter a Password">
                        </td>
                    </tr>
                    <tr>
                        <td colspan="2">
                            <input type="submit" value="LOGIN" style="background-color: lightseagreen; color:white;">
                        </td>
                    </tr>
                </table>
                
            </form>
            </div>
        </div>
    <div class="bottomdiv">
        <p> Copyrights @2024 and Developed by RAHUL V(212223240132))
</body>
<html>

PRODUCT.HTML

product.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Softweb Products</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:rgb(179, 229, 245);
            color:pink;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:45%
        }
        li{
            color:wheat;
        }
        li:hover{
            color:white;
            cursor:pointer;
        }
 input{
            width: 18%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
        }
        .box{
            border-color:wheat;
            border-width:2px;
            border-style:solid;
            display: inline-block;
            width: 414px;
        }
        .product{

            text-align: center;
        }
        .box{
            background-color:rgb(255, 224, 254);
            cursor:pointer;
        }
        a{
            color:#062d41;
            text-decoration: none;
        }
        a:hover{
            color:white;
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color:black;
        }
      p{
            color:brown;
            text-align: center;
        }
   b{
            width: 300px;
            height: 200px;
        }
    h1{
            color:black;
            text-align: center;
        }
        .bottomdiv{
 background-color:aqua;
            color:black;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 230px;

        }
    </style>
</head>
<body background="backk.png">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">rahul TECH</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="product.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="people.html" target="_blank">People  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contact.html" target="_blank">Contact</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">PRODUCTS</h1>
        <br>
        <div class="product">
            <div class="box">
               <b><img src="python.jpeg" ></b>
                <h1>PYTHON</h1>
                <p>
                   
            Learn python from scratch and we also teach you additional frameworks</p>
            </div>
            <div class="box">
                <img src="cprogram.jpeg">
                <h1>Introduction to C</h1>
                <p>Learn C Language and it's Functions </p>
            </div>
            <div class="box">
                <img src="html.png">
                <h1>HTML</h1>
                <p>Learn HTML and and how to design web pages in an effective way</p>
            </div>
            <div class="box">
                <img src="java.jpeg">
                <h1>JAVA</h1>
                <p>Learn Java and Concepts such as abstraction,encapsulation,inheritance and polymorphism</p>
        </div>
    </div>
    <div class="bottomdiv">
        <b>Copyrights @2024 and Developed by RAHUL V(212223240132)</b>
    </div>
</body>
</html>

PEOPLE.HTML

people.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Softweb Members</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:rgb(179, 229, 245);
            color:#000000;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:45%
        }
        li{
            color:lightblue;
        }
        li:hover{
            color:#fafafa;
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
        }
        a{
            color:teal;
text-decoration: none;
        }
        a:hover{
            color:#ffffff;
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color:#63b8c0;
        }
        .bottomdiv{
            background-color:aqua;
            color:black;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 0.7px;

        }
        img{
            border-radius: 50%;
            width: 200px;
            display: inline;
            padding:15px;
            
        }
        .person{
            margin: 150px;
            text-align: center;
        }
        b,p{
            color:black;
            text-align: center;
        }
      
</style>
</head>
<body>
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">SELVA TECH</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="product.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="people.html" target="_blank">People  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contact.html" target="_blank">Contact</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">Members</h1>
        <table class="person">
            <tr>
                <td>
                    <img src="c:\Users\admin\Downloads\dd.jpg" width="100" height="160">
                </td>
		

                <td>
                    <img src="c:\Users\admin\OneDrive\Desktop\pp.jpg" width="100" height="160">
                </td>
		
                <td>
                   <img src="c:\Users\admin\OneDrive\Desktop\rr.webp" width="100" height="160">
                </td>
            </tr>
            <tr>
                
                <td>
                    <b>RAHUL V</b>
                    <p>Co-Founder</p>
                </td>
                <td>
                    <b>KL RAHUL</b>
                    <p>Asst.Director</p>
                </td>
                <td>
                    <b>MS DHONI</b>
                    <p>Marketing Director</p>
                </td>
              
            </tr>
        </table>
    </div>
    <div class="bottomdiv">
<p>Copyrights @2024 and Developed BY RAHUL V(212223240132)</p>
    </div>
</body>
</html>

CONTACT.HTML

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Softweb contact</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:rgb(153, 198, 125);
            color:#000000;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:45%
        }
        li{
            color:#074565;
  }
        li:hover{
            color:white;
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
        }
        .box{
            border-color:rgb(254, 253, 253);
            border-width:2px;
            border-style:solid;
            display: inline-block;
            width: 414px;
        }
        .product{

            text-align: center;
        }
        .box{
            background-color:rgb(66, 16, 66);
            cursor:pointer;
        }
        a{
            color:b#007cb9;
            text-decoration: none;
        }
        a:hover{
color:rgb(255, 255, 255);
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color:#c00000;
        }
        .table1{
            color:darkgreen;
            font-size: large;
        }
        .contact{
            margin-left:400px;
        }
        .heading3{
            padding-top: 30px;
            padding-bottom: 10px;
            text-align: center;
            color:#5eb3e1;
        }
        .table2{
            color:#000000;
            font-size: large;
            background-color:rgb(187, 208, 219);
            border-radius: 5px;
            border-style:dotted;
            border-color: rgb(125, 199, 213);

        }
        .queries{
            margin-left:400px;
        }
        .bottomdiv{
            background-color:aqua;
            color:#000000;
            text-align: center;
            position:relative;
display:block;
            margin-top: 24px;

        }
    </style>
</head>
<body background="backk.png">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">SELVA TECH</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="product.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="people.html" target="_blank">People  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contact.html" target="_blank">Contact</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">CONTACT US</h1>
        <div class="contact">
            <table cellpadding="15px" cellspacing="15px" class="table1">
                <tr>
                    <td>
                        ADDRESS :
                    </td>
                    
                    <td>
                        THIRUVANNAMALI
</td>
                </tr>
                <tr>
                    <td>
                        LANDMARK :
                    </td>
                    <td>
                        Near IIVM college
                    </td>
                </tr>
                <tr>
                    <td>
                        EMAIL :
                    </td>
                    <td>
                        rahul@gmail.com
                    </td>
                </tr>
                <tr>
                    <td>
                        PHONE :
                    </td>
                    <td>
                        8356469253
                    </td>
                </tr>
            </table>
        </div>
        <div>
            <h2 class="heading3">QUERIES</h2>
            <div class="queries">
                <table cellpadding="15px" cellspacing="15px" class="table2">
                    <tr>
                        <td>
 NAME :
                        </td>
                        <td>
                            <input type="name" placeholder="Enter your name"> 
                        </td>
                    </tr>
                    <tr>
                        <td>
                            EMAIL :
                        </td>
                        <td>
                            <input type="email" placeholder="Enter your E-mail">
                        </td>
                    </tr>
                    <tr>
                        <td>
                            Your Query :
                        </td>
                        <td>
                            <input type="text" placeholder="Enter your Queries">
                        </td>
                    </tr>
                    <tr>
                        <td colspan="2">
                            <input type="submit" style="background-color: darkcyan; color:#000000;">
                        </td>
                    </tr>
            </table>
        </div>
        <div class="bottomdiv">
            <p>Copyrights @2024 and Developed by RAHUL V(212223240132)</p>
        </div>
    </div>
</body>
</html>
```

## OUTPUT:

![Screenshot 2024-05-10 142243](https://github.com/Rahulv2005/softweb/assets/152600335/52405d7c-88f3-4d96-a495-ed773b01ca8d)

![Screenshot 2024-05-10 142300](https://github.com/Rahulv2005/softweb/assets/152600335/b6881fd2-8dee-48b3-8c4a-56577bd7345b)

![Screenshot 2024-05-10 142336](https://github.com/Rahulv2005/softweb/assets/152600335/e63b6550-d6c7-45c7-b35c-670d9333d6b9)

![Screenshot 2024-05-10 142352](https://github.com/Rahulv2005/softweb/assets/152600335/77c792d7-b6e6-4e3d-9dca-83048b27ef75)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
