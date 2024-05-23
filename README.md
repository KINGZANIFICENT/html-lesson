# html-lesson

<h1>Anna Dowlin</h1> h1 for header in html closing line always has a /
<p>Hi! I'm Anna, a NYC-based marketer. Say hello!</p> p is for paragraph
<input type="email" placeholder="Your email"> typebox
<input type="submit"> clicker






<style>
body {
  text-align: center;
  }
</style>
<body> used to wrap all off the contents together --> 
<h1>Anna Dowlin</h1>
<p>Hi! I'm Anna, a NYC-based marketer. Say hello!</p>
<input type="email" placeholder="Your email">
<input type="submit">
</body> 








<!DOCTYPE html>
<head>
  <title>Anna Dowlin</title>
  <style>
   body {
       text-align: center;
        background: black; /* color and font customization */
       color: white;
       font-family: helvetica;
     }
  </style>
</head>
<body>
    <h1>Anna Dowlin</h1>
    <p>Hi! I'm Anna, a NYC-based marketer. Say hello!</p>
    <input type="email" placeholder="Your email">
    <input type="submit">
</body>




FINISHED 

<!DOCTYPE html>
<head>
  <title>Angel Vargas</title>
  <style>
    body {
      text-align: center;
      background: url("https://blog.solostove.com/wp-content/uploads/2020/07/1599px-Ekstedt_AV4A6627_39980571391-1.jpg");
      background-size: cover;
      background-position: centr;
      color: black;
      font-family: system-ui;
    }
    p {
      font-size: 50px;
    }
    input {
      border: 0;
      padding: 10px;
      font-size: 18px;
    }
    input[type="submit"] {
      background: Green;
      color: white;
    }
  </style>
</head>
<body>
  <img src=https://i.imgur.com/w4ZWhbr.jpeg">
  <p>Hi! I'm Chef Angel Luis Vargas, Private Chef and Caterer for Hire! </p>
  <p> Leave me your email and I will contact you as soon as possible! </p>
  <input type="email" placeholder="Your email">
  <input type="submit">
</body> -->



--------------------------------------------------------------
 blog starts here -->


 links 
<!DOCTYPE html>
<head>

</head>

<body>
 <header>
    <img src="/assets/jeff.png">
    <h1>Jeff's Blog</h1>
    <ul>
        <li><a href="#">About Me</a></li>
        <li><a href="#">Best Poems</a></li>
        <li><a href="#">Worst Poems</a></li>
        </ul>
 </header>
</body>




<!DOCTYPE html>
<head>
  <link href="/normalize.css" rel="stylesheet">
  <style>
   header {
      text-align: center;
      background: url("/assets/jeff-bg.png");
      background-size: cover;
      color: white;
   }
   a { 
     color: white;
   }
   h1 { 
     font-size: 70px;
   }
   img {
     margin: 40px 0px 0px 0px;  auto gets url this is for size inside
     border: 7px solid white; border for images 
     border-radius: 20px;  smoothed out edges 
   }
   ul {
     padding: 10px;
     background: black; added color to nav bar
   }
   li {
     display: inline;
     padding: 0px 10px 0px 10px;
   }
   </style>
</head>
<body>
  <header>
    <img src="/assets/jeff.png">
    <h1>Jeff's Blog</h1>
    <ul>
      <li><a href="#">About Me</a></li>
      <li><a href="#">Best Poems</a></li>
      <li><a href="#">Worst Poems</a></li>
    </ul>
  </header>
</body>



<!-- finished -->



<!DOCTYPE html>
<head>
  <link href="/normalize.css" rel="stylesheet">
  <style>
    header {
      text-align: center;
      background: url('http://dash.ga.co/assets/jeff-bg.png');
      background-size: cover;
      color: white;
    }
    a {
      color: white;
    }
    h1 {
      font-size: 70px;
    }
    img {
      margin: 40px 0px 0px 0px;
      border: 7px solid white;
      border-radius: 20px;
    }
    ul {
      padding: 10px;
      background: rgba(0, 0, 0, 0.5);
    }
    li {
      display: inline;
      padding: 0px 10px 0px 10px;
    }
    article {
      max-width:500px;
      padding: 20px;
      margin: 0 auto;
    }
    @media (max-width: 500px) {
      body {
        background: red;
      }
      h1{
        font-size: 36px;
      }
      li {
        display: block;
        padding: 5px;
      }
    }
  </style>
