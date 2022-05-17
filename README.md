<!DOCTYPE html>
<html lang = "en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Bharat Mart</title>
        <link rel ="stylesheet" href="a2.css">
        <link href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@5.15.4/css/fontawesome.min.css"
        " rel="stylesheet">
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@5.15.4/css/fontawesome.min.css">

    
</head>
<body>
    


        <div class="container">
            <div class="navbar">
                <div class="logo">
                    <img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAoGBxQUExYRExMWFhYWFhETGBgYERkWFhYXFhYXFxYWGRYZHyoiGRwnHxYWIzQjJysuMTExGCE2OzYwOiowMi4BCwsLDw4PHRERHTAnIicwMjA6NDEuMDIxMDQwMjAwMDEzMDAwMDIwMDA//Z" width="125px">
                </div>
                <nav>
                    <ul id=""MenuItems>
                        <li><a href="">Home</a></li>
                        <li><a href="">Products</a></li>
                        <li><a href="">About</a></li>
                        <li><a href="">Contact</a></li>
                        <li><a href="">Account</a></li>
                    </ul>
                </nav>
                 <img  src="data:image/png;base64,iVBORw0KGhaUGG6uCAAAAAElFTkSuQmCC" width="30px" height="30px">
               <img src="https://e7.pngegg.com/pngimages/513/277/png-clipart-computer-icons-menu-bar-icon-design-hamburger-button-others-miscellaneous-angle.png" class="menu-icon oneclick="menutoggle()">
                <!----single product details--->

                <div class="small-container single-product">
                    <div class="row">
                        <div class="col-2">
                            <img src="new1.jpg"width="100%" id="ProductImg">
                        </div>
                        <div class="small-img-row">
                            <div class="small-img-col">
                                <img src="new1.jpg" width="100%" class="small-img">
                            </div>
                            <div class="small-img-col">
                                <img src="new2.jpg" width="100%" class="small-img">
                            </div>
                            <div class="small-img-col">
                                <img src="new11.jpg" width="100%" class="small-img">
                            </div>
                            <div class="small-img-col">
                                <img src="new4.jpg" width="100%" class="small-img">
                            </div>

                        </div>
                        <div class="col-2">
                            <p>
                                 T-Shirt By Jordan
                            </p>
                            <h1>Designer T Shirts</h1>
                            <h4>$90.00</h4>
                            <select>
                                <option >Select Size</option>
                                <option >XXL</option>
                                <option >XL</option>
                                <option >Large</option>
                                <option >Medium</option>
                                <option >Small</option>

                            </select>
                            <input type="number" value="1">
                            <a href="" class="btn">Add to Cart</a>
                            <h3>
                                Product Details<i class="fa faident"></i>
                            </h3>
                            <br>
                            <p><i>Give Yourself a New Style</i></p>

                        </div>
                    </div>
    
                </div>
            </div>
        </div>
    
            
<!---title-->
    
    <div class="small-conatiner">
        <div class="row row-2">
            
             <p>View More</p>
        </div>
        
    </div>
        <!-----featured products----->
    <div class="small-conatiner">
        <h2 class="title">Brands</h2>
        <div class="row">
            <div class="col-4">
                <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAASIAAACuCAMAAAClZfCTAAAAgVBMVEUAAAD////8/Pzc3Nw/Pz/S0tJ+fn4EBAT29vbx8fFNTU3Nzc2enp5lZWWvr68TExNxcXEcHBwiIiJERETCwsLi4uK7u7ulpaXGxsaGhobg4ODo6OiAgICNjY0rKyvX19czMzNaWlp2dnY6OjqXl5dVVVVJSUlgYGAvLy9tbW21tbVhYetPAAADuElEQVR4nO3b2XKiQBSAYRpUJO4b0RCjUTOOvv8DTgOSoNMICgJp/6+SiyzVdTx1egfDAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA+KUG8ns0MOwCmmosWkU0Uztz17Bn0wIa2s6FEFYBDdXNlxD9phAvuRvaicCwgJhqZiVM/5OtNp+jPM0MOmGGxKKowOqi0fQzdPqyuo172xl5pwyJryLDq4GWuLDa3NfQd4Y0G4tsoxn2soj/g9e6o6VO1I55dx3W1Lh9WUW+t55x4xJgFyXYmjwo0qo0PEWCTPlJpx83tTM5lVBQgHotjLzzbhbTvmlekt1VJnb2/qg4K9RMTJEQnXHmZnpB5XUfGGh1Rp1ovlcVUi9rM5ZswdFtrv+2SKwimbfXbG3IIhKzx4ZZHTmyLuUs1FGP2qZoDrK0IkvRybUwr7sPf/JaJIxJ3p/0Caoh/29fQqBVWyX0NjN9U9qX2+ASIqxcQoqkZdpKpy3amfrjL/V34a7eVvNd10ye/VNKRO7yduUEW4l+Yl5+upoQ86ttWMLRaz19ZpqeocDsyipyr+uaMdAQV7pXrI7kujB5cyqXjRpP+D0/Ac7RE/FUmUKZOLk/tVX9SS6rjqUHXp6BfxIie8nhbDprq7qfKVzlrPUi/6bbAdGZnsxRsBHbd8IO5fepF6NlqurIUayQxo7c7pYddZlsY/wefe71zgpK6OgPLEPVxlZuRy4vSdaO/O2h5KgrtZ5EB2mHhN1/J0hSNCYNTZ33r2kOygz5B6+LKI2TedA5tT0DSWEbn44qRf4YZc7c7nLXt8JC0/GgMauP5F1brKruuSzRhX+SpLwdict+LqmrcdcR6oVkWEI3nG5rbOiqxqQTjfdmt1lvum5z5jmO+V9JPdWSKIvB3r1YLjlVh1RDW+u8qz3zhJaof9bXmlWHU0vH+KRmanzemMPZndvTL4yUDvEUZbyvfTZWbFpjMFLaxFLkVR1MTTmxk26dLxlziN++basOpp7WsRQ964lamvnPaMSsrxYrozuf0tbfKylK5ZGiNJMoRRq+NlQM21icRuxl1aHUlf2949fspZhidcIntluavdBQqLegjNpcgyQbhG+QOD3qKIFtjKzg5JHLokR2uKGVlaTxk3z5bdom2/0UwTFt/vfXdfbpp0i7184LtfdT9LRPqmWyZxuS5itcPzKnJduGp/zMaVc4XKelmXIpm2YvtH3/vDAuVZTq1XyOd2NzaXAachXpAQAAAAAAAAAAAAAAAAAAAAAAAIDq/AMt6x0FHJgffAAAAABJRU5ErkJggg==">
                <h4>PUMA WEARS</h4>
                <div class="rating">
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star-o" aria-hidden="true"></i>
                </div>
                <p>$70.00</p>
            </div>
            <div class="col-4">
                <img src="https://i.pinimg.com/550x/a2/bc/bb/a2bcbb216b790eb34844962944a3a16e.jpg" , width="40%">
                <h4>AIR JORDANT WEARS </h4>
                <div class="rating">
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star-o" aria-hidden="true"></i>
                </div>
                <p>$90.00</p>
            </div>
            <div class="col-4">
                <img src="https://cdn.logojoy.com/wp-content/uploads/2018/05/30143359/2_big1.png">
                <h4>ADIDAS WEARS </h4>
                <div class="rating">
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star-o" aria-hidden="true"></i>
                </div>
                <p>$80.00</p>
            </div>
            <div class="col-4">
                <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAARMAAAC3CAMAAAAGjUrGAAAAflBMVEX19fUAAAD5+fn8/Pz6+vr+/v7q6up9fX3v7++3t7fOzs7Z2dnAwMCxsbHz8/N5eXmXl5eoqKjW1tbIyMg7OzuPj4+Dg4NoaGiqqqo0NDRiYmJXV1fl5eWfn59dXV0jIyNxcXFOTk4WFhZHR0cPDw8dHR0tLS2RkZFCQkKbm5vFyIMDAAAEtUlEQVR4nO3b22KiMBAGYJIQFUQRFLVKPbdu3/8FN0CxKAdBIYnt/93vMg6ZZJJQwwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABo3UB1AHdQKvuJPOjJfmQTlDF/FMp9JnfPTO4T66OMj63dZmTIHSh8TsZSH1gXNTm1JzOy8Lnk0uEBmWg4TChnw+WCEHLuyc6Iwb8I0W2GFQXTc/pbkZC3EWXyp9clIX0u+6kVRMEY9uRIIpupacqPgDni0UPpb6IEpdwMvcUhTgjpD+UPkSgIXzx7r8cwESuuKJi3JB9k+yV/GknC6EWvxFIwPm8DMfnYnuxJ6mgZSsZIFEpctoorh4pZNPRWh0tCyMpmyl4Td6MIXJWlExWMdSmY2DxUUzQx7sUxTFVFEK8w5302H2T7PlCYEYPaSRhqQhADZOityLWjY6qaRpKgBqc4joX80olaMsv9uEkI2Ulv4W/xdRLJUm4cIh/GNJjd5oOQQNHamxG19DGJDRuN9jDvm3w+yOdS2dr7w/S/oznJCkUMkNDaHQoSQtaOurU3g6bVLKWJFSvMoLBgIq6aFj6H79KIOt//RSuu/74uzgfZTnp6ZCTZ+SXeOz06ocwMLXdbkhAyG2kwjSTSZTgy6qySxQQiCuZfWT5UnQSU+KkcQpxO3pNYYahYYU7lCSHzofK1N8OcZkLroLOP9zDuZ0U+RAuvvhu5lg3Xajc0ajLDDo5V+YhOAqhmB8D8nI3Pa7GkC/cwOStbsyEiAg+vIgxaemPRjGr1S1eYC6UnAWX44irGdQv9SbLpr1hhUlvP0DAjlxOCi2f/P5PzoVe0h8kRLbxm08g3djv/PbMYV+xhclyt1t4s6tzGunmweJKWrGQPc+sU6NLCF2D5qvebBytasoo9TM5sOdZ1jAh0mo/4X8OBIlZcUTD3V5jUxlFwvdkA3xcEPamflLt7mBxFl3n1Ub8wbqtWUqo3/YU+VF3mNcD7xbGP7iYlupcaNSiYiEYnARXGZeHPjYoWX0wgA2dec4W52Ey5PicB5cxR6S/YOsW/QOSDZi9y69LrJKBC4QybEiOdXw11KiZU6r8vKv5NiQ+1l3mN9O78lo1nGzxl+FZQlcNSRz1O4euh5aWTecf71W632xyrjsiqyP8e7ynsgTJoKNDxJKAKe/Td1/TmjV9g7b0W3v9ZT1g7uh0o1pDfErdIl8u8hkyvq4Qczq82jaRY0E1GZsvXm0ZSzO0iI1pd5jXGO8hJ/1Va+BKt5+T0Qi18CVZyUPCgmXaXeQ9gkxYzsrJf4iTgnoqTgqa0vMx7BB22k5DPF2zhS9E2MrJ3zNefRn60sC/e+S90NlKHaT2XkEMQ/p6iuXgmI7Ply3cjRZ5YjTdTvS/zHld6l3GHvt8EPI89NKMo+ANfmZrveaJuRHXUHTMb3feKaYT90mkki9ZPysfkt7Tw95Tdo99ybf4Hhsg37tz/AG2n+Xc0raPGV9VNz2w+1fKLzY6x8WhfnA93FKr9002FTBZa/X3mG5u3dd+ze5SZfzQhMWpyZvSGvm3b/rA3MNhfWHVrod9UxwEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAkPMfHis0dBOPTiIAAAAASUVORK5CYII=">
                <h4>NIKE</h4>
                <div class="rating">
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star-half-o" aria-hidden="true"></i>
                </div>
            </div>
        </div>
    </div>
            
    <!-----Footer----->
    <div class="footer">
        <div class="container">
            <div class="row">
                <div class="footer-col-1">
                    <h3>
                        Download Our App
                    </h3>
                    <p>
                        Download App for Android and IOS Mobile Phone.
                    </p>
                    <div class="app-logo">
                        <img src="https://images.samsung.com/is/image/samsung/assets/uk/support/lucidcx/wherecanifindtheplaystore.png?$ORIGIN_PNG$">
                        <img src="data:image/jpeg;base64,/9j/4AAQ">
                    
                    </div>
                </div>
                <div class="footer-col-2">
                    <img src="https://99designs-blog.imgix.net/blog/wp-content/uploads/2019/09/attachment_109861736-e1567623620590-1.png?auto=format&q=60&w=2000&h=862&fit=crop&crop=faces">

                    <p>Download App for Android and IOS mobile phone.</p>
                </div>
                <div class="footer-col-3">
                    <h3>
                        Useful Links
                    </h3>
                    <ul>
                        <li>Coupons</li>
                        <li>Blog Post</li>
                        <li>Return Policy</li>
                        <li>Join Affiliate</li>
                    </ul>
                </div>
                <div class="footer-col-4">
                    <h3>
                        Follow us
                    </h3>
                    <ul>
                        <li>Facebook</li>
                        <li>Twitter</li>
                        <li>Instagarm</li>
                        <li>You Tube</li>
                    </ul>
                </div>
            </div>
            <hr>
            <p class="Copyright">Copyright 2022 - Bharat Mart</p>
        </div>
    </div>
    <script>
        var MenuItems = document.getElementById("MenuItems");
        MenuItems.style.maxHeight = "0px";
        function menutoggle(){
            if(MenuItems.style.maxHeight == "0px"){
                MenuItems.style.maxHeight = "200px";
            }
            else{
                MenuItems.style.maxHeight = "0px";
            }
        }
    </script>   
    <!---js for products gallery-->
    <script>
        var productImg = document.getElementById("ProductImg");
        var smallImg = document.getElementByClassName("small-img")
        SmallImg[0].oneclick = function()
        {
            ProductImg.src = SmallImg[0].src
        }
        SmallImg[1].oneclick = function()
        {
            ProductImg.src = SmallImg[1].src
        }
        SmallImg[2].oneclick = function()
        {
            ProductImg.src = SmallImg[2].src
        }
        SmallImg[3].oneclick = function()
        {
            ProductImg.src = SmallImg[3].src
        }

    </script>



