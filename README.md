<!DOCTYPE html>
<html lang="en">
<head>
<style>
    /* CSS Styling */
    body { 
        font-family: 'Comic Sans MS', cursive; 
        text-align: center; 
        margin: 0; 
        background-color: #f4f4f4; 
    }
    header { 
        background-color: #00008b; 
        color: white; 
        padding: 20px; 
    }
    nav a { 
        color: white; 
        margin: 0 15px; 
        text-decoration: none; 
    }
    .card { 
        background: white; 
        margin: 20px auto; 
        padding: 20px; 
        width: 80%; 
        border-radius: 10px; 
        box-shadow: 0 4px 8px rgba(0,0,0,0.1); 
    }
    img { 
        width: 80%; 
        margin: 10px; 
        border-radius: 15px; 
    }
    button { 
        background-color: #00008b; 
        color: white; 
        padding: 15px 30px; 
        border: none; 
        border-radius: 5px; 
        cursor: pointer; 
    }
    footer { 
        background: black; 
        color: white; 
        padding: 20px; 
        margin-top: 20px; 
    }
</style>
</head>
<body>

   <!-- HTML Content -->
   <header>
        <h1>Helping Hands NGO</h1>
        <nav>
            <a href="#">Home</a> <a href="#">About</a> 
            <a href="#">Projects</a> <a href="#">Gallery</a>
            <p><a href="#">Contact</a></p>
        </nav>
    </header>

  <section id="about">
        <h2>About Our NGO</h2>
        <p>Helping Hands NGO works for education, food donation, women empowerment, and helping poor communities.</p>
    </section>

  <section id="projects">
        <h2>Our Projects</h2>
        <div class="card"><h3>Food Donation</h3><p>Providing food for needy people.</p></div>
        <div class="card"><h3>Education Support</h3><p>Helping children with free education.</p></div>
        <div class="card"><h3>Tree Plantation</h3><p>Making the environment green and clean.</p></div>
    </section>

  <section id="gallery">
        <h2>Gallery</h2>
        <img src="img1.jpg" alt="Gallery Image 1">
        <img src="img2.jpg" alt="Gallery Image 2">
        <img src="img3.jpg" alt="Gallery Image 3">
    </section>

  <section id="volunteer">
        <h2>Become a Volunteer</h2>
        <button>Join Us</button>
    </section>

  <footer>
        <p>&copy; 2026 Helping Hands NGO | All Rights Reserved</p>
    </footer>

</body>
</html>
