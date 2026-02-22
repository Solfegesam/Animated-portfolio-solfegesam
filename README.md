<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Portfolio</title>

<!-- INTERNAL CSS -->
    <style>
      body {
        font-family: Arial, sans-serif;
        margin: 20px;
        background-color: #f0f0f0;
      }

      nav {
        background-color: #333333;
        padding: 15px;
      }
        nav h1 {
            color: white;
            margin: 0 10px;
            text-decoration: none;
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
        }
        nav ul li {
            display: inline;
            margin-right: 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
        }

        #about {
            padding: 40px;
            text-align: center;  
        }

        footer {
            background-color: #0a192f;
            color: white;
            text-align: center;
            padding: 20px;
        }
    </style>
    <!-- EXTERNAL CSS -->
    <link rel="stylesheet" href="styles.css">

  </head>

    <body>

        <!-- INLINE CSS Example -->
        <nav style="text-align: center;"
        <h1>Samuel Billy</h1>
        <ul>
            <li><a href="#about">About Me</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
        </nav>
    
        <section id="about">
            <img src="https://avatars.githubusercontent.com/u/260166915?v=4"
            alt="Profile photo of Samuel Billy"
            style="border-radius: 50%; border: 4px 
            solid #0a192f;"><!-- INLINE CSS -->

        <h2>Hi, I'm Samuel Billy!</h2>
        <p>Junior web developer based in Nairobi, Kenya.</p>
        <P>I build responsive and user-friendly websites using modern web technologies like HTML, CSS, JavaScript, and React.</P>
        </section>

        <section id="skills">
            <h2> My Skills</h2>
            
            <div class="skills-box">
                <h3>HTML</h3>
                <p>Semantic structure and accessibility.</p>
            </div>
            
            <div class="skills-box">
                <h3>JavaScript</h3>
                <p>Interactive web functionality and dynamic user experiences.</p>
            </div>
            
            <div class="skills-box">
                <h3>CSS</h3>
                <p>Styling, layouts, and responsive design.</p>
            </div>
        </section>

        <section id="contact">
            <h2>Contact Me</h2>
            <p>Email: samuelbarasa106@gmail.com</p>
            <a href="https://github.com/Solfegesam" target="_blank" rel="noopener noreferrer">Visit My GitHub Profile</a>
        </section>
            
        <footer>
        &copy; 2026 Samuel Billy| Built with HTML & CSS. All rights reserved.
        </footer>

    </body>
</html>

