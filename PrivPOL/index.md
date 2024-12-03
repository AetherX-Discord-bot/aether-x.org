<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>AetherX Bot - Privacy Policy</title>
    <style id="theme-style">
        /* Default Light Mode */
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }
        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1rem;
        }
        main {
            padding: 2rem;
            background-color: #fff;
            max-width: 900px;
            margin: 2rem auto;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            flex: 1; /* Allow the main content to expand */
        }
        h1 {
            font-size: 2rem;
            margin-bottom: 1rem;
        }
        h2 {
            font-size: 1.5rem;
            color: #444;
            margin-top: 2rem;
        }
        p {
            margin-bottom: 1rem;
            font-size: 1rem;
        }
        ul {
            list-style-type: disc;
            margin-left: 2rem;
            font-size: 1rem;
        }
        a {
            color: #007bff;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        footer {
            text-align: center;
            padding: 1rem;
            background-color: #333;
            color: #fff;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>AetherX Bot - Privacy Policy</h1>
        <p>Last Updated: December 3, 2024</p>
    </header>

    <main>
        <section>
            <h2>1. No User Data Collection</h2>
            <p>AetherX Bot does not collect, store, or process any personal user data.</p>
            <p>The only data retained by the Bot is the public Discord User IDs of the Bot's developers. These User IDs are used strictly for internal purposes, such as Bot management and troubleshooting. User IDs are inherently public as part of the Discord platform and are not sensitive information.</p>
        </section>

        <section>
            <h2>2. Data Security</h2>
            <p>As the Bot does not store any user data outside of developer User IDs, there is minimal risk of data breaches. Developer User IDs are managed securely within the Bot's internal configuration.</p>
        </section>

        <section>
            <h2>3. No Data Sharing</h2>
            <p>Since the Bot does not collect or store user data, there is no data to share with third parties under any circumstances.</p>
        </section>

        <section>
            <h2>4. No Data Retention</h2>
            <p>The Bot does not retain any data from users. Developer User IDs are part of the Bot's static configuration and are not altered or used beyond Bot-related purposes.</p>
        </section>

        <section>
            <h2>5. Changes to this Privacy Policy</h2>
            <p>We may update this Privacy Policy from time to time to reflect changes in functionality or compliance requirements. Any updates will be communicated via appropriate channels, such as the Bot or its support server.</p>
        </section>

        <section>
            <h2>6. Contact Us</h2>
            <p>If you have any questions or concerns about this Privacy Policy or the Bot’s functionality, please contact us at:</p>
            <p>Email: <a href="mailto:AetherXdevs@outlook.com">AetherXdevs@outlook.com</a></p>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 AetherX Bot. All rights reserved.</p>
    </footer>

    <script>
        // Check for the dark mode cookie
        function getCookie(name) {
            const value = `; ${document.cookie}`;
            const parts = value.split(`; ${name}=`);
            if (parts.length === 2) return parts.pop().split(';').shift();
        }

        // Apply dark mode if the cookie is set to "dark"
        function applyTheme() {
            const theme = getCookie('theme');
            if (theme === 'dark') {
                const darkStyle = `
                    body {
                        background-color: #121212;
                        color: #e0e0e0;
                    }
                    header {
                        background-color: #1e1e1e;
                    }
                    main {
                        background-color: #1e1e1e;
                        box-shadow: none;
                    }
                    a {
                        color: #bb86fc;
                    }
                    footer {
                        background-color: #1e1e1e;
                    }
                `;
                document.getElementById('theme-style').innerHTML += darkStyle;
            }
        }

        // Execute theme application on page load
        applyTheme();
    </script>
</body>
</html>