</body>
</html>


/// MAIN PAGE 

<!DOCTYPE html>
<html lang = "en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Bharat Mart</title>
        <link rel ="stylesheet" href="c2.css">
        <link href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@5.15.4/css/fontawesome.min.css"
        " rel="stylesheet">
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@5.15.4/css/fontawesome.min.css">

    
</head>
<body>
    


        <div class="container">
            <div class="navbar">
                <div class="logo">
                    <a href="h3.html" <img src="data:image/jpeg;base64,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" width="125px"></a>
                </div>
                <nav>
                    <ul id=""MenuItems>
                        <li><a href="h3.html">Home</a></li>
                        <li><a href="p2.html">Products</a></li>
                        <li><a href="">About</a></li>
                        <li><a href="">Contact</a></li>
                        <li><a href="a1.html">Account</a></li>
                    </ul>
                </nav>
                <a href="b1.html"<img  src="data:image/png;base64,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" width="30px" height="30px"></a>
               <img src="https://e7.pngegg.com/pngimages/513/277/png-clipart-computer-icons-menu-bar-icon-design-hamburger-button-others-miscellaneous-angle.png" class="menu-icon oneclick="menutoggle()">
            </div>
        </div>
        <!----AccountPage -->
        <div class="account-page">
            <div class="container">
                <div class="row">
                    <div class="col-2">
                        <img src="data:image/jpeg;base64,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" width="100%">
                    </div>
                    <div class="col-2">
                        <div class="form-container">
                            <div class="form-btn">
                                <span  onclick="login()">Login</span>
                                <span onclick="register()">Register</span>
                                <hr id="Indicator">
                            </div>
                            <form  id="LoginForm">
                                <input type="text" placeholder="Username">
                                <input type="password" placeholder="Password">
                                <button type="submit" class="btn">Login</button>
                                <a href="">Forgot Password</a>

                            </form>
                            <form id="RegForm">
                                <input type="text" placeholder="Username">
                                <input type="Email" placeholder="Email">
                                <input type="password" placeholder="Password">
                                <button type="submit" class="btn">Register</button>


                            </form>
                        </div>
                    </div>
                        
                </div>
            </div>
        </div>
        
        <!-----Footer----->
    <div class="footer">
        <div class="container">
            <div class="row">
                <div class="footer-col-1">
                    <h3>
                        Download Our App
                    </h3>
                    <p>
                        Download App for Android and IOS Mobile Phone.
                    </p>
                    <div class="app-logo">
                        <img src="https://images.samsung.com/is/image/samsung/assets/uk/support/lucidcx/wherecanifindtheplaystore.png?$ORIGIN_PNG$">
                        <img src="data:image/jpeg;base64,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">
                    
                    </div>
                </div>
                <div class="footer-col-2">
                    <img src="https://99designs-blog.imgix.net/blog/wp-content/uploads/2019/09/attachment_109861736-e1567623620590-1.png?auto=format&q=60&w=2000&h=862&fit=crop&crop=faces">

                    <p>Download App for Android and IOS mobile phone.</p>
                </div>
                <div class="footer-col-3">
                    <h3>
                        Useful Links
                    </h3>
                    <ul>
                        <li>Coupons</li>
                        <li>Blog Post</li>
                        <li>Return Policy</li>
                        <li>Join Affiliate</li>
                    </ul>
                </div>
                <div class="footer-col-4">
                    <h3>
                        Follow us
                    </h3>
                    <ul>
                        <li>Facebook</li>
                        <li>Twitter</li>
                        <li>Instagarm</li>
                        <li>You Tube</li>
                    </ul>
                </div>
            </div>
            <hr>
            <p class="Copyright">Copyright 2022 - Bharat Mart</p>
        </div>
    </div>
    <script>
        var MenuItems = document.getElementById("MenuItems");
        MenuItems.style.maxHeight = "0px";
        function menutoggle(){
            if(MenuItems.style.maxHeight == "0px"){
                MenuItems.style.maxHeight = "200px";
            }
            else{
                MenuItems.style.maxHeight = "0px";
            }
        }
    </script>   

    <!----JS for toggle Form---->
    <script>
        var LoginForm=document.getElementById("LoginForm");
        var RegForm=document.getElementById("RegForm");
        var Indicator = document.getElementById("Indicator");

        function register(){
            RegForm.style.transform = "translate(0px)";
            LoginForm.style.transform = "translate(0px)";
            Indicator.style.transform = "translate(100px)";
        }
        function login(){
            RegForm.style.transform = "translate(300px)";
            LoginForm.style.transform = "translate(300px)";
            Indicator.style.transform = "translate(0px)";
        }
    
    
    </script>
    



</body>
</html>


/// PRODUCT PAGE 

