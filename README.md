<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Roblox Script Hub - Cobalt</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #1f1f1f, #101010);
            color: #fff;
            overflow-x: hidden;
        }

        header {
            width: 100%;
            padding: 20px 10px;
            background: rgba(0, 0, 50, 0.8);
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
            animation: fadeIn 1.5s;
        }

        header h1 {
            font-size: 2.5rem;
            color: #00bfff;
        }

        section {
            padding: 60px 20px;
            text-align: center;
        }

        h2 {
            font-size: 2rem;
            margin-bottom: 20px;
        }

        .button {
            background-color: #007bff;
            padding: 15px 30px;
            border-radius: 5px;
            text-decoration: none;
            color: white;
            font-size: 1.2rem;
            margin: 10px;
            transition: all 0.3s ease-in-out;
        }

        .button:hover {
            background-color: #0056b3;
            transform: scale(1.1);
        }

        .scripts-grid {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 30px;
            margin-top: 40px;
        }

        .script-card {
            background-color: rgba(30, 30, 30, 0.9);
            border-radius: 10px;
            padding: 20px;
            width: 300px;
            transition: transform 0.3s ease-in-out;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.5);
        }

        .script-card:hover {
            transform: translateY(-10px);
        }

        .script-card h3 {
            font-size: 1.5rem;
            margin-bottom: 10px;
            color: #00bfff;
        }

        .script-card p {
            font-size: 1rem;
            line-height: 1.6;
        }

        footer {
            padding: 20px;
            text-align: center;
            background-color: #0a0a0a;
            color: #808080;
        }

        footer p a {
            color: #00bfff;
            text-decoration: none;
        }

        footer p a:hover {
            text-decoration: underline;
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to Cobalt - Roblox Script Hub</h1>
    </header>

    <section>
        <h2>Available Scripts</h2>
        <p>Check out some of the best Roblox scripts below:</p>

        <div class="scripts-grid">
            <div class="script-card">
                <h3>Script Name 1</h3>
                <p>A description of the script goes here. It explains what the script does and any key features.</p>
                <a href="#" class="button">View Script</a>
            </div>

            <div class="script-card">
                <h3>Script Name 2</h3>
                <p>Another amazing script that enhances your Roblox experience.</p>
                <a href="#" class="button">View Script</a>
            </div>

            <div class="script-card">
                <h3>Script Name 3</h3>
                <p>This script offers cool new abilities. Check it out!</p>
                <a href="#" class="button">View Script</a>
            </div>
        </div>
    </section>

    <footer>
        <p>Created by <a href="https://github.com/yourusername">Your GitHub</a>. Powered by Cobalt.</p>
    </footer>

</body>
</html>
