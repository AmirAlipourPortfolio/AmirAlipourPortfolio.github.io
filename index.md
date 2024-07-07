<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Personal Portfolio</h1>
        <nav>
            <ul>
                <li><a href="#biography">Biography</a></li>
                <li><a href="#research">Research</a></li>
                <li><a href="#teaching">Teaching</a></li>
                <li><a href="#events">Events</a></li>
                <li><a href="#misc">MISC</a></li>
            </ul>
        </nav>
    </header>
    
    <main>
        <section id="biography">
            <h2>Biography</h2>
            <p>Biography will be written here.</p>
        </section>
        
        <section id="research">
            <h2>Research</h2>
            <p>My past, present, and future research work will be demonstrated here.</p>
        </section>
        
        <section id="teaching">
            <h2>Teaching</h2>
            <p>Detailing teaching experiences here.</p>
        </section>
        
        <section id="events">
            <h2>Events</h2>
            <p>List of upcoming and past events here.</p>
        </section>
        
        <section id="misc">
            <h2>MISC</h2>
            <p>Any other relevant information (Video game industry. Fundamentals of figure drawing, sports, etc).</p>
        </section>
    </main>
    
    <footer>
        <section id="contact">
            <h2>Contact</h2>
            <form action="" method="POST">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="_replyto" required>
                
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
                
                <button type="submit">Send</button>
            </form>
        </section>
        
        <section id="social">
            <h2>Follow Me</h2>
            <a href="https://twitter.com/yourprofile">Twitter</a>
            <a href="https://linkedin.com/in/yourprofile">LinkedIn</a>
            <a href="https://github.com/yourprofile">GitHub</a>
        </section>
        
        <p>&copy; 2024 Amir Ali-Pour. All rights reserved.</p>
    </footer>
</body>
</html>