<!DOCTYPE html>
<html lang = "en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Bharat Mart</title>
        <link rel ="stylesheet" href=""
        <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@1,200&display=swap" rel="stylesheet">
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@5.15.4/css/fontawesome.min.css">

    
    </head>
    <body>
        <div class="header">


        <div class="container">
            <div class="navbar">
                <div class="logo">
                    <img src="project/log.png" width="125px">
                </div>
                <nav>
                    <ul id=""MenuItems>
                        <li><a href="">Home</a></li>
                        <li><a href="">Products</a></li>
                        <li><a href="">About</a></li>
                        <li><a href="">Contact</a></li>
                        <li><a href="">Account</a></li>
                    </ul>
                </nav>
                <img src="project/cart.png" width="30px" height="30px">
                <img src="https://e7.pngegg.com/pngimages/513/277/png-clipart-computer-icons-menu-bar-icon-design-hamburger-button-others-miscellaneous-angle.png" class="menu-icon oneclick="menutoggle()">

    
            </div>
            <div class="row">
                <div class="col-2"
                    <h1>Desh Ka<br> Apna Mart</h1>
                    <p>Purchase Like Anything</p>
                    <a href="" class="btn">Explore Now  &#8594;</a>
            </div>
            <div class="col-2">
                <img src="project/lo.png">

            </div>
            

        </div>
    </div>
    <!---featured cateogries-->
    <div class="cateogries">
        <div class="small-container">
            <div class="row">
                <div class="col-3">
                    <img src="https://penji.co/wp-content/uploads/2021/03/Top-apparel-brand-logos.jpeg">
                </div>
                <div class="col-3">
                    <img src ="https://cdn.dribbble.com/users/384646/screenshots/6242189/gadget-news-logo-design-concept-brand-identity.jpg?compress=1&resize=400x300">
                </div>
                <div class="col-3">
                    <img src="https://www.logodesign.net/logo-new/food-items-in-brown-bag-with-leaves-for-grocery-store-9053ld.png">
                </div>
            </div>

        </div>
    </div>
    <!-----featured products----->
    <div class="small-conatiner">
        <h2 class="title">Featured Products</h2>
        <div class="row">
            <div class="col-4">
                <img src="https://99designs-blog.imgix.net/blog/wp-content/uploads/2018/06/savage2.jpg?auto=format&q=60&fit=max&w=930">
                <h4>Designer T-Shirts</h4>
                <div class="rating">
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star-o" aria-hidden="true"></i>
                </div>
                <p>$70.00</p>
            </div>
            <div class="col-4">
                <img src="https://99designs-blog.imgix.net/blog/wp-content/uploads/2016/12/attachment_87652694-e1513588202331.png?auto=format&q=60&fit=max&w=930">
                <h4>Designer T-Shirts</h4>
                <div class="rating">
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star-o" aria-hidden="true"></i>
                </div>
                <p>$90.00</p>
            </div>
            <div class="col-4">
                <img src="https://cdn.logojoy.com/wp-content/uploads/2018/05/30143359/2_big1.png">
                <h4>Designer T-Shirts</h4>
                <div class="rating">
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star-o" aria-hidden="true"></i>
                </div>
                <p>$80.00</p>
            </div>
            <div class="col-4">
                <img src="https://images-platform.99static.com//wgCzJuXXfoqe8nNKg--NdhU4oyw=/178x177:866x865/fit-in/500x500/projects-files/106/10661/1066168/9ead8f05-9230-4018-bc0d-2052d5634add.png">
                <h4>Designer T-Shirts</h4>
                <div class="rating">
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star-half-o" aria-hidden="true"></i>
                </div>
                <p>$100.00</p>
            </div>
            <h2 class="tilte">Latest Products</h2>
            <div class="row">
                <div class="col-4">
                    <img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAoHCBUVFRgVFRUYGBgZGBgYGBgYGBgYGBgYGBgaGhgYGBgcIS4lHB4rIRgYJjgmKy8xNTU1GiQ7QDs0Py40NTEBDAwMEA8QHhISHzghJCs3MTQ0NDQxOzQ0NDQxND80NDQ0NDQ0NDQxNDQ0NDQxNDQ0NDQ0NDQ0NDQ0NDQ0NDQ0NP/AABEIAN4A4wMBIgACEQEDEQH/xAAcAAABBQEBAQAAAAAAAAAAAAAGAAECBQcEAwj/xABJEAACAQICAwsIBwcDAwUAAAABAgADEQQSBiExBQciMkFRYXGBkbETUoKSocHC0RZTYmNyouEUI0KDk9LwJFSyRNPxFTM0Q3P/xAAYAQEBAQEBAAAAAAAAAAAAAAABAAIDBP/EACARAQEAAgIDAQEBAQAAAAAAAAABAhESMQMh0UFRMiL/2gAMAwEAAhEDEQA/ANK3a3b/AGdlXLmzX6LWt85WfTD7s94njprx6fU3wQZMzJtroV/TH7s94j/TD7s94glHjxGxb9L/ALs94i+l/wB2e8QTEV5cVsV/TD7s94jHTH7s94gpGMuK2Lfph92e8RfTD7s94gkJIS4rYs+l/wB2e8TtwukGdc2W23Vt2TPcXj6dMcNwOjae6CO6GnFQPbD2VNl3GbOee3IJZYZa9HHLHftubbuEbVEqsRpuqG3ky3URBvRfPicMtSuxzsW1LwVtyatuzpnM24RVyXZmA2X2DsGqcOWX9emYYfwUppzfZRb1hPY6aar+SPeIMfstuSeGKS2qXLL+nhh/BHjNPwiM/kGbICxAYXIG23ZI7lb4lPEUxUSmbXIKki6kcht2HtgfimARydgU36rG8zXcjdaph3zIbg2DoeKwHIeY8xH6Tp47ct7cfLJjrT6G+mf3Z7xF9M/uz3iZnudpVQqamuh+1Yj1h7xL0G+saxyHknTi5bF/0z+6PeIx01H1R7xBEyBhxWxidNh9Ue8SP04H1R7xA4xrS4rY0Gmw+qPeIjpp90e8QMEkZcVsY/TYfVHvEttwd3f2ksMmXLbbrve/ymbGFugHGq+h4NKzSnscxRRRAK0246dTfDBiE+m3HTqb4YLkwx6N+FJSIkhNA8VpKMZJCc+Ix1NOO4HRe57hAzSPdqqK9SlmsilQAObKGuee95RPiSeWbmM/WblfwbYvSpF4ilukm3sEo8bpPWfUGyj7Or27YOs8V5r1Omfd7TxGKZjrYn5zkIjsI4XnhfZnpv2hNEfsKMNgs1/sVAHBPUWP+CW1ZOicO9VVD7n0769Rpkfg4Nj2S7xWHy8E6x/Ceccx6R8jPL5MP2PThn+KGtSuZTY+nwrQwp4UE3lU+BzO7nYDYTlp3lgM3eonyDjnBBPRy+yZNNu0yo5MFXci1kyjrqMEA6+FMYZP/M9Hix9WvP5svcjyU21y13P3Yq0uI5A5r3X1TqlYE5DHy2naOF1Rtg9K2PHVW6uC3yPsl3gt16VXUrWbzW4J+R7JmCvOiniCDe5vzx1KN2NVjQD3A3Vq/tCIGLIxylTxbWJJA5CNvZDwTFmmpTxRR4FEwt0A41X0PBoJwt0B41X0PBpnIwcRRRRAK0146dTfBBgwn0146dTfBBkwx6N+IiSEjJCaCQiaKeOKrhEdzsRWY+iCfdJMu0jq5sVWP2yPVAX3eyVmePXqF2Z22sxY9bG59pnnNs6emaNnjSIjtaexbmkbyN9kcGQbnvKYi+DqJ5lY/nW/jNExNEOpVusEbQeRh0zJd42twcUn/wCbj8y/Ka8puJjKNxTlWU5W4w5RsYecP81T0oYW4tsHKflLKpSVrZhsN+r9JJrTnwm3TndM0342FPAoo1Z6yC3OFVnPXrVZiQM1HfxxhNXDUb6lR3I/EwRT+RplhM7YzUccuzVG1RryLteNLa0kWiDSMa8NrS00f3QFGursAQbqTyqGsMw6vAmaaJjpmgaF7oGpSZGN2pkWJ25GHBHTYgjumWhJJCRjiSIiFmgO2r6Hg0E4W6BbavoeDTORg3iiiiAVptx06m+GDMJtNeOnU3wQYhj0b8KPI3jiaCUqtJ3thaxvbgW7yBbtvaWgg/pw4XCsCbZnQAecb5rey/ZGdqs1JkbxRRtEPGvHMaW0kNkSxgdslFNM3kK9sXXTz6F/UcfObah1T5/3n62XdNB51Oqv5QR4TfUMze1OnueeQMmhkHgXz3vt4vPuk68lNKdP8mc+2oR2QJJlppRjvL4vEVdoes5H4QxC/lCypYzYRijCKZR40V4pIoV6BD97UN/4Bq9Ia/Z7YKQj0Ga2JI56bDuZT7oFoMUUUkeFmgO2r6Hg0EYXaA7avoeDTORg4iiiiAXprx06m+GDBhNprx06m+CDTQx6N+PMmOsiY4mg9BAbfEqnNRT+HKzdZJA9gHthysz/AHwcTetTTLbIhObnznZ1DL7TGdihMA8gjMIiZGVSUUYRRSS7Y4kRJLtlBRXva1cu6WHPSw71M+iieFPmnQp8uNpt5oc9yNPpINcg9EKZ061M5N1a+SjVfzKbt6qE+6dIlBpxiMmAxbXt+4cDrcZB7WEi+ZBsHVOrAYA1TYMq69pnKZ5mWW9ehjrfsSjcCgo4eIHYVHzkGweBTbVZuo3/AOIg7aKcuGX7a6cp+R17oGlceSBtruTfXstt7ZxiKITcmozbunlvoxjFpYhWc5Vsyk8guLC/ReVEaIbKYp50agZVYEEEA3XWDcbR0T1EkiYXaAbavofFBIwt0A21fQ+KZpg4iiiiAVptx06m+GDBMJtN+OnU3wwYMMejfiJjiK0QmgmDM00zx4q4hlC2FO6X5SQbknouTb9ZpImbaa1wcU2XUVRFY7OFYk9ephGCh8WkSJJm6PdGuOY9/wCkqiEUipjmSKTEhJrslBVzoqf9StvNcd6298+kcM90Q/ZHhPnHQ5b4kdCN4qPfPobcx700/CPCVM6XC7ID77GIy7m1h57Uk76isfYhhvTOqZlv21CuEppfj4hSekJTfV3sJRMSJnmJNtkgJVQ8UaKBIxxOrySCiWIJZnyoQbABFBe4trvnS2zZOQSRzGj2jWkmi6GJUXD8Pik3p6xfKdvUL3t2wgvA/QVqpDcIGkNQUm5V7g6htAIzdEL5I5hZoBxqvoeDQRJhdvf7avoeDTN6MHMUUUQCdN+OnU3wwZhPptx06m+GCrGGPRvw94gZGITQSmb6ZsDinsBqVAbW1nLe56dYHYJoeJBKOAcpKMM3NwTr1c22ZBUudea49o6+eMFeZA57df6Rm6wfZJW6Af8AOaQbqAlUYGKdQxjeRNEgW8oKgPKDlKkdRuD2dM5ZIpNZGOkol/ok1qjt9i3ewPum/wC4fCppbzRPnzR6kxzsouBlB7c3ym4b326Iq4fITw04JHLb+E93hGmdCyi20c0ybf1rf/FTkvWY9Y8mo8WmoYR7Fgdp190xnfpxBbE0V82kxHpOR8MIGbOZERGKBKKNHEkP9E9zadTCr5RFcF3YZhs2KbHk4vsgTj0RajqhugZgh51vq18urlmj7hYX/RImzPTbWOTymY3/ADTL1kjxiI8UkN9AadqdR+dwvqrf44VEwN0JxajNTaprY8CnY21C7Nmta/RfkMMpIxML97466voeDQOaGG97tq+h4NC9GDuKKKQBOm/HTqb4YLNCnTc8On1N8MFWhj0b8K8eRAk5oOTdYfuKvCy/u34Ws5RkOvVr1dEyM9k1bSByMNWsL/u3HYRYnsBJ7JlLAxgqLExix5SZK/V3fKMydI7/AJyqeqYYmmal9QdVO3aysw17P4GnlaF2BwC/+l1GYEFiXueUowClei1x2mCMZ0jRxFEJIe73dJXp10NsxZCOewU/OaFolhclViNR1X9vzmYaH0HVRUQ8IsRbnA1fObTo/SuocizEC46ZFa4qkLq/YfnME31celbG3Q3VKSpfnIdyT+ab1utVTyZQtYsMo5xcbeyfOunuDWliiikkeTQknnN7yAZiiimSUkBfUOXUJGetCoVZWFiVIYX2Eg3190k2KjSyIqDYqqvqgD3TP9OKSLWRUphOCSzKoUMSTzDWRynph9h8QKio67HVWHUwvAbfAdjVpqeKEJXrLEN/xWSCkVooopf6GYfNiM9xwFY2J1nMCuodF5oMz7Qsf6nZeyPr83Zr93bD+CMYY73u2r6Hg0DjDHe921fQ8GhejB3FFFIAjTjj0+p/ggtCnTjj0+p/ggvDHo34cCNFHtNBVaTV8mFqnnTL65C/FMtNppulGCetSWlTUs71FA1gAWzElidQGrwlQm9hjCL56A6M7nwSXLGdmY29Ae8g0L8boBi6YJPkmt5rtf2qIM4vBvTNnXL3EeyXKXqq45TuDnS6sKWFSituHlUW1cBFBNhzXCd8AIe6V+TqOlBmytkDox2ZmZlKn1R1wMx259SkbOthyMNanqPulMpvX6uN1tySdNbnbbae4E+6RERM0y1bQXDKcKhHGu2a/SxIt3w53OV7WBIEEdF8J5NWQbAQB2KAfbDzcumcokXpS3JRjdyzduqY1vx4ZExyhBYHDodXPnqD4RN6ppYa5iG/cn+rot51DL6tRz8UAzaKKKBKOBOihTQjMzW12yjb13k2roOIuvnP6/pDf8jUn9rR9G2H7NS6EsesEgjvgnp5m/aEuOD5MZebjNe3sndoHugSXosb/wD2L7Aw9qnvnVjdwGxWMYOzLTVEylbXIINwL7OFm5JW6m6JN3UAEU1Krva4ci61qqnpyMPAQU3b0NrYe5VhVUeaCGA/CdvYZmZ41q+PKJaCIfKVDyBACOtxbwMNTBbQSiAlR+UuF7FW/wAUKDNsGJhjvebavoeDQNaGW93tq+h4NC9GDyKKKQBGnXHp9T/BBaFOnXHp9T/BBe0MejfhCSAjgRiZoPTC8deuFdM8EQSwx4a/iHjCqieDOHk7ejxf5Ve7J4Jma06QqY2mpAIUs5B18VTbV+IrNA0krZUJ6IEaLpnrVanMFQekcx/4rDxz/pryXWIf04r5sUR5iKvi/wAUpauNqMgRmJVTcA923mnvu7Xz4iq3O7AdSnKPYJwT02PLuledG59LPURfOZR3sL+y855c6KUc2JTbwQzatewWHtIkGr7knhAc5mg4GmAogBuKvDW3dNDwqWXZKl6VDqmL7+JBqYW3mVB+ZPnNhr1Dr1TH9+HAnJRrEk8N0N72GdQygeo0gyyIRRQJRCNEJJ3bj47yFZKnIrcLpU6mHcTNb3PANa41gopB5CCzETFiJre9+5eijHWVTJ2Kzhfy5Zzz/wAuni7F9U2EGt16kIcW2q0FsW+dwOQbeof4J55N3T171NvHAYJaSlV5XZj+Jjc26BqHZOgyUiZ7HhQaGW93tq/y/B4GNDPe621fQ8HhelB5FFFIAjTjj0+p/ggwITac8en1P8EGCYY9G/DkyJMRimgem1mHWPGFtDiwQhbhDdeycfL3Ho8PVC+l9SyNB/RlAmHLnVmZ3PUvBHsT2yz09q2Q9crcUfI4Fr6iKGU/idcv/JpeKLzX1IzRjcknl19+uRiinoeYoVaCgq9R7DUqpckDjG51n8IgrCPR3SBMNTYFXZmcscuUC1gBrJvz8nLItc0brKz3PNq5fC8N0qrbae5vlMIwu+O9PN5LDoGINnds2U21HKFF+e157VtPN0M1xiWUGxsqUrC4BsLodUrdpuLuOQN6rfKA++fR8rgKqhSShSqNQ1ZDwjtvxGeZ82mOPc8LEuexAPYonJptiqrJQc1HIdWDAuxBOo6xfrhtAy8aOZEwRRXitPWnTvGe1tFV5ZrW9hSK4UsdjO5XqFh4gzK6xAFptWiGHCbn0ANpTP2sxY/8pz83qadPD7u3VulVsDB2gLlm5zYdXL/nRLHdSrqnGi2AE5+PH3t282WsdETGjmMTPQ8qDQy3uttX0PB4FsYZ73G2r6Hg8zSPooopAEadcen1P8EFrwp0649Pqf4ILQx6N+FEYojNAxhZgDdB1QTIhTueeCOqcvL+O/h/QRp4mYonnOF9Yge+VOnFfLhso/jdV7Fu3wiXelKfvqV+SqviIJafVf8A2U/Gx/KB74+LpebuA+KNFOzzlE9r6oximaXvhqdzLUOWIUJrttLW4q6/CV2EYD+HunfSxI1Cx267rq2c81JA8xVfkS/pfpPTdTdF6tNKRphcjE3vcm4tbZOR8QbquwfrI1aoJPGOvbLULkdCNsjOhmvqtaeNrQsB1Xnki/NIFp1bk4XytVV5L3b8I2jt2dsbZIpjuubIxPFPcZo2jmmwyLRroFVRlWot7WA/jXWbDVwl7hOvcrccZw5UC049LtyqaAV0Pk8zqlXKoKlWa+YqLEm4F7EX5Zw5TK6r0cLhNyrerWVwGUhlJ1EEEbdesRXgbhkNFAyMwYFSFvwW1EsCOXXYWty3vDG83jjxc88uRMZ5sZIyBmmUCIa73G2t/L8GgW0NN7jbW/l+DQvSg+iiikARpzx6fU/wQWMKdOuPT6n+CCpMMemr8ImK8a8YzTJy0JNyHugMGTCTcYWRf82/+Zy8vUdvD3VTpTgWZc6i5R0ew2kKQWt02mV6ZYjPiSo2IiqObWM5P5putZAZkunm5iLma1nUrY+chOWxH2SVseY25IeO69NeXHc2BoojGJnd5iiURCetJDe8JNl0YamZ7Ou3ZexPNyG0lh6tttuWRauGNrdHXedA56acNevk1DbJVattSge+e1MgMOiw9sg1RRycpgXMQ55PdEaDbTb3zrUk8kdrAbZaCsMM9AtyjUfNbVtJ+yCQB2kHuntS0HdqCMLmvUyuFvZaaN55I221nm2AE3h3uLuXTwVAIWBIHDbZdjcm3aTYThnlOo7+Px2XddGICpYDzfCCekCGvTamNdzftB4I6OWWmKxmdcw1gEgdvT2TgXWe3wnOT275esarsJuZUUqtRlKJltl2uQNpBHB6dZlxeMTFPQ8R2MgTHMiZFFoa72+2t/L8HgSTDXe341b+X4PC9IfxRRSAG07PDpdT/BBW8O9JdyTiGWzBcoO0XvfL09Epvom/1q+qfnMzKT1W7jb7gcjQl+ij/Wr6p+cb6Jv9avqn5x5RcKGiYVYHgoByAe6ea6JNcXqi1/NPzlsNyzltmHdOedl6dfHjre1UmPUuU5gD2G/ygFvpoGRGUHgnWfsk219tu+GFbRGu1daoxKgI18vk21jmvm1X5dXNOnSHQ9sTTKCqqGxFypbaLbLiZxuq6ZyWWRgWGUMpB5I74MiadS3nqqm4xif0m/vnsd6mp/uk/pN/fPRMsbPby8MmT+RI5JMOw/hE1I70tX/dp/Rb++Md6Cr/ALxP6J/vlzxi4VljVvsyNJtfXs6+Sagd52oduMX+kf7ol3nqg1jGL/SP90OcXCs2UNnsQQQddxsAPLPJagFydfNNTbeirEZTjVtzeSNu7PFS3n3X/qkJ5zSb++UziuNZoi1G5lEn+zINbEsemaad6qra37VT/pP/ANyRO9NUP/VJ/Sf/ALk1zxXDJHc7TBTQQKL1AoV1AN8w4I6lNr3nDjsQahBruTrutJDq9K2szvo71VZGzJjVU2IutJhcHaDw9kssFve16SFVxVPOSSahoktY8mt5xyk/Hoxy9e4G8Ti3sqFQi7VReOelv8AnRgmLDMVtydvLLtd7yuFIGLTOSbuaRJ7OHqMtRoa1gPKrq+yfnDHW/azts1AxEYUfQ5vrV9U/OL6Gv9cvqn5zryjhxoVaQYwsOhj/AFy+ofnInQxvrl9Q/wB0OUXGhImG29rtrfy/B5xnQtvrl9Q/3Qi0R3EbDGpdw+fLsUi1s3SeeFyl9RcbPdFUUUU0w//Z">
                    <h4>Blazzer</h4>
                    <div class="rating">
                        <i class="fa fa-star" aria-hidden="true"></i>
                        <i class="fa fa-star" aria-hidden="true"></i>
                        <i class="fa fa-star" aria-hidden="true"></i>
                        <i class="fa fa-star" aria-hidden="true"></i>
                        <i class="fa fa-star-o" aria-hidden="true"></i>
                    </div>
                    <p>$170.00</p>
                </div>
                <div class="col-4">
                    <img src="https://img2.exportersindia.com/product_images/bc-full/2018/12/6034254/mens-designer-lower-1545390296-4584693.jpeg">
                    <h4>Lower</h4>
                    <div class="rating">
                        <i class="fa fa-star" aria-hidden="true"></i>
                        <i class="fa fa-star" aria-hidden="true"></i>
                        <i class="fa fa-star" aria-hidden="true"></i>
                        <i class="fa fa-star" aria-hidden="true"></i>
                        <i class="fa fa-star-o" aria-hidden="true"></i>
                    </div>
                    <p>$50.00</p>
                </div>
                <div class="col-4">
                    <img src="https://i.pinimg.com/originals/b4/90/78/b490784213bba72d6869a007de213823.jpg">
                    <h4>Jacket</h4>
                    <div class="rating">
                        <i class="fa fa-star" aria-hidden="true"></i>
                        <i class="fa fa-star" aria-hidden="true"></i>
                        <i class="fa fa-star" aria-hidden="true"></i>
                        <i class="fa fa-star" aria-hidden="true"></i>
                        <i class="fa fa-star-o" aria-hidden="true"></i>
                    </div>
                    <p>$70.00</p>
                </div>
                <div class="col-4">
                    <img src="https://www.dhresource.com/0x0/f2/albu/g10/M00/4D/0F/rBVaVlzYI5mAbXHcAAFiWMrwIWw381.jpg/18ss-new-mens-luxury-designer-shoes-special.jpg">
                    <h4>Shoes</h4>
                    <div class="rating">
                        <i class="fa fa-star" aria-hidden="true"></i>
                        <i class="fa fa-star" aria-hidden="true"></i>
                        <i class="fa fa-star" aria-hidden="true"></i>
                        <i class="fa fa-star" aria-hidden="true"></i>
                        <i class="fa fa-star-half-o" aria-hidden="true"></i>
                    </div>
                    <p>$120.00</p>
                </div>
        </div>
    </div>
    <!-----Offer----->
    <div class="offer">
        <div class="small-container">
            <div class="row">
                <div class="col-2">
                    <img src="https://img.gkbcdn.com/s3/p/2019-06-26/xiaomi-mi-band-4-smart-bracelet-0-95-inch-amoled-color-screen-orange-1571987603971.jpg">
                </div>
                <div class="col-2">
                    <p>Exlusively Available on Bharat Mart</p>
                    <h1>Smart Band 4</h1>
                    <small>
                        The Sony smart Band 4 Features has some amzazing
                        features which makes it different
                    </small>
                    <a href=""class="btn">Buy Now &#8594;</a>
                </div>

            </div>
            <!----Testimonial-->
            <div class="testimonial">
                <div class="smallcontainer">
                    <div class="row">
                        <div class="col-3">
                            <i class="fa fa-quote-left">

                            </i>
                            <p>
                                Its a Testimonial Program
                            </p>
                            <div class="rating">
                                <i class="fa fa-star" aria-hidden="true"></i>
                                <i class="fa fa-star" aria-hidden="true"></i>
                                <i class="fa fa-star" aria-hidden="true"></i>
                                <i class="fa fa-star" aria-hidden="true"></i>
                                <i class="fa fa-star-o" aria-hidden="true"></i>
                            </div>
                            
                            <img src="https://www.koimoi.com/wp-content/new-galleries/2021/12/new-spider-man-trilogy-to-witness-tom-hollands-peter-parker-in-college-001.jpg">
                            <h3>Tom Holand</h3>
                            <img src="data:image/jpeg;base64,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">
                            <h3>Tom Cruise</h3>
                            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1f/Dwayne_Johnson_2014_%28cropped%29.jpg/640px-Dwayne_Johnson_2014_%28cropped%29.jpg">
                            <h3>The Rock</h3>

                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!---Brands-->
    <div class="brands">
        <div class="small-container">
            <div class="row">
                <div class="col-5">
                    <img src="https://i0.wp.com/www.logotaglines.com/wp-content/uploads/2021/11/PhonePe-Logo-Tagline-Slogan-Owner-Founder-480x480.jpg?resize=480%2C480&ssl=1">
                </div>
                <div class="col-5">
                    <img src="https://lh3.googleusercontent.com/RkN2IcvWd4DWNTVbh8Ma2G77D42Gd5HP0Deydf9FmzbDUMxLNsmWUSE8k562PgEPKzmF_OGWIiySxhdLUdNcxJ3t8kc7JugTaAhHYA">
                </div>
                <div class="col-5">
                    <img src="https://download.logo.wine/logo/Paytm/Paytm-Logo.wine.png"
                </div>
                <div class="col-5">
                    <img src="https://logowik.com/content/uploads/images/897_paypal.jpg">
                </div>
                <div class="col-5">
                    <img src="https://static.amazon.jobs/teams/378/thumbnails/AmazonPayLogo-543.jpg?1508227956">

                </div>
            </div>
        </div>

    </div>
    <!-----Footer----->
    <div class="footer">
        <div class="container">
            <div class="row">
                <div class="footer-col-1">
                    <h3>
                        Download Our App
                    </h3>
                    <p>
                        Download App for Android and IOS Mobile Phone.
                    </p>
                    <div class="app-logo">
                        <img src="https://images.samsung.com/is/image/samsung/assets/uk/support/lucidcx/wherecanifindtheplaystore.png?$ORIGIN_PNG$">
                        <img src="data:image/jpeg;base64,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">
                    
                    </div>
                </div>
                <div class="footer-col-2">
                    <img src="https://99designs-blog.imgix.net/blog/wp-content/uploads/2019/09/attachment_109861736-e1567623620590-1.png?auto=format&q=60&w=2000&h=862&fit=crop&crop=faces">

                    <p>Download App for Android and IOS mobile phone.</p>
                </div>
                <div class="footer-col-3">
                    <h3>
                        Useful Links
                    </h3>
                    <ul>
                        <li>Coupons</li>
                        <li>Blog Post</li>
                        <li>Return Policy</li>
                        <li>Join Affiliate</li>
                    </ul>
                </div>
                <div class="footer-col-3">
                    <h3>
                        Follow us
                    </h3>
                    <ul>
                        <li>Facebook</li>
                        <li>Twitter</li>
                        <li>Instagarm</li>
                        <li>You Tube</li>
                    </ul>
                </div>
            </div>
            <hr>
            <p class="Copyright">Copyright 2022- Bharat Mart</p>
        </div>
    </div>
    <script>
        var MenuItems = document.getElementById("MenuItems");
        MenuItems.style.maxHeight = "0px";
        function menutoggle(){
            if(MenuItems.style.maxHeight == "0px"){
                MenuItems.style.maxHeight = "200px";
            }
            else{
                MenuItems.style.maxHeight = "0px";
            }
        }
    </script>   




