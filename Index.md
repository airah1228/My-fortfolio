# My-fortfolio website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Airah Nicolei delos Reyes - Portfolio</title>
    <style>
        body {
            font-family: sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #fff;
            padding: 20px;
            text-align: center;
        }
        h1 {
            margin-top: 0;
        }
        section {
            padding: 20px;
            background-color: #fff;
            margin: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        img {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 0 auto 20px auto;
            border-radius: 5px;
        }
        .project {
            margin-bottom: 20px;
        }
        .project img {
            max-width: 300px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: #fff;
        }
        a {
            color: #007bff;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        @media (max-width: 768px) {
            section {
                margin: 10px;
            }
            img {
                max-width: 100%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Airah Nicolei delos Reyes</h1>
        <p>BS Entrepreneurship Student | Baker | Nature Lover | Artist</p>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <img src="avatar.jpg" alt="Airah Nicolei delos Reyes">
        <p>Hello! I’m Airah Nicolei delos Reyes, a first-year BS Entrepreneurship student at Mariano Marcos State University. I’m passionate about learning how to start and manage businesses, and I enjoy taking risks when it comes to exploring new opportunities. I have a strong interest in baking, nature photography, and creating art, which I often combine with my business ideas. I’m a creative and curious individual who loves turning small ideas into meaningful projects. Whether it’s designing a product, capturing nature’s beauty through my camera, or experimenting with new recipes, I always bring enthusiasm and attention to detail. My goal is to keep growing as an entrepreneur while doing the things I love.</p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>SweetBox Brownie Shop</h3>
            <p>A simple page I created to showcase my small brownie business. It includes a photo of my homemade brownies and a short description of the different flavors I offer.</p>
            <img src="brownies.jpg" alt="Brownies">
        </div>
        <div class="project">
            <h3>Nature Photography Gallery</h3>
            <p>A photo gallery that displays some of my favorite nature shots. This project shows my love for nature and photography in a simple and organized layout that looks good on both phones and computers.</p>
            <img src="nature.jpg" alt="Nature Photography">
        </div>
        <div class="project">
            <h3>Brownie Flavors & Price List</h3>
            <img src="brownie_flavors.jpg" alt="Brownie Flavors and Prices">
        </div>

    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Email: <a href="mailto:airahnicoleidelosreyes@gmail.com">airahnicoleidelosreyes@gmail.com</a></p>
        <p>Phone: 0960-913-9158</p>
    </section>

    <footer>
        <p>&copy; 2025 Airah Nicolei delos Reyes</p>
    </footer>
</body>
</html>
