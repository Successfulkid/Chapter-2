<!DOCTYPE html>
<html lang="en">
    <head>
      <meta charset = "utf-8">
      <title>Dandre Jackson</title>
    <style>
        body{
          background-color: lightgrey;
          }
        nav ul{
          list-style-type: none;
          padding: 0 .5em;
          margin: auto;
          }
        nav ul li{
          padding: 0;
          margin: 3px 0 0;
          border: 1px solid #111111;
          background-color: #f0f0f0;
          padding: 10px 1em;
          text-align: center;
          }
        nav ul li a{
          text-decoration: none;
          font-size: 1.2em;
          display: block;
          }
        body {margin: 0;}
        div, footer, header, aside {position: relative; margin: .5em;}
        section, aside, footer, header{ border: 1px solid #aaa; padding: 1.25em; border-radius: 5px;}
        section {
          margin-bottom: .5em
          }
        img{
          float: left;
          margin-right: 20px;
          width: 100px;
          }
        header{
          text-align: center;
          }
        header h2{
          padding-top: 0;
          }
        footer p a img{
          float: none;
          vertical-align: middle;
          }
        footer{
          text-align: center;
          background-color: #c0c0c0;
          }
        aside h4{
          font-size: 1.5em;
          }
        /* for wider screen*/
        @media only screen and (min-width: 45em){
          nav ul{
            text-align: canter;
            }
          nav ul li{
            display: inline-block;
            text-align: center;
            width: 20%;
            }
          div{
            clear: left;
            min-height: 430px;
            }
          body{position: relative; }
          section {
            margin-right: 22em; min-height: 135px;
            }
          main{
            min-height: 28em;
            }
          aside#amazon{
            position: absolute; top: 14.5em; right: 0; width: 18.75em;
            }
          aside#bn{
            position: absolute; top: 26em; right: 0; width: 18.75em;
            }
          textarea{
            width: 50%;
            }
          }
      </style>
    </head>
    <body>
      <header>
        <h1>Dandre Jackson</h1>
        <h2>Web programming is FUN</h2>
        <nav>
          <ul>
            <li><a href="README.md">Home</a></li>
            <li><a href="edu.html">Eduation</a></li>
            <li><a href="work.html">Work</a></li>
          </ul>
        </nav>
      </header>
      <main>
        <section id = "aboutMe">
      <h3>About Me</h3>
      <img alt = "Dandre's Photo" src="d.jpeg">
      <p>My name is Dandre Jackson, and I'm 19 years old. I have a passion for Parkour and motorcycles, finding joy in the adrenaline and freedom they bring. Alongside these hobbies, I also find fulfillment in coding. Exploring the intricacies of programming and creating digital solutions fuels my curiosity and creativity.</p>
    </section>
    <section id = "contactMe">
    <h3>Contact Me</h3>
    <form action="#">
<label for="name">Enter your name: </label><input type = "text" id="name">
<br>
<label for="purpose">Selet a topic: </label>
    <select id="purpose">
        <option>make friends</option>
        <option>intend to hire</option>
        <option>like your page</option>
        <option>someone you know</option>
    </select>
<br>
<label for="message">Type your Message: </label>
<br>
<textarea id = "message"></textarea>
<input type="submit" id = "submit" value="Send">
<input type="reset" value="clear">
</form>
</section>
</main>
</body>
</html>