</body>
</html>
                                                 
///  Backend page 
                                                 
                                                 <!DOCTYPE html>
<html lang = "en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Bharat Mart</title>
        <link rel ="stylesheet" href="p1.css">
        <link href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@5.15.4/css/fontawesome.min.css"
        " rel="stylesheet">
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@5.15.4/css/fontawesome.min.css">

    
</head>
<body>
    


        <div class="container">
            <div class="navbar">
                <div class="logo">
                    <img src="data:image/jpeg;base64,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" width="125px">
                </div>
                <nav>
                    <ul id=""MenuItems>
                        <li><a href="">Home</a></li>
                        <li><a href="">Products</a></li>
                        <li><a href="">About</a></li>
                        <li><a href="">Contact</a></li>
                        <li><a href="">Account</a></li>
                    </ul>
                </nav>
                 <img  src="data:image/png;base64,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" width="30px" height="30px">
               <img src="https://e7.pngegg.com/pngimages/513/277/png-clipart-computer-icons-menu-bar-icon-design-hamburger-button-others-miscellaneous-angle.png" class="menu-icon oneclick="menutoggle()">

    
            </div>
            <div class="row">
                <div class="col-2"
                    <h1><i><b>All Products-Bharat Mart</b></i></h1>
                     
                    <p>Purchase Like Anything</p>
                    <a href="" class="btn">Explore Now  &#8594;</a>
                </div>
               
                <div class="col-2">

                </div>
            </div>
            

        </div>
    </div>
    
    <div class="small-conatiner">
        <div class="row row-2">
           <h2>All Products</h2>
           <select>
               <option>Default Shorting</option>
               <option>Short By Price</option>
               <option>Short By Popularity</option>
               <option>Short by Rating</option>
               <option>Short by Sale</option>
           </select>
        </div>
        <h2 class="title">Featured Products</h2>
        <div class="row">
            <div class="col-4">
                <img src="https://canary.contestimg.wish.com/api/webimage/5e5637c2c5a7b75508387dc2-large.jpg?cache_buster=2d66c3e0c28c3754c1d468413f3e3ff6">
                <h4>Designer T-Shirts</h4>
                <div class="rating">
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star-o" aria-hidden="true"></i>
                </div>
                <p>$70.00</p>
            </div>
            <div class="col-4">
                <img src="data:image/jpeg;base64,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">
                <h4>Designer T-Shirts</h4>
                <div class="rating">
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star-o" aria-hidden="true"></i>
                </div>
                <p>$90.00</p>
            </div>
            <div class="col-4">
                <img src="https://m.media-amazon.com/images/I/616NrT2vnqL._AC_UX385_.jpg">
                <h4>Designer T-Shirts</h4>
                <div class="rating">
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star-o" aria-hidden="true"></i>
                </div>
                <p>$80.00</p>
            </div>
            <div class="col-4">
                <img src="https://images-platform.99static.com//wgCzJuXXfoqe8nNKg--NdhU4oyw=/178x177:866x865/fit-in/500x500/projects-files/106/10661/1066168/9ead8f05-9230-4018-bc0d-2052d5634add.png">
                <h4>Designer T-Shirts</h4>
                <div class="rating">
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star-half-o" aria-hidden="true"></i>
                </div>
                <p>$100.00</p>
            </div>
        </div>
        <!-----featured products----->
    <div class="small-conatiner">
        <h2 class="title">Brands</h2>
        <div class="row">
            <div class="col-4">
                <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAASIAAACuCAMAAAClZfCTAAAAgVBMVEUAAAD////8/Pzc3Nw/Pz/S0tJ+fn4EBAT29vbx8fFNTU3Nzc2enp5lZWWvr68TExNxcXEcHBwiIiJERETCwsLi4uK7u7ulpaXGxsaGhobg4ODo6OiAgICNjY0rKyvX19czMzNaWlp2dnY6OjqXl5dVVVVJSUlgYGAvLy9tbW21tbVhYetPAAADuElEQVR4nO3b2XKiQBSAYRpUJO4b0RCjUTOOvv8DTgOSoNMICgJp/6+SiyzVdTx1egfDAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA+KUG8ns0MOwCmmosWkU0Uztz17Bn0wIa2s6FEFYBDdXNlxD9phAvuRvaicCwgJhqZiVM/5OtNp+jPM0MOmGGxKKowOqi0fQzdPqyuo172xl5pwyJryLDq4GWuLDa3NfQd4Y0G4tsoxn2soj/g9e6o6VO1I55dx3W1Lh9WUW+t55x4xJgFyXYmjwo0qo0PEWCTPlJpx83tTM5lVBQgHotjLzzbhbTvmlekt1VJnb2/qg4K9RMTJEQnXHmZnpB5XUfGGh1Rp1ovlcVUi9rM5ZswdFtrv+2SKwimbfXbG3IIhKzx4ZZHTmyLuUs1FGP2qZoDrK0IkvRybUwr7sPf/JaJIxJ3p/0Caoh/29fQqBVWyX0NjN9U9qX2+ASIqxcQoqkZdpKpy3amfrjL/V34a7eVvNd10ye/VNKRO7yduUEW4l+Yl5+upoQ86ttWMLRaz19ZpqeocDsyipyr+uaMdAQV7pXrI7kujB5cyqXjRpP+D0/Ac7RE/FUmUKZOLk/tVX9SS6rjqUHXp6BfxIie8nhbDprq7qfKVzlrPUi/6bbAdGZnsxRsBHbd8IO5fepF6NlqurIUayQxo7c7pYddZlsY/wefe71zgpK6OgPLEPVxlZuRy4vSdaO/O2h5KgrtZ5EB2mHhN1/J0hSNCYNTZ33r2kOygz5B6+LKI2TedA5tT0DSWEbn44qRf4YZc7c7nLXt8JC0/GgMauP5F1brKruuSzRhX+SpLwdict+LqmrcdcR6oVkWEI3nG5rbOiqxqQTjfdmt1lvum5z5jmO+V9JPdWSKIvB3r1YLjlVh1RDW+u8qz3zhJaof9bXmlWHU0vH+KRmanzemMPZndvTL4yUDvEUZbyvfTZWbFpjMFLaxFLkVR1MTTmxk26dLxlziN++basOpp7WsRQ964lamvnPaMSsrxYrozuf0tbfKylK5ZGiNJMoRRq+NlQM21icRuxl1aHUlf2949fspZhidcIntluavdBQqLegjNpcgyQbhG+QOD3qKIFtjKzg5JHLokR2uKGVlaTxk3z5bdom2/0UwTFt/vfXdfbpp0i7184LtfdT9LRPqmWyZxuS5itcPzKnJduGp/zMaVc4XKelmXIpm2YvtH3/vDAuVZTq1XyOd2NzaXAachXpAQAAAAAAAAAAAAAAAAAAAAAAAIDq/AMt6x0FHJgffAAAAABJRU5ErkJggg==">
                <h4>PUMA WEARS</h4>
                <div class="rating">
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star-o" aria-hidden="true"></i>
                </div>
                <p>$70.00</p>
            </div>
            <div class="col-4">
                <img src="https://i.pinimg.com/550x/a2/bc/bb/a2bcbb216b790eb34844962944a3a16e.jpg">
                <h4>AIR JORDANT WEARS </h4>
                <div class="rating">
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star-o" aria-hidden="true"></i>
                </div>
                <p>$90.00</p>
            </div>
            <div class="col-4">
                <img src="https://cdn.logojoy.com/wp-content/uploads/2018/05/30143359/2_big1.png">
                <h4>ADIDAS WEARS </h4>
                <div class="rating">
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star-o" aria-hidden="true"></i>
                </div>
                <p>$80.00</p>
            </div>
            <div class="col-4">
                <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAARMAAAC3CAMAAAAGjUrGAAAAflBMVEX19fUAAAD5+fn8/Pz6+vr+/v7q6up9fX3v7++3t7fOzs7Z2dnAwMCxsbHz8/N5eXmXl5eoqKjW1tbIyMg7OzuPj4+Dg4NoaGiqqqo0NDRiYmJXV1fl5eWfn59dXV0jIyNxcXFOTk4WFhZHR0cPDw8dHR0tLS2RkZFCQkKbm5vFyIMDAAAEtUlEQVR4nO3b22KiMBAGYJIQFUQRFLVKPbdu3/8FN0CxKAdBIYnt/93vMg6ZZJJQwwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABo3UB1AHdQKvuJPOjJfmQTlDF/FMp9JnfPTO4T66OMj63dZmTIHSh8TsZSH1gXNTm1JzOy8Lnk0uEBmWg4TChnw+WCEHLuyc6Iwb8I0W2GFQXTc/pbkZC3EWXyp9clIX0u+6kVRMEY9uRIIpupacqPgDni0UPpb6IEpdwMvcUhTgjpD+UPkSgIXzx7r8cwESuuKJi3JB9k+yV/GknC6EWvxFIwPm8DMfnYnuxJ6mgZSsZIFEpctoorh4pZNPRWh0tCyMpmyl4Td6MIXJWlExWMdSmY2DxUUzQx7sUxTFVFEK8w5302H2T7PlCYEYPaSRhqQhADZOityLWjY6qaRpKgBqc4joX80olaMsv9uEkI2Ulv4W/xdRLJUm4cIh/GNJjd5oOQQNHamxG19DGJDRuN9jDvm3w+yOdS2dr7w/S/oznJCkUMkNDaHQoSQtaOurU3g6bVLKWJFSvMoLBgIq6aFj6H79KIOt//RSuu/74uzgfZTnp6ZCTZ+SXeOz06ocwMLXdbkhAyG2kwjSTSZTgy6qySxQQiCuZfWT5UnQSU+KkcQpxO3pNYYahYYU7lCSHzofK1N8OcZkLroLOP9zDuZ0U+RAuvvhu5lg3Xajc0ajLDDo5V+YhOAqhmB8D8nI3Pa7GkC/cwOStbsyEiAg+vIgxaemPRjGr1S1eYC6UnAWX44irGdQv9SbLpr1hhUlvP0DAjlxOCi2f/P5PzoVe0h8kRLbxm08g3djv/PbMYV+xhclyt1t4s6tzGunmweJKWrGQPc+sU6NLCF2D5qvebBytasoo9TM5sOdZ1jAh0mo/4X8OBIlZcUTD3V5jUxlFwvdkA3xcEPamflLt7mBxFl3n1Ub8wbqtWUqo3/YU+VF3mNcD7xbGP7iYlupcaNSiYiEYnARXGZeHPjYoWX0wgA2dec4W52Ey5PicB5cxR6S/YOsW/QOSDZi9y69LrJKBC4QybEiOdXw11KiZU6r8vKv5NiQ+1l3mN9O78lo1nGzxl+FZQlcNSRz1O4euh5aWTecf71W632xyrjsiqyP8e7ynsgTJoKNDxJKAKe/Td1/TmjV9g7b0W3v9ZT1g7uh0o1pDfErdIl8u8hkyvq4Qczq82jaRY0E1GZsvXm0ZSzO0iI1pd5jXGO8hJ/1Va+BKt5+T0Qi18CVZyUPCgmXaXeQ9gkxYzsrJf4iTgnoqTgqa0vMx7BB22k5DPF2zhS9E2MrJ3zNefRn60sC/e+S90NlKHaT2XkEMQ/p6iuXgmI7Ply3cjRZ5YjTdTvS/zHld6l3GHvt8EPI89NKMo+ANfmZrveaJuRHXUHTMb3feKaYT90mkki9ZPysfkt7Tw95Tdo99ybf4Hhsg37tz/AG2n+Xc0raPGV9VNz2w+1fKLzY6x8WhfnA93FKr9002FTBZa/X3mG5u3dd+ze5SZfzQhMWpyZvSGvm3b/rA3MNhfWHVrod9UxwEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAkPMfHis0dBOPTiIAAAAASUVORK5CYII=">
                <h4>NIKE</h4>
                <div class="rating">
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star-half-o" aria-hidden="true"></i>
                </div>
                <p>$100.00</p>
            </div>
            <h2 class="tilte">Latest Products</h2>
            <div class="row">
                <div class="col-4">
                    <img src="data:image/jpeg;base64,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">
                    <h4>Blazzer</h4>
                    <div class="rating">
                        <i class="fa fa-star" aria-hidden="true"></i>
                        <i class="fa fa-star" aria-hidden="true"></i>
                        <i class="fa fa-star" aria-hidden="true"></i>
                        <i class="fa fa-star" aria-hidden="true"></i>
                        <i class="fa fa-star-o" aria-hidden="true"></i>
                    </div>
                    <p>$170.00</p>
                </div>
                <div class="col-4">
                    <img src="https://img2.exportersindia.com/product_images/bc-full/2018/12/6034254/mens-designer-lower-1545390296-4584693.jpeg">
                    <h4>Lower</h4>
                    <div class="rating">
                        <i class="fa fa-star" aria-hidden="true"></i>
                        <i class="fa fa-star" aria-hidden="true"></i>
                        <i class="fa fa-star" aria-hidden="true"></i>
                        <i class="fa fa-star" aria-hidden="true"></i>
                        <i class="fa fa-star-o" aria-hidden="true"></i>
                    </div>
                    <p>$50.00</p>
                </div>
                <div class="col-4">
                    <img src="https://i.pinimg.com/originals/b4/90/78/b490784213bba72d6869a007de213823.jpg">
                    <h4>Jacket</h4>
                    <div class="rating">
                        <i class="fa fa-star" aria-hidden="true"></i>
                        <i class="fa fa-star" aria-hidden="true"></i>
                        <i class="fa fa-star" aria-hidden="true"></i>
                        <i class="fa fa-star" aria-hidden="true"></i>
                        <i class="fa fa-star-o" aria-hidden="true"></i>
                    </div>
                    <p>$70.00</p>
                </div>
                <div class="col-4">
                    <img src="https://www.dhresource.com/0x0/f2/albu/g10/M00/4D/0F/rBVaVlzYI5mAbXHcAAFiWMrwIWw381.jpg/18ss-new-mens-luxury-designer-shoes-special.jpg">
                    <h4>Shoes</h4>
                    <div class="rating">
                        <i class="fa fa-star" aria-hidden="true"></i>
                        <i class="fa fa-star" aria-hidden="true"></i>
                        <i class="fa fa-star" aria-hidden="true"></i>
                        <i class="fa fa-star" aria-hidden="true"></i>
                        <i class="fa fa-star-half-o" aria-hidden="true"></i>
                    </div>
                    <p>$120.00</p>
                </div>
        </div>
        <div class="page-btn">
            <span>1</span>
            <span>2</span>
            <span>3</span>
            <span>4</span>
            <span>&#8594;</span>
        </div>

    </div>
            
    <!-----Footer----->
    <div class="footer">
        <div class="container">
            <div class="row">
                <div class="footer-col-1">
                    <h3>
                        Download Our App
                    </h3>
                    <p>
                        Download App for Android and IOS Mobile Phone.
                    </p>
                    <div class="app-logo">
                        <img src="https://images.samsung.com/is/image/samsung/assets/uk/support/lucidcx/wherecanifindtheplaystore.png?$ORIGIN_PNG$">
                        <img src="data:image/jpeg;base64,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">
                    
                    </div>
                </div>
                <div class="footer-col-2">
                    <img src="https://99designs-blog.imgix.net/blog/wp-content/uploads/2019/09/attachment_109861736-e1567623620590-1.png?auto=format&q=60&w=2000&h=862&fit=crop&crop=faces">

                    <p>Download App for Android and IOS mobile phone.</p>
                </div>
                <div class="footer-col-3">
                    <h3>
                        Useful Links
                    </h3>
                    <ul>
                        <li>Coupons</li>
                        <li>Blog Post</li>
                        <li>Return Policy</li>
                        <li>Join Affiliate</li>
                    </ul>
                </div>
                <div class="footer-col-4">
                    <h3>
                        Follow us
                    </h3>
                    <ul>
                        <li>Facebook</li>
                        <li>Twitter</li>
                        <li>Instagarm</li>
                        <li>You Tube</li>
                    </ul>
                </div>
            </div>
            <hr>
            <p class="Copyright">Copyright 2022 - Bharat Mart</p>
        </div>
    </div>
    <script>
        var MenuItems = document.getElementById("MenuItems");
        MenuItems.style.maxHeight = "0px";
        function menutoggle(){
            if(MenuItems.style.maxHeight == "0px"){
                MenuItems.style.maxHeight = "200px";
            }
            else{
                MenuItems.style.maxHeight = "0px";
            }
        }
    </script>   




