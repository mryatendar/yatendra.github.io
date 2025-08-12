<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>YATENDRASHAR.COM</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #0a0a0a;
            color: #fff;
        }
        header {
            background: linear-gradient(90deg, #8e2de2, #4a00e0);
            padding: 40px 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 3rem;
            letter-spacing: 2px;
        }
        section {
            padding: 40px 20px;
            max-width: 900px;
            margin: auto;
        }
        .services {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }
        .card {
            background: #1a1a1a;
            padding: 20px;
            border-radius: 10px;
            border: 1px solid #4a00e0;
        }
        form {
            display: grid;
            gap: 15px;
        }
        input, textarea {
            padding: 10px;
            border: none;
            border-radius: 5px;
            font-size: 1rem;
        }
        button {
            background: #8e2de2;
            color: #fff;
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1rem;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #111;
            border-top: 1px solid #333;
        }
    </style>
</head>
<body>
    <header>
        <h1>YATENDRASHAR.COM</h1>
        <p>Premium Personal Portfolio</p>
    </header>

    <section>
        <h2>About Me</h2>
        <p>Hello! I'm Yatendar, and this is my official portfolio website. I showcase my skills, services, and projects here. Let's connect and work together!</p>
    </section>

    <section>
        <h2>Services</h2>
        <div class="services">
            <div class="card">Web Design & Development</div>
            <div class="card">Creative Graphics</div>
            <div class="card">Content Creation</div>
        </div>
    </section>

    <section>
        <h2>Contact Me</h2>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" rows="5" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        &copy; 2025 YATENDRASHAR.COM | All Rights Reserved
    </footer>
</body>
</html>
