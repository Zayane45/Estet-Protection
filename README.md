<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Women's Data Security Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #007bff;
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        h1 {
            margin: 0;
        }

        main {
            padding: 20px;
        }

        section {
            margin-bottom: 30px;
        }

        h2 {
            color: #007bff;
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        li {
            padding: 5px 0;
        }

        button {
            background-color: #007bff;
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        button:hover {
            background-color: #0056b3;
        }

        footer {
            background-color: #333;
            color: #fff;
            padding: 10px 20px;
            text-align: center;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Women's Data Security Page</h1>
    </header>
    <main>
        <section>
            <h2>Security Tips</h2>
            <ul>
                <li>Do not share your password with anyone.</li>
                <li>Regularly update your security software.</li>
                <li>Avoid opening email messages from unknown senders.</li>
                <li>Use strong passwords that include uppercase and lowercase letters, numbers, and symbols.</li>
                <li>Copy links before opening them to verify their authenticity.</li>
            </ul>
        </section>
        <section>
            <h2>Secure Contact Form</h2>
            <form action="process.php" method="post">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                <br><br>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <br><br>
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
                <br><br>
                <button type="submit">Send</button>
            </form>
        </section>
    </main>
    <footer>
        <p>All rights reserved &copy; 2024</p>
    </footer>
</body>
</html>

 