</body>
</html>
                                                 //// MAIN CSS
                                                 
                                                 
                                                 *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;

}
body{
    font-family: 'Poppins', sans-serif;
}
.navbar{
    display: flex;
    align-items: centre;
    padding: 20px;
}
nav{
    flex: 1;
    text-align: right;
}
nav ul{
    display: inline-box;
    list-style-type: none;
}
nav ul li{
    display: inline box;
    margin-right: 20px;
}
a{
    text-decoration: none;
    color: #555;
}
p{
    color: #555;
}
.container{
    max-width: 1300px;
    margin: auto;
    padding-left: 25px;
    padding-right: 25px;
}
.row{
    display: flex;
    align-items: centre;
    flex-wrap: wrap;
    justify-content: space-around;
}
.col-2{
    flex-basis: 50%;
    min-width: 300px;
}
.col-2 img{
    max-width: 100%;
    padding: 50px 0;
}
.col-2 h1{
    font-size: 50px;
    line-height: 60px;
    margin: 25px 0
}
.btn{
    display: inline-block;
    background: #ff523b;
    color: #fff;
    padding: 8px 30px;
    margin: 30px 0;
    border-radius: 30px;
    transition: background 0.5s;
}
.btn:hover{
    background: #563434;
}
.header{
    background: radial-gradient(#fff,#ffd6d6);
}
.header .row{
    margin-top: 70px;
}
.cateogries{
    margin: 70px 0;
}
.col-3{
    flex-basis: 30%;
    min-width: 250px;
    margin-bottom: 30px;
}
.col-3 img{
    width: 100%;
}
.small-container{
    max-width: 1080px;
    margin: auto;
    padding-left: 25px;
    padding-right: 25px;
}
.col-4{
    flex-basis: 25%;
    padding: 10px;
    min-width:200px;
    margin-bottom: 50px;
    transition: transform 0.5s;
}
.col-4 img{
    width: 100%;
}
.title{
    text-align: centre;
    margin: 0 auto 80px;
    position: relative;
    line-height: 60px;
    color: #555;
}
.title::after{
    content: '';
    background: #ff523b;
    width: 80px;
    height: 5px;
    border-radius: 5px;
    position: absolute;
    bottom: 0;
    left: 50%;
    transform: translateX(-50);
}
h4{
    color: #555;
    font-weight: normal;
}
.col-4 p{
    font-size: 14px;
}
.rating .fa{
    color: #ff523b;
}
.col-4:hover{
    transform: translateY(-5px);
}
/*----Offer---*/
.offer{
    background: radial-gradient(#fff,#ffd6d6);
    margin-top: 80px;
    padding: 30px 0;
}
.col-2 .offer-img{
    padding: 50px;
}
small{
    color: #555;
}
.testimonial{
    padding-top: 100px;
}
.testimonial .col-3{
    text-align: centre;
    padding: 40px 20px;
    box-shadow: 0 0 20px 0px rgba(0,0,0,0.1);
    cursor: pointer;
    transition: transform 0.5;
}
.testimonial .col-3 img{
    width: 50px;
    margin-top: 20px;
    border-radius: 50%;
}
.testimonial .col-3:hover{
    transform: translateY(-10px);
}
.fa.fa-quote-left{
    font-size: 34px;
    color: #ff523b;
}
.col-3 p{
    font-size: 12px;
    margin: 12px  0;
    color: #777; 
}
.testimonial .col-3 h3{
    font-weight: 600;
    color: #555;
    font-size: 16px;  
}
/*------Brands----*/
.brands{
    margin: 100px auto;
}
.col-5{
    width: 160px;
}
.col-5 img{
    width: 100%;
    cursor: pointer;
    filter: grayscale(100%)
}
.col-5 img:hover{
    filter: grayscale(0%)
}
/*-----Footer-----*/
.footer{
    background: #000;
    color: #8a8a8a;
    font-size: 14px;
    padding: 60px 0 20px;
}
.footer p{
    color: #8a8a8a;
}
.footer h3{
    color: #fff;
    margin-bottom:20px;
}
.footer-col-1, .footer-col-2, .footer-col-3, .footer-col-4{
    min-width: 250px;
    margin-bottom: 20px;
}
.footer-col-1{
    flex-basis:30%
}
.footer-col-2{
    flex:1;
    text-align: centre;
}
.footer-col-2 img{
    width: 180px;
    margin-bottom: 20px;
}
.footer-col-3, .footer-col-4{
    flex-basis:12%;
    text-align: centre;
}
ul{
    list-style-type: none;
}
.app-logo{
    margin-top: 20px;
}
.app-logo img{
    width: 140px;
}
.footer hr{
    border: none;
    background: #b5b5b5;
    height: 1px;
    margin: 20px 0;
}
.copyright{
    text-align: centre;

}
.menu-icon{
    width: 28px;
    margin-left: 20px;
    display: none;
}
/*------media query for menu----*/
@media only screen and(max-width: 800px){

nav ul
{
    position: absolute;
    top: 70px;
    left: 0;
    background: #333;
    width: 100%;
    overflow: hidden;
    transition: max-height 0.5s;

}
nav ul li{
    display: block;
    margin-right: 50px;
    margin-top: 10px;
    margin-bottom: 10px;
}
nav ul li a{
    color: #fff;
}
.menu-icon{
    display: block;
    cursor: pointer;
}
}
/*----all Products page----*/

.row-2{
    justify-content: space-between;
    margin: 100px auto 50px;
}
select{
    border: 1px solid #ff523b;
    padding: 5px;
}
select:focus{
    outline: none;
}
.page-btn{
    margin: 0 auto 80px;
}
.page-btn span{
    display: inline-block;
    border: 1px solid #ff523b;
    margin-left: 10px;
    width: 40px;
    height: 40px;
    text-align: center;
    line-height: 40px;
    cursor:pointer;
}
.page-btn span:hover{
    background: #ff523b;
    color: #fff;
    
}
/*------media query for less than 600 screeen size----*/
@media only screen and(max-width: 600px){
    .row{
        text-align: center;
    }
    .col2, .col3 , .col-4{
        flex-basis: 100%;
    }


}

                                                 
                                                 //// MAIN CSS
                                                 
                                                 
                                                 *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;

}
body{
    font-family: 'Poppins', sans-serif;
}
.navbar{
    display: flex;
    align-items: centre;
    padding: 20px;
}
nav{
    flex: 1;
    text-align: right;
}
nav ul{
    display: inline-box;
    list-style-type: none;
}
nav ul li{
    display: inline box;
    margin-right: 20px;
}
a{
    text-decoration: none;
    color: #555;
}
p{
    color: #555;
}
.container{
    max-width: 1300px;
    margin: auto;
    padding-left: 25px;
    padding-right: 25px;
}
.row{
    display: flex;
    align-items: centre;
    flex-wrap: wrap;
    justify-content: space-around;
}
.col-2{
    flex-basis: 50%;
    min-width: 300px;
}
.col-2 img{
    max-width: 100%;
    padding: 50px 0;
}
.col-2 h1{
    font-size: 50px;
    line-height: 60px;
    margin: 25px 0
}
.btn{
    display: inline-block;
    background: #ff523b;
    color: #fff;
    padding: 8px 30px;
    margin: 30px 0;
    border-radius: 30px;
    transition: background 0.5s;
}
.btn:hover{
    background: #563434;
}
.header{
    background: radial-gradient(#fff,#ffd6d6);
}
.header .row{
    margin-top: 70px;
}
.cateogries{
    margin: 70px 0;
}
.col-3{
    flex-basis: 30%;
    min-width: 250px;
    margin-bottom: 30px;
}
.col-3 img{
    width: 100%;
}
.small-container{
    max-width: 1080px;
    margin: auto;
    padding-left: 25px;
    padding-right: 25px;
}
.col-4{
    flex-basis: 25%;
    padding: 10px;
    min-width:200px;
    margin-bottom: 50px;
    transition: transform 0.5s;
}
.col-4 img{
    width: 100%;
}
.title{
    text-align: centre;
    margin: 0 auto 80px;
    position: relative;
    line-height: 60px;
    color: #555;
}
.title::after{
    content: '';
    background: #ff523b;
    width: 80px;
    height: 5px;
    border-radius: 5px;
    position: absolute;
    bottom: 0;
    left: 50%;
    transform: translateX(-50);
}
h4{
    color: #555;
    font-weight: normal;
}
.col-4 p{
    font-size: 14px;
}
.rating .fa{
    color: #ff523b;
}
.col-4:hover{
    transform: translateY(-5px);
}
/*----Offer---*/
.offer{
    background: radial-gradient(#fff,#ffd6d6);
    margin-top: 80px;
    padding: 30px 0;
}
.col-2 .offer-img{
    padding: 50px;
}
small{
    color: #555;
}
.testimonial{
    padding-top: 100px;
}
.testimonial .col-3{
    text-align: centre;
    padding: 40px 20px;
    box-shadow: 0 0 20px 0px rgba(0,0,0,0.1);
    cursor: pointer;
    transition: transform 0.5;
}
.testimonial .col-3 img{
    width: 50px;
    margin-top: 20px;
    border-radius: 50%;
}
.testimonial .col-3:hover{
    transform: translateY(-10px);
}
.fa.fa-quote-left{
    font-size: 34px;
    color: #ff523b;
}
.col-3 p{
    font-size: 12px;
    margin: 12px  0;
    color: #777; 
}
.testimonial .col-3 h3{
    font-weight: 600;
    color: #555;
    font-size: 16px;  
}
/*------Brands----*/
.brands{
    margin: 100px auto;
}
.col-5{
    width: 160px;
}
.col-5 img{
    width: 100%;
    cursor: pointer;
    filter: grayscale(100%)
}
.col-5 img:hover{
    filter: grayscale(0%)
}
/*-----Footer-----*/
.footer{
    background: #000;
    color: #8a8a8a;
    font-size: 14px;
    padding: 60px 0 20px;
}
.footer p{
    color: #8a8a8a;
}
.footer h3{
    color: #fff;
    margin-bottom:20px;
}
.footer-col-1, .footer-col-2, .footer-col-3, .footer-col-4{
    min-width: 250px;
    margin-bottom: 20px;
}
.footer-col-1{
    flex-basis:30%
}
.footer-col-2{
    flex:1;
    text-align: centre;
}
.footer-col-2 img{
    width: 180px;
    margin-bottom: 20px;
}
.footer-col-3, .footer-col-4{
    flex-basis:12%;
    text-align: centre;
}
ul{
    list-style-type: none;
}
.app-logo{
    margin-top: 20px;
}
.app-logo img{
    width: 140px;
}
.footer hr{
    border: none;
    background: #b5b5b5;
    height: 1px;
    margin: 20px 0;
}
.copyright{
    text-align: centre;

}
.menu-icon{
    width: 28px;
    margin-left: 20px;
    display: none;
}
/*------media query for menu----*/
@media only screen and(max-width: 800px){

nav ul
{
    position: absolute;
    top: 70px;
    left: 0;
    background: #333;
    width: 100%;
    overflow: hidden;
    transition: max-height 0.5s;

}
nav ul li{
    display: block;
    margin-right: 50px;
    margin-top: 10px;
    margin-bottom: 10px;
}
nav ul li a{
    color: #fff;
}
.menu-icon{
    display: block;
    cursor: pointer;
}
}
/*----all Products page----*/

.row-2{
    justify-content: space-between;
    margin: 100px auto 50px;
}
select{
    border: 1px solid #ff523b;
    padding: 5px;
}
select:focus{
    outline: none;
}
.page-btn{
    margin: 0 auto 80px;
}
.page-btn span{
    display: inline-block;
    border: 1px solid #ff523b;
    margin-left: 10px;
    width: 40px;
    height: 40px;
    text-align: center;
    line-height: 40px;
    cursor:pointer;
}
.page-btn span:hover{
    background: #ff523b;
    color: #fff;
    
}
/*------media query for less than 600 screeen size----*/
@media only screen and(max-width: 600px){
    .row{
        text-align: center;
    }
    .col2, .col3 , .col-4{
        flex-basis: 100%;
    }


}

                                                 
