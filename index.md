<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <script defer src="script.js"></script>
</head>
<body>
    <header>
        <h1>Personal Portfolio</h1>
        <nav>
            <ul>
                <li><a href="#" data-section="biography">Biography</a></li>
                <li><a href="#" data-section="research">Research</a></li>
                <li><a href="#" data-section="teaching">Teaching</a></li>
                <li><a href="#" data-section="events">Events</a></li>
                <li><a href="#" data-section="misc">MISC</a></li>
            </ul>
        </nav>
    </header>
    
    <main id="content">
        <section id="biography" class="content-section">
            <h2>Biography</h2>
            <p>Write your biography here.</p>
        </section>
        
        <section id="research" class="content-section">
            <h2>Research</h2>
            <p>Describe your research here.</p>
        </section>
        
        <section id="teaching" class="content-section">
            <h2>Teaching</h2>
            <p>Detail your teaching experiences here.</p>
        </section>
        
        <section id="events" class="content-section">
            <h2>Events</h2>
            <p>List your upcoming and past events here.</p>
        </section>
        
        <section id="misc" class="content-section">
            <h2>MISC</h2>
            <p>Include any other relevant information here.</p>
        </section>
    </main>
    
    <footer>
        <section id="contact">
            <h2>Contact</h2>
            <form action="https://formspree.io/your-email" method="POST">
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
        
        <p>&copy; 2024 Your Name. All rights reserved.</p>
    </footer>
</body>
</html>
