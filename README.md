<!DOCTYPE html>
<html lang="en">
<head>
<title>CSS Template</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Arial, Helvetica, sans-serif;
}

/* Style the header */
header {
  background-color: lightpink;
  padding: 10px;
  text-align: center;
  font-size: 35px;
  color: white;
}

/* Container for flexboxes */
section {
  display: -webkit-flex;
  display: flex;
}

/* Style the navigation menu */
nav {
  -webkit-flex: 1;
  -ms-flex: 1;
  flex: 1;
  background: lightcoral;
  padding: 20px;
}

/* Style the list inside the menu */
nav ul {
  list-style-type: none;
  padding: 0;
}

/* Style the content */
article {
  -webkit-flex: 3;
  -ms-flex: 3;
  flex: 3;
  background-color: ivory;
  padding: 10px;
}

/* Style the footer */
footer {
  background-color: darksalmon;
  padding: 10px;
  text-align: center;
  color: white;
}

/* Responsive layout - makes the menu and the content (inside the section) sit on top of each other instead of next to each other */
@media (max-width: 600px) {
  section {
    -webkit-flex-direction: column;
    flex-direction: column;
  }
}
</style>
</head>
<body>


<header>
  <h2> <i>6 girls on a stage </h2> </i>
</header>

<section>
  <nav>
    <ul>
      <li><a href="#">Story #1</a></li>
      <li><a href="#">Story #2</a></li>
      <li><a href="#">Story #3</a></li>
    </ul>
  </nav>
  
  <article>
    <h1>Hi everyone!</h1>
    <p>We're Isabella and..</p>
    <p>We'll be delighted to take you on this journey with us..</p>
  </article>
</section>

<footer>
  <p>Scroll down to read the articles and reports!</p>
</footer>


2


</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
<title>CSS Template</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Arial, Helvetica, sans-serif;
}


/* Container for flexboxes */
section {
  display: -webkit-flex;
  display: flex;
}

/* Style the navigation menu */
nav {
  -webkit-flex: 1;
  -ms-flex: 1;
  flex: 1;
  background: lightcoral;
  padding: 20px;
}

/* Style the list inside the menu */
nav ul {
  list-style-type: none;
  padding: 0;
}

/* Style the content */
article {
  -webkit-flex: 3;
  -ms-flex: 3;
  flex: 3;
  background-color: ivory;
  padding: 10px;
}

/* Style the footer */
footer {
  background-color: darksalmon;
  padding: 10px;
  text-align: center;
  color: white;
}

/* Responsive layout - makes the menu and the content (inside the section) sit on top of each other instead of next to each other */
@media (max-width: 600px) {
  section {
    -webkit-flex-direction: column;
    flex-direction: column;
  }
}
</style>
</head>
<body>


<section>
  <nav>
    <ul>
      <li><a href="#">Story #1</a></li>
      
    </ul>
  </nav>
  
  <article>
    <h1 style:"font-size:30%; color:"black"> <i>Theatre in the UK and classical music: a love story"</h1> </i>
   <small> <i> A story by Isabella Porrovecchio and Eleonora Pellegrini </i></small>
    <p>article</p>
    <p><img style="image-align:center;" src="https://www.historyhit.com/app/uploads/fly-images/5158910/ROH-1-788x537.jpg?x50601" alt="google.com" width="
320" height="250"> </p>
     
    
     <h4> <i> About our methodological research </i> <h4>
    <p> <small> article </small></p>
    
  </article>
</section>

<footer>
  <p>Scroll down to read the articles and reports!</p>
</footer>





</body>
</html>


3

<!DOCTYPE html>
<html lang="en">
<head>
<title>CSS Template</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Arial, Helvetica, sans-serif;
}


/* Container for flexboxes */
section {
  display: -webkit-flex;
  display: flex;
}

/* Style the navigation menu */
nav {
  -webkit-flex: 1;
  -ms-flex: 1;
  flex: 1;
  background: lightcoral;
  padding: 20px;
}

/* Style the list inside the menu */
nav ul {
  list-style-type: none;
  padding: 0;
}

/* Style the content */
article {
  -webkit-flex: 3;
  -ms-flex: 3;
  flex: 3;
  background-color: ivory;
  padding: 10px;
}

/* Style the footer */
footer {
  background-color: darksalmon;
  padding: 10px;
  text-align: center;
  color: white;
}

/* Responsive layout - makes the menu and the content (inside the section) sit on top of each other instead of next to each other */
@media (max-width: 600px) {
  section {
    -webkit-flex-direction: column;
    flex-direction: column;
  }
}
</style>
</head>
<body>



<section>
  <nav>
    <ul>
      <li><a href="#">Story #2</a></li>
    </ul>
  </nav>
  
  <article>
    <h1> <i>Titolo Agnese e Giulia</h1> </i>
   <small> <i> A story by Agnese Musacchio and Giulia Montesanto </i></small>
    <p>article</p>
    <p><img src="https://cdn.shopify.com/s/files/1/0130/8714/6043/articles/image1_1_580x.jpg?v=1621417630" alt="google.com" width="
400" height="309"></p>
     
    
     <h4> <i> About our methodological research </i> <h4>
    <p> <small> article </small></p>
    
  </article>
</section>

<footer>
  <p>Scroll down to read the articles and reports!</p>
</footer>






</body>
</html>

