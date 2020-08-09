
<!DOCTYPE html>
<html lang="eng">

<head>
<title> Products Page</title>
<meta charset="utf-8">
<meta name="viewport" content="widht=device-width, initial-scale=1">
<meta name="description" content="">
<meta name="robots" content="">

<style>
*{
margin: 0;
padding: 0;
}

body{
font-family: arial;
}

header{
background-color: silver;
height: 70px;
padding: 10px;
display: flex;
justify-content: space-between;
border-bottom: 1px solid white;
}

#logo{
font-family: arial;
font-size: 7vw;
font-weight: bold;
}

#links-div{
align-self: flex-end;
}

#links-div a{
font-size: 0.7em;
text-decoration: none;
}

#login:after{
content: ' |';
}

nav ul{
background-color: silver;
display: flex;
justify-content: space-between;
list-style: none;
}

nav ul li{
flex-grow: 3;
}

nav ul li a{
text-decoration: none;
display: block;
text-align: center;
border: 1px solid white;
}

nav ul li a:hover{
background-color: black;
color: white;
}

.products{
margin: 40px 10px;
display: flex;
justify-content: space-around;
flex-wrap: wrap;
align-items: center; 
}

.product{
border: 1px solid black;
text-align: center;
flex: 1 250px;
margin: 10px;
background-color: silver;
}

.product-img{
width: 100%;
height: 250px;
background-color: white;
border: 1px solid black;
text-align: center;
line-height: 250px;
font-size: 10px;
}

h3{
display: inline-block
}

.product-brief{
text-align: left;
margin-left: 10px;
font-size: 15px;
}

footer{
background-color: silver;
height: 40px;
}

footer div{
margin: 10px;
padding: 10px
}

</style>
</head>

<body>
<header>
    <div id="logo">logo</div>
    <div id="links-div">
        <a href="" id="login">login</a>
        <a href="">sign-up</a>
    </div>
</header>

<nav>
    <ul>
        <li><a href="">Home</a></li>
        <li><a href="">About us</a></li>
        <li><a href="">Products</a></li>
        <li><a href="">Contact us</a></li>
    </ul>
</nav>


<section class="products">
    <article class="product">
        <div class="product-img">
            product-img
        </div>
        <div class="product-brief">
             <p><h3>Name: </h3> Product-name</p>
             <p><h3>Price: </h3> $ 467</p>
        </div>
    </article>
    
    <article class="product">
        <div class="product-img">
            product-img
        </div>
        <div class="product-brief">
             <p><h3>Name: </h3> Product-name</p>
             <p><h3>Price: </h3> $ 467</p>
        </div>
    </article>
    
    <article class="product">
        <div class="product-img">
            product-img
        </div>
        <div class="product-brief">
             <p><h3>Name: </h3> Product-name</p>
             <p><h3>Price: </h3> $ 467</p>
        </div>
    </article>
    
    <article class="product">
        <div class="product-img">
            product-img
        </div>
        <div class="product-brief">
             <p><h3>Name: </h3> Product-name</p>
             <p><h3>Price: </h3> $ 467</p>
        </div>
    </article>
    
    <article class="product">
        <div class="product-img">
            product-img
        </div>
        <div class="product-brief">
             <p><h3>Name: </h3> Product-name</p>
             <p><h3>Price: </h3> $ 467</p>
        </div>
    </article>
    
    <article class="product">
        <div class="product-img">
            product-img
        </div>
        <div class="product-brief">
             <p><h3>Name: </h3> Product-name</p>
             <p><h3>Price: </h3> $ 467</p>
        </div>
    </article>
    
    <article class="product">
        <div class="product-img">
            product-img
        </div>
        <div class="product-brief">
             <p><h3>Name: </h3> Product-name</p>
             <p><h3>Price: </h3> $ 467</p>
        </div>
    </article>
    
    <article class="product">
        <div class="product-img">
            product-img
        </div>
        <div class="product-brief">
             <p><h3>Name: </h3> Product-name</p>
             <p><h3>Price: </h3> $ 467</p>
        </div>
    </article>
    
    <article class="product">
        <div class="product-img">
            product-img
        </div>
        <div class="product-brief">
             <p><h3>Name: </h3> Product-name</p>
             <p><h3>Price: </h3> $ 467</p>
        </div>
    </article>


    <article class="product">
        <div class="product-img">
            product-img
        </div>
        <div class="product-brief">
             <p><h3>Name: </h3> Product-name</p>
             <p><h3>Price: </h3> $ 467</p>
        </div>
    </article>


</section>


<footer>
<div>&copy; 2020</div>
</footer>
</body>

</html>
