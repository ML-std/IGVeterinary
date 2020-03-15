<!DOCTYPE html>
<html lang="en">
<head>
    <title>Main Page</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="shortcut icon" href="favicon.ico" />
</head>
<body>
<header>

    <div class="tab">
        <button class="tablinks" ><em> Main Page</em></button>
        <a href="blog.html"> <button class="tablinks" > Blog </button></a>
        <a href="services.html" ><button class="tablinks">Services</button></a>
        <a href="team.html"  > <button class="tablinks"> Team</button></a>
        <a href="gallery.html"  ><button class="tablinks" onclick="">Gallery</button></a>
        <a href="contactme.html" > <button class="tablinks"> Contact Us</button></a>
        <a href="registration.html"><button class="tablinks"> Register</button></a>
    </div>
      </header>
<nav>


    <form action="http://www.google.com/search" method="get">
        <label>Search On Google :</label>
        <input type="hidden" name="q"  value="">
        <label>
            <input type="text" name="q" placeholder="Search" alt="search">
        </label>
         <input  type="submit" value="Search">
    </form>
</nav>
<hr>
<aside>
    <img  class = "index" src="veterinary.png" alt="Veterinary">
    <img class =" index" src="injuredGood.png" alt = "IG Logo">
    <img  class = "index" src="vet2.png" alt="Veterinary">
    <section class="right">
        <form>
        <div class="center">
            <h4>IG Veterinary Clinic</h4>
            <h5>Please Login</h5>
            <label>
                <input name="username" placeholder="UserName">
            </label>
            <label>
                <input name="password" type="password" maxlength="8" placeholder="password"/>
            </label>
            <hr class="another">
            <a href="index.html"> <input type="submit" value="Login"></a>
            <a href="registration.html"><button>Register!</button></a>
        </div></form>
    </section>
</aside>
<article>
    <p class="center">Should you need any information,please <a href="contactme.html">contact Us!</a></p>
</article>

<footer>
    &copy; 2020 all rights reserved IG Company
</footer>
</body>
</html>