</head>
<body>
  <header>
    <img src="/assets/jeff.png">
    <h1>Jeff's Blog</h1>
    <ul>
      <li><a href="#">About Me</a></li>                                  added like button and script on bottom to give output on button clicking
      <<li><a href="#">Best Poems</a></li>
      <li><a href="#">Worst Poems</a></li>
    </ul>
  </header>
  <article>
  <h2>VHS umami pop-up trust fund</h2>
  <p>Marfa church-key kitsch bicycle rights, 8-bit mixtape cardigan gentrify Echo Park. Street art swag brunch, next level roof party Schlitz hella organic keffiyeh selfies. You probably haven't heard of them polaroid hashtag +1, meggings biodiesel Portland High Life cray tumblr retro.</p>
  <button>Like</button>
  </article>
  <article>
  <h2>Sartorial synth Echo Park, roof party</h2>
  <p>chambray you probably haven't heard of them pour-over viral selvage umami skateboard VHS post-ironic selfies. Wes Anderson gentrify fanny pack twee, bicycle rights bitters blog keffiyeh plaid flannel. Tonx irony cliche sustainable mlkshk bitters. Four loko leggings chambray Vice.</p>
  <button>Like</button>
  </article>
  <article>
  <h2>Forage food truck keytar master cleanse</h2>
  <p>ethical thundercats sustainable locavore quinoa Neutra. Aesthetic tacky sweater single-origin coffee, bicycle rights organic lo-fi street art american apparel ennui four loko ethnic Brooklyn small batch. Forage YOLO polaroid</p>
  <button>Like</button>
  </article>
  <script>
  alert("Javascript works!")
  $("button").on("click", function() {
    alert("clicked!")
  });
  </script>
</body> 







<!-- resturant site starts here -->

<!DOCTYPE html>

<head>

<style>
body {
  font-family: helvetica, sans-serif;                                added the non_semantic div tag its used as a container to group any type of content to be styled by a sinlge bit of css
}
div {
  height: 200px;
}
</style>
</head>
<body>
<h1>esha's restaurant</h1>
<div>
<h2>welsh onion soko $14</h2>
<p>Mustard sierra leone bologi kale chard beet greens black-eyed pea sorrel amaranth garlic tigernut spring onion summer purslane asparagus lentil. </p>
</div>
<div>
<h2>pastrami boudin tongue $22</h2>
<p>Tri-tip capicola kielbasa salami brisket chicken rump strip steak drumstick. Meatloaf chuck boudin ribeye pork jowl. Andouille bacon jowl meatloaf pork loin prosciutto bresaola.</p>
</div>
<div>
<h2>fruitcake marzipan pudding dragee $8</h2>
<p>Lollipop tart cotton candy jelly-o carrot cake apple pie cupcake. Jelly-o bear claw ice cream candy canes.</p>
</div>
</body>




<!DOCTYPE html>

<head>

<style>
body {
  font-family: helvetica, sans-serif;
}
div {
  height: 200px;
  background: url("/assets/firstcourse.jpg");                  added background
  background-size: cover;                                      added background size 
  background-position: center;
  margin:0 auto;                                               centers elements but not text
}
</style>
</head>
<body>
<h1>esha's restaurant</h1>
<div>
<h2>welsh onion soko $14</h2>
<p>Mustard sierra leone bologi kale chard beet greens black-eyed pea sorrel amaranth garlic tigernut spring onion summer purslane asparagus lentil. </p>
</div>
<div>
<h2>pastrami boudin tongue $22</h2>
<p>Tri-tip capicola kielbasa salami brisket chicken rump strip steak drumstick. Meatloaf chuck boudin ribeye pork jowl. Andouille bacon jowl meatloaf pork loin prosciutto bresaola.</p>
</div>
<div>
<h2>fruitcake marzipan pudding dragee $8</h2>
<p>Lollipop tart cotton candy jelly-o carrot cake apple pie cupcake. Jelly-o bear claw ice cream candy canes.</p>
</div>
</body>




<!DOCTYPE html>

<head>

<style>
body {
  font-family: helvetica, sans-serif;
  max-width: 600px;
}
div {
  height: 200px;
  background: url("/assets/firstcourse.jpg");
  background-size: cover;
  background-position: center;
  margin:0 auto;
}
.first { 
    background: url("/assets/firstcourse.jpg")
}     
.second {                                                added classes to style to change each picture
    background: url("/assets/secondcourse.jpg")
}
.dessert {
    background: url("/assets/dessertcourse.jpg")
}
</style>
</head>
<body>
<h1>esha's restaurant</h1>
<div class="first">                                added class to change specific parts of the site 
<div>
<h2>welsh onion soko $14</h2>
<p>Mustard sierra leone bologi kale chard beet greens black-eyed pea sorrel amaranth garlic tigernut spring onion summer purslane asparagus lentil. </p>
</div>
<div class="second">
<div>
<h2>pastrami boudin tongue $22</h2>
<p>Tri-tip capicola kielbasa salami brisket chicken rump strip steak drumstick. Meatloaf chuck boudin ribeye pork jowl. Andouille bacon jowl meatloaf pork loin prosciutto bresaola.</p>
</div>
<div class="dessert">
<div>
<h2>fruitcake marzipan pudding dragee $8</h2>
<p>Lollipop tart cotton candy jelly-o carrot cake apple pie cupcake. Jelly-o bear claw ice cream candy canes.</p>
</div>
</body>




