<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Your Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1rem;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin-right: 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
        }
        .hero {
            background: url('https://via.placeholder.com/1500x500') no-repeat center center/cover;
            height: 500px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #fff;
            font-size: 3rem;
        }
        .content {
            padding: 2rem;
        }
        .content h2 {
            text-align: center;
            margin-bottom: 2rem;
        }
        .content p {
            max-width: 800px;
            margin: 0 auto;
            line-height: 1.6;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1rem;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to My Website</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero" id="home">
        <div>
            <h2>Your Catchy Hero Message</h2>
        </div>
    </section>

    <section class="content" id="about">
        <h2>About Us</h2>
        <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur eget lorem ac quam aliquet vehicula. 
            Suspendisse potenti. Duis feugiat ligula a lacus efficitur, non lacinia lorem ultricies. 
            Proin et ligula vitae tortor convallis accumsan.
        </p>
    </section>

    <section class="content" id="services">
        <h2>Our Services</h2>
        <p>
            We offer a wide range of services to meet your needs. Whether you need web development, graphic design, 
            or digital marketing, we have the expertise to deliver outstanding results.
        </p>
    </section>

    <footer id="contact">
        <p>Contact us at: info@example.com | Phone: (123) 456-7890</p>
    </footer>

</body>
</html>
