# ngkamhei.githut.io
the elec3120 assignment1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #666;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
        }
        section {
            background-color: white;
            padding: 20px;
            margin: 20px 0;
            border-radius: 5px;
        }
        footer {
            text-align: center;
            margin-top: 20px;
            color: #666;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
        <p>This is my first webpage</p>
    </header>
    
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>
    
    <section id="home">
        <h2>Home Section</h2>
        <p>This is the home section of my webpage.</p>
        <img src="https://via.placeholder.com/400x200" alt="Placeholder Image">
    </section>
    
    <section id="about">
        <h2>About Me</h2>
        <p>Here's some information about me.</p>
        <ul>
            <li>Web developer</li>
            <li>Learning HTML/CSS</li>
            <li>Building my first website</li>
        </ul>
    </section>
    
    <section id="contact">
        <h2>Contact</h2>
        <form>
            <label for="name">Name:</label><br>
            <input type="text" id="name" name="name"><br><br>
            
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email"><br><br>
            
            <label for="message">Message:</label><br>
            <textarea id="message" name="message" rows="4"></textarea><br><br>
            
            <input type="submit" value="Send Message">
        </form>
    </section>
    
    <footer>
        <p>&copy; 2024 My Website. All rights reserved.</p>
    </footer>
</body>
</html>
