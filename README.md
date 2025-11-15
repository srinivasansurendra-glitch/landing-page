<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Violet Portfolio</title>

    <style>
        *{
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }

        body{
            background: #f4e9ff; /* light violet */
            color: #333;
        }

        /* NAVBAR */
        nav{
            width: 100%;
            background: #6a0dad; /* violet */
            padding: 15px 40px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            color: white;
        }

        nav .logo{
            font-size: 26px;
            font-weight: bold;
        }

        nav ul{
            display: flex;
            list-style: none;
        }

        nav ul li{
            margin-left: 22px;
        }

        nav ul li a{
            text-decoration: none;
            color: white;
            font-size: 16px;
        }

        /* HERO SECTION */
        .hero{
            position: relative;
            background: #6a0dad;
            padding: 90px 80px;
            color: white;
            overflow: hidden;
        }

        /* Watermark image on right */
        .hero::after{
            content: "";
            background: url("https://images.pexels.com/photos/614810/pexels-photo-614810.jpeg") no-repeat right;
            background-size: 450px;
            opacity: 0.15;      /* watermark effect */
            position: absolute;
            top: 0;
            right: 0;
            width: 100%;
            height: 100%;
        }

        .hero h1{
            font-size: 45px;
            font-weight: 700;
        }

        .hero p{
            width: 60%;
            margin: 15px 0;
            font-size: 18px;
        }

        .btn{
            padding: 12px 25px;
            background: #a357ff;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 17px;
        }

        /* ABOUT SECTION */
        .about{
            padding: 60px 80px;
            background: white;
            display: flex;
            align-items: center;
            gap: 40px;
        }

        .about-text h2{
            color: #6a0dad;
            font-size: 32px;
            margin-bottom: 10px;
        }

        .about-text p{
            margin-bottom: 15px;
            line-height: 1.6;
        }

        .resume-btn{
            padding: 12px 25px;
            background: #6a0dad;
            color: white;
            border: none;
            border-radius: 5px;
        }

        /* Man image on left */
        .about img{
            width: 290px;
            border-radius: 10px;
        }
    </style>
</head>
<body>

    <!-- NAV BAR -->
    <nav>
        <div class="logo">Online Portfolio</div>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About Me</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">Skills</a></li>
            <li><a href="#">Experience</a></li>
            <li><a href="#">Works</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>

    <!-- HERO -->
    <section class="hero">
        <h1>SURENDRA KUMAR S</h1>
        <p>I am a Professional Developer with 5 years of experience in the IT sector. Passionate about teaching and technology.</p>
        <button class="btn">Hire Me</button>
    </section>

    <!-- ABOUT SECTION -->
    <section class="about">
        <img src="https://images.pexels.com/photos/220453/pexels-photo-220453.jpeg" alt="Man">
        
        <div class="about-text">
            <h2>ABOUT ME</h2>
            <p>I am a developer with strong expertise and industry knowledge. I build websites, design UI, and manage systems.</p>
            <p>Skilled in HTML, CSS, JavaScript, communication, and modern web technology.</p>
            <button class="resume-btn">Download Resume</button>
        </div>
    </section>

</body>
</html>
!
