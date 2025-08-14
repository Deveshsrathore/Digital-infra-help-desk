<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Digital Infra Helpdesk</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background: #0056b3;
            color: white;
            padding: 15px 0;
            text-align: center;
        }
        nav {
            background: #003d80;
            display: flex;
            justify-content: center;
            padding: 10px;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            padding: 20px;
            max-width: 1100px;
            margin: auto;
        }
        .services {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
        }
        .service {
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.1);
            text-align: center;
        }
        footer {
            background: #003d80;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 20px;
        }
        .contact-form {
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.1);
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            margin: 8px 0;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        button {
            background: #0056b3;
            color: white;
            border: none;
            padding: 10px 15px;
            cursor: pointer;
            border-radius: 5px;
        }
        button:hover {
            background: #003d80;
        }
    </style>
</head>
<body>

    <header>
        <h1>Digital Infra Helpdesk</h1>
        <p>Your Partner in IT & Infrastructure Solutions</p>
    </header>

    <nav>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="container">
        <section id="services">
            <h2>Our Services</h2>
            <div class="services">
                <div class="service">
                    <h3>ERP Support</h3>
                    <p>End-to-end SAP & ERP solutions for small contractors & enterprises.</p>
                </div>
                <div class="service">
                    <h3>Inventory and Raw material management </h3>
                    <p>Managment inventory and raw material for your business presence online</p>
                </div>
                <div class="service">
                    <h3>IT Infrastructure</h3>
                    <p>Networking, servers, IoT support, and cloud solutions.</p>
                </div>
                <div class="service">
                    <h3>Data Analytics</h3>
                    <p>Power BI, SQL, and reporting solutions for better decisions.</p>
                </div>
            </div>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <div class="contact-form">
                <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
                    <input type="text" name="name" placeholder="Your Name" required>
                    <input type="email" name="email" placeholder="Your Email" required>
                    <input type="text" name="phone" placeholder="Your Phone" required>
                    <textarea name="message" placeholder="Your Message" rows="4" required></textarea>
                    <button type="submit">Send Message</button>
                </form>
                <p>Email: contact@digitalinfrahelpdesk.com</p>
                <p>Phone: +91 9536020859</p>
            </div>
        </section>
    </div>

    <footer>
        <p>© 2025 Digital Infra Helpdesk. All Rights Reserved.</p>
    </footer>

</body>
</html>
