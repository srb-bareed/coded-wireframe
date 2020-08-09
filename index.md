## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/srb-bareed/coded-wireframe/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/srb-bareed/coded-wireframe/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

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
