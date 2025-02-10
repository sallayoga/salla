<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Salla Yoga</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            color: #4a4a4a;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4d774e;
            color: white;
            text-align: center;
            padding: 20px;
            font-size: 24px;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
        }
        .section {
            background-color: white;
            padding: 20px;
            margin: 20px 0;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .btn {
            background-color: #a67c52;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            display: inline-block;
            margin-top: 10px;
        }
        footer {
            background-color: #4d774e;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
        .contact-form {
            display: flex;
            flex-direction: column;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 5px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .contact-form button {
            background-color: #a67c52;
            color: white;
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        Salla Yoga
    </header>
    <div class="container">
        <div class="section">
            <h2>Welcome to Salla Yoga</h2>
            <p>Find balance and strength through Ashtanga yoga. Join our online classes and courses to deepen your practice.</p>
            <a href="#" class="btn">Join a Class</a>
        </div>
        <div class="section">
            <h2>About Me</h2>
            <p>I'm Salla, an experienced Ashtanga yoga teacher. My goal is to help you build flexibility, strength, and confidence in your yoga practice.</p>
        </div>
        <div class="section">
            <h2>Online Yoga Courses</h2>
            <p>Explore structured courses designed for beginners and advanced practitioners alike.</p>
            <a href="#" class="btn">View Courses</a>
        </div>
        <div class="section">
            <h2>Contact Me</h2>
            <form class="contact-form">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </div>
    </div>
    <footer>
        &copy; 2025 Salla Yoga | Follow on Instagram @sallayoga
    </footer>
</body>
</html>