<!DOCTYPE html>

<head>

<style>
body {
  font-family: helvetica, sans-serif;
  max-width: 600px;
}
div {
  height: 200px;                                deleted background url since we have class calling specifc pics
  background-size: cover;
  background-position: center;
  margin:0 auto;
}
.first { 
    background: url("/assets/firstcourse.jpg")
}     
.second {                                                added classes to style to change each picture
    background: url("/assets/secondcourse.jpg")
}
.dessert {
    background: url("/assets/dessertcourse.jpg")
}
</style>
</head>
<body>
<h1>esha's restaurant</h1>
<div class="first">                                added class to change specific parts of the site 
<div>
<h2>welsh onion soko $14</h2>
<p>Mustard sierra leone bologi kale chard beet greens black-eyed pea sorrel amaranth garlic tigernut spring onion summer purslane asparagus lentil. </p>
</div>
<div class="second">
<div>
<h2>pastrami boudin tongue $22</h2>
<p>Tri-tip capicola kielbasa salami brisket chicken rump strip steak drumstick. Meatloaf chuck boudin ribeye pork jowl. Andouille bacon jowl meatloaf pork loin prosciutto bresaola.</p>
</div>
<div class="dessert">
<div>
<h2>fruitcake marzipan pudding dragee $8</h2>
<p>Lollipop tart cotton candy jelly-o carrot cake apple pie cupcake. Jelly-o bear claw ice cream candy canes.</p>
</div>
</body>




<!DOCTYPE html>

<head>

<style>
body {
  font-family: helvetica, sans-serif;
  max-width: 600px;
}
div {
  height: 200px;
  background-size: cover;
  background-position: center;
  margin:0 auto;
}
.first { 
    background: url("/assets/firstcourse.jpg");
}     
.second {                                               
    background: url("/assets/secondcourse.jpg");
}
.dessert {
    background: url("/assets/dessertcourse.jpg");
}
p {
  color: rgba(255, 255, 255, 1);
  background: rgba(0, 0, 0, 1);
  padding: 10px;
  text-align: justify;                            added padding for spacing aligned text and adjusted height 
  line-height: 28px;
}
</style>
</head>
<body>
<h1>esha's restaurant</h1>
<div class="first">
<div>
<h2>welsh onion soko $14</h2>
<p>Mustard sierra leone bologi kale chard beet greens black-eyed pea sorrel amaranth garlic tigernut spring onion summer purslane asparagus lentil. </p>
</div>
<div class="second">
<div>
<h2>pastrami boudin tongue $22</h2>
<p>Tri-tip capicola kielbasa salami brisket chicken rump strip steak drumstick. Meatloaf chuck boudin ribeye pork jowl. Andouille bacon jowl meatloaf pork loin prosciutto bresaola.</p>
</div>
<div class="dessert">
<div>
<h2>fruitcake marzipan pudding dragee $8</h2>
<p>Lollipop tart cotton candy jelly-o carrot cake apple pie cupcake. Jelly-o bear claw ice cream candy canes.</p>
</div>
</body>
 



  <!DOCTYPE html>

<head>

