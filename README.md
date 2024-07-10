<!DOCTYPE html>
<html>
<head>
    <title>Enam web page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #a03604be;
        }

        header {
            background-color: #fc975dab;
            color: #b81c1c;
            text-align: center;
            padding: 2rem 0;
            position: relative; /* Add this */
        }

        .header-content h1 {
            font-size: 2.5rem;
        }

        /* Add styles for the round profile picture */
        .profile-picture {
            width: 150px; /* Adjust the size as needed */
            height: 150px;
            border-radius: 50%; /* Create a circular shape */
            object-fit: contain; /* To ensure the image fills the circular area */
            position: absolute; /* Add this */
            top: 30px; /* Adjust top position as needed */
            left: 20px;  /* Adjust left position as needed */
        }

        nav {
            background-color: #a03604be;
            color: #111111;
            text-align: center;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 20px;
        }

        nav ul li a {
            text-decoration: none;
            color: #f8f5f5;
        }

        .section-content {
            background-color: #fff;
            padding: 2rem;
            margin: 1rem;
            border-radius: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: justify;
        }

        .download-button {
            background-color: #e7800a;
            color: #fff;
            padding: 0.5rem 1rem;
            text-decoration: none;
            border-radius: 20px;
            display: inline-block;
            margin-top: 10px;
            align-self: center;
        }

        .download-button:hover {
            background-color: #0e0f0e;
        }

        footer {
            text-align: center;
            padding: 1rem 0;
            background-color: #f3f6f7;
            color: #0e0d0d;
        }

        ul {
            list-style-type: disc;
            padding-left: 20px;
        }
    </style>
</head>
<body>
    <header>
        <div class="header-content">
            <!-- Add your profile picture here -->
            <img src="C:\Users\ELCOT\Desktop\New web\IMG-20220201-WA0014.jpg" alt="Your Profile Picture" class="profile-picture">
            <h1>M Enamul Hussain</h1>
            <h2>Mohamed Farook</h2>
        </div>
    </header>

    <nav>
        <ul>
            <li><a href="#my dream">My Dream</a></li>
            <li><a href="#education">Education Details</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#certificate">Certificate</a></li>
        </ul>
    </nav>

    <section id="about">
        <div class="section-content">
            <h2>My Dream</h2>
            <p>I'm a cyber security expert and technology enthusiast who is passionate about helping organizations protect their data and create secure online environments. I'm driven by the desire to put technology to work for the greater good and empower individuals and businesses to benefit from the digital revolution. I'm dedicated to staying up to date with the latest trends and innovations in the cyber security landscape. I'm also committed to helping others learn more about the importance of online security and how to stay safe online..</p>
        </div>
    </section>

    <section id="education">
        <div class="section-content">
            <CENTER><h1>"EDUCATION DETAILS"</h1></CENTER>
            <h2>UNIVERSITY :</h2>
            <p>ANNAMALAI UNIVERSITY</p>
            <h2>COLLEGE :</h2>
            <p>M.R.K-COLLEGE OF ARTS AND SCIENCE</p>
            <h2>DEGREE :</h2>
            <p>BCA(Computer Application)</p>
        </div>
    </section>

    <section id="skills">
        <div class="section-content">
            <h2>Skills</h2>
            <ul>
                <li>C and C++ language</li>
                <li>Java and Javascript language </li>
                <li>Css and C# language</li>
                <li>Python</li>
                <li>Application and Software developer</li>
                <li>UI/UX Designer</li>
            </ul>
        </div>
    </section>

    <section id="projects">
        <div class="section-content">
            <h2>Projects</h2>
            <ul>
                <li><a href="#">Web site created</a></li>
                <li><a href="#">Application developed</a></li>
                <li><a href="#">Upcoming Projects......</a></li>
                <center><h1>......Coming soon......</h1></center>
                <!-- Add more project links here -->
            </ul>
        </div>
    </section>

    <section id="resume">
    
        <div class="section-content">
            <center>
            <h2>Certificate</h2> 
            <a href="C:\Users\ELCOT\Desktop\New web\Enam.pdf"target="_blank"class="download-button">Download Certificate</a>
        </center>
        <center> 
            <h3>Scan QR Code</h3>
            <h4>Download certificate</h4>
            <img src="C:\Users\ELCOT\Desktop\New web\Enam QR.png" width="150" height="150"</center>
        </div>
        
    </section>

    <footer>
        <p>&copy; 2023 EH Company,Lalpet</p>
    </footer>

    <script>
        // Smooth scrolling to section when clicking on navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();

                const targetId = this.getAttribute('href').substring(1);
                const targetElement = document.getElementById(targetId);
                
                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop,
                        behavior: 'smooth'
                    });
                }
            });
        });
    </script>
</body>
</html>
