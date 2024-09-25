- 👋 Hi, I’m @chewebsite
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Connect with Us!</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #6200ea;
            color: white;
            text-align: center;
            padding: 2rem 0;
        }
        main {
            padding: 20px;
            text-align: center;
        }
        .social-links {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
        }
        .social-card {
            background: white;
            border: 1px solid #ccc;
            border-radius: 8px;
            padding: 20px;
            text-align: center;
            width: 200px;
            transition: transform 0.2s;
            text-decoration: none;
            color: #333;
        }
        .social-card img {
            width: 50px;
            height: 50px;
        }
        .social-card:hover {
            transform: scale(1.05);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        footer {
            margin-top: 20px;
            padding: 10px;
            background-color: #6200ea;
            color: white;
            text-align: center;
        }
        /* Modal styles */
        .modal {
            display: none;
            position: fixed;
            z-index: 1;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            overflow: auto;
            background-color: rgba(0,0,0,0.4);
        }
        .modal-content {
            background-color: #fefefe;
            margin: 15% auto;
            padding: 20px;
            border: 1px solid #888;
            width: 80%;
        }
        .close {
            color: #aaa;
            float: right;
            font-size: 28px;
            font-weight: bold;
        }
        .close:hover,
        .close:focus {
            color: black;
            text-decoration: none;
            cursor: pointer;
        }
    </style>
</head>
<body>

    <header>
        <h1>Connect with Us!</h1>
        <p>Join our community and stay in touch!</p>
    </header>

    <main>
        <section class="social-links">
            <a href="https://discord.gg/ZmdcTtuc" target="_blank" class="social-card">
                <img src="discord-logo.png" alt="Discord Logo">
                <h2>Join our Discord</h2>
            </a>
            <a href="https://www.facebook.com/kongkimche" target="_blank" class="social-card">
                <img src="facebook-logo.png" alt="Facebook Logo">
                <h2>Message us on Facebook</h2>
            </a>
            <a href="https://www.instagram.com/kongkimche" target="_blank" class="social-card">
                <img src="instagram-logo.png" alt="Instagram Logo">
                <h2>View our Instagram</h2>
            </a>
            <a href="https://wa.me/680822066" target="_blank" class="social-card">
                <img src="whatsapp-logo.png" alt="WhatsApp Logo">
                <h2>Message us on WhatsApp</h2>
            </a>
        </section>
    </main>

    <!-- Modal -->
    <div id="modal" class="modal">
        <div class="modal-content">
            <span class="close" id="close-modal">&times;</span>
            <p>You will be redirected to the chosen platform!</p>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 KKC BRAND. All Rights Reserved.</p>
    </footer>

    <script>
        // Get the modal
        var modal = document.getElementById("modal");

        // Get all social cards
        var socialCards = document.querySelectorAll(".social-card");

        // Get the <span> element that closes the modal
        var closeModal = document.getElementById("close-modal");

        // When a social card is clicked, open the modal
        socialCards.forEach(function(card) {
            card.addEventListener("click", function(event) {
                event.preventDefault(); // Prevent default link action
                modal.style.display = "block"; // Show the modal
                var link = this.href; // Store the link
                // Set a timeout to redirect after a delay
                setTimeout(function() {
                    window.open(link, "_blank"); // Open the link in a new tab
                    modal.style.display = "none"; // Hide the modal
                }, 2000); // Delay in milliseconds
            });
        });

        // When the user clicks on <span> (x), close the modal
        closeModal.onclick = function() {
            modal.style.display = "none";
        }

        // When the user clicks anywhere outside of the modal, close it
        window.onclick = function(event) {
            if (event.target == modal) {
                modal.style.display = "none";
            }
        }
    </script>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Connect with Us!</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #6200ea;
            color: white;
            text-align: center;
            padding: 2rem 0;
        }
        main {
            padding: 20px;
            text-align: center;
        }
        .social-links {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
        }
        .social-card {
            background: white;
            border: 1px solid #ccc;
            border-radius: 8px;
            padding: 20px;
            text-align: center;
            width: 200px;
            transition: transform 0.2s;
            text-decoration: none;
            color: #333;
        }
        .social-card img {
            width: 50px;
            height: 50px;
        }
        .social-card:hover {
            transform: scale(1.05);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        footer {
            margin-top: 20px;
            padding: 10px;
            background-color: #6200ea;
            color: white;
            text-align: center;
        }
        /* Modal styles */
        .modal {
            display: none;
            position: fixed;
            z-index: 1;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            overflow: auto;
            background-color: rgba(0,0,0,0.4);
        }
        .modal-content {
            background-color: #fefefe;
            margin: 15% auto;
            padding: 20px;
            border: 1px solid #888;
            width: 80%;
        }
        .close {
            color: #aaa;
            float: right;
            font-size: 28px;
            font-weight: bold;
        }
        .close:hover,
        .close:focus {
            color: black;
            text-decoration: none;
            cursor: pointer;
        }
    </style>
</head>
<body>

    <header>
        <h1>Connect with Us!</h1>
        <p>Join our community and stay in touch!</p>
    </header>

    <main>
        <section class="social-links">
            <a href="https://discord.gg/ZmdcTtuc" target="_blank" class="social-card">
                <img src="discord-logo.png" alt="Discord Logo">
                <h2>Join our Discord</h2>
            </a>
            <a href="https://www.facebook.com/kongkimche" target="_blank" class="social-card">
                <img src="facebook-logo.png" alt="Facebook Logo">
                <h2>Message us on Facebook</h2>
            </a>
            <a href="https://www.instagram.com/kongkimche" target="_blank" class="social-card">
                <img src="instagram-logo.png" alt="Instagram Logo">
                <h2>View our Instagram</h2>
            </a>
            <a href="https://wa.me/680822066" target="_blank" class="social-card">
                <img src="whatsapp-logo.png" alt="WhatsApp Logo">
                <h2>Message us on WhatsApp</h2>
            </a>
        </section>
    </main>

    <!-- Modal -->
    <div id="modal" class="modal">
        <div class="modal-content">
            <span class="close" id="close-modal">&times;</span>
            <p>You will be redirected to the chosen platform!</p>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 KKC BRAND. All Rights Reserved.</p>
    </footer>

    <script>
        // Get the modal
        var modal = document.getElementById("modal");

        // Get all social cards
        var socialCards = document.querySelectorAll(".social-card");

        // Get the <span> element that closes the modal
        var closeModal = document.getElementById("close-modal");

        // When a social card is clicked, open the modal
        socialCards.forEach(function(card) {
            card.addEventListener("click", function(event) {
                event.preventDefault(); // Prevent default link action
                modal.style.display = "block"; // Show the modal
                var link = this.href; // Store the link
                // Set a timeout to redirect after a delay
                setTimeout(function() {
                    window.open(link, "_blank"); // Open the link in a new tab
                    modal.style.display = "none"; // Hide the modal
                }, 2000); // Delay in milliseconds
            });
        });

        // When the user clicks on <span> (x), close the modal
        closeModal.onclick = function() {
            modal.style.display = "none";
        }

        // When the user clicks anywhere outside of the modal, close it
        window.onclick = function(event) {
            if (event.target == modal) {
                modal.style.display = "none";
            }
        }
    </script>

</body>
</html>
<!---<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Description of your store">
    <meta name="keywords" content="keyword1, keyword2, keyword3">
    <link rel="stylesheet" href="styles.css"> <!-- Your CSS file -->
    <title>KKC BRAND</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: white; /* White background */
        }

        header {
            background-color: #333;
            color: white;
            padding: 10px 0;
        }

        nav ul {
            list-style: none;
            padding: 0;
        }

        nav li {
            display: inline;
            margin-right: 20px;
        }

        nav a {
            color: white;
            text-decoration: none;
        }

        h2 {
            color: #333;
        }

        .product {
            border: 1px solid #ddd;
            padding: 10px;
            margin: 10px;
            text-align: center;
            background-color: #f9f9f9; /* Light background for products */
        }

        .cta-button {
            background-color: #007bff;
            color: white;
            padding: 10px;
            text-decoration: none;
            border-radius: 5px;
        }

        .cta-button:hover {
            background-color: #0056b3;
        }

        .search-bar {
            margin: 20px 0;
        }

        .feedback {
            padding: 20px;
        }

        footer {
            text-align: center;
            padding: 10px 0;
            background-color: #333;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <h1>KKC BRAND</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="products">
            <h2>Our Products</h2>
            <div class="product">
                <img src="product-image-url.jpg" alt="KKC BRAND Product Title">
                <h3>KKC BRAND Product Title</h3>
                <p class="description">Product description highlighting features and benefits.</p>
                <p class="price">$XX.XX</p>
                <button>Add to Cart</button>
            </div>
            <!-- Repeat for other products -->
        </section>

        <section id="testimonials">
            <h2>What Our Customers Say</h2>
            <blockquote>
                <p>"Great quality! Will definitely order again."</p>
                <cite>- Customer Name</cite>
            </blockquote>
        </section>

        <div class="cta">
            <h2>Sign Up for Our Newsletter!</h2>
            <a href="/signup" class="cta-button">Subscribe</a>
        </div>

        <div class="search-bar">
            <input type="text" placeholder="Search products...">
            <button>Search</button>
        </div>

        <section id="feedback" class="feedback">
            <h2>We Value Your Feedback</h2>
            <form>
                <label for="comments">Your Comments:</label>
                <textarea id="comments" name="comments" rows="4" required></textarea>
                <button type="submit">Submit</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 KKC BRAND. All Rights Reserved.</p>
    </footer>
</body>
</html>

chewebsite/chewebsite is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