<style>
body {
  font-family: helvetica, sans-serif;
  max-width: 600px;
}
div {
  height: 200px;
  background-size: cover;
  background-position: center;
  margin:0 auto;
  position: relative;.
}
.first { 
    background: url("/assets/firstcourse.jpg");
}     
.second {                                               
    background: url("/assets/secondcourse.jpg");
}
.dessert {
    background: url("/assets/dessertcourse.jpg");
}
p {
  color: rgba(255, 255, 255, 1);
  background: rgba(0, 0, 0, 1);
  padding: 10px;
  text-align: justify;
  line-height: 28px;
  position: absolute;                                 fixed position of the paragraphs and moved them to the bottom 
  bottom: 0;        
  margin: 0;
}
</style>
</head>
<body>
<h1>esha's restaurant</h1>
<div class="first">
<div>
<h2>welsh onion soko $14</h2>
<p>Mustard sierra leone bologi kale chard beet greens black-eyed pea sorrel amaranth garlic tigernut spring onion summer purslane asparagus lentil. </p>
</div>
<div class="second">
<div>
<h2>pastrami boudin tongue $22</h2>
<p>Tri-tip capicola kielbasa salami brisket chicken rump strip steak drumstick. Meatloaf chuck boudin ribeye pork jowl. Andouille bacon jowl meatloaf pork loin prosciutto bresaola.</p>
</div>
<div class="dessert">
<div>
<h2>fruitcake marzipan pudding dragee $8</h2>
<p>Lollipop tart cotton candy jelly-o carrot cake apple pie cupcake. Jelly-o bear claw ice cream candy canes.</p>
</div>
</body>





<!DOCTYPE html>

<head>

<style>
body {
  font-family: helvetica, sans-serif;
  max-width: 600px;
}
div {
  height: 200px;
  background-size: cover;
  background-position: center;
  margin:0 auto;
  position: relative;
  margin: 40px 0px 0px 0px;
  border-radius: 12px;
}
.first { 
    background: url("/assets/firstcourse.jpg");
}     
.second {                                               
    background: url("/assets/secondcourse.jpg");
}
.dessert {
    background: url("/assets/dessertcourse.jpg");
}
p {
  color: rgba(255, 255, 255, 1);
  background: rgba(0, 0, 0, 1);
  padding: 10px;
  text-align: justify;
  line-height: 28px;
  position: absolute;
  bottom: 0;
  margin: 0;
}                                                       style formatted add breakpoints its <br /> mad text smaller with <small>
</style>
</head>
<body>
<h1>esha's restaurant</h1>
<div class="first">
<div>
<p>
  welsh onion soko $14
  <br />
  <small>
    Mustard sierra leone bologi kale chard beet greens black-eyed pea sorrel amaranth garlic tigernut spring onion summer purslane asparagus lentil.
  </small>
</p>
</div>
<div class="second">
<div>
<p>
  pastrami boudin tongue $22
  <br />
  <small>
    Tri-tip capicola kielbasa salami brisket chicken rump strip steak drumstick. Meatloaf chuck boudin ribeye pork jowl. Andouille bacon jowl meatloaf pork loin prosciutto bresaola.
  </small>
</p>
</div>
<div class="dessert">
<div>
<p>
  fruitcake marzipan pudding dragee $8
  <br />
  <small>
    Lollipop tart cotton candy jelly-o carrot cake apple pie cupcake. Jelly-o bear claw ice cream candy canes.
    </small>
</p>
</div>
</body>

<!DOCTYPE html>

<head>

<style>
body {
  font-family: helvetica, sans-serif;
  margin: 0 auto;
  max-width: 600px;
}
div {
  height: 200px;                                                     used float because we neede to move the prices to the right yey they were in inline 
  background-size: cover;
  position: relative;
  margin: 40px 0 0 0;
  border-radius: 12px;
}

p {
  color: rgba(255,255,255,1);
  background: rgba(0,0,0,1);
  padding: 10px;
  line-height: 28px;
  text-align: justify;
  position: absolute;
  bottom: 0;
  margin: 0;
}
.price {
  float: right;
}
.first{
  background-image: url("http://dash.ga.co/assets/firstcourse.jpg");
}
.second{
  background-image: url("http://dash.ga.co/assets/secondcourse.jpg");
}
.dessert{
  background-image: url("http://dash.ga.co/assets/dessertcourse.jpg");
}
</style>

</head>

<body>
<h1>esha's restaurant</h1>
<div class="first">
  <p>
  welsh onion soko
  <span class="price">$14</span>
  <br />
  <small>
    Mustard sierra leone bologi kale chard beet greens black-eyed pea sorrel amaranth garlic tigernut spring onion summer purslane asparagus lentil. </small></p>
</div>
<div class="second">
  <p>
pastrami boudin tongue
<span class="price">$22</span>
  <br />
  <small>
    Tri-tip capicola kielbasa salami brisket chicken rump strip steak drumstick. Meatloaf chuck boudin ribeye pork jowl. Andouille bacon jowl meatloaf pork loin prosciutto bresaola.</small></p>
</div>
<div class="dessert">
  <p>
    fruitcake marzipan pudding dragee
  <span class="price">$8</span>
  <br />
  <small>
    Lollipop tart cotton candy jelly-o carrot cake apple pie cupcake. Jelly-o bear claw ice cream candy canes.</small></p>
</div>
</body>
