# flamehoz-website
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FlameHoz - Ultimate Gaming Enthusiast</title>
    <style>
        body {
            background-color: black;
            color: white;
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        header {
            background-color: #673ab7; /* deep purple */
            padding: 1em;
        }

        section {
            padding: 2em;
        }

        footer {
            background-color: #673ab7; /* deep purple */
            padding: 1em;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        #game-container {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 300px;
            border: 2px solid white;
            margin: 20px;
            overflow: hidden;
        }

        canvas {
            border: 2px solid white;
        }
    </style>
</head>

<body>

    <header>
        <h1>FlameHoz</h1>
        <p>Ultimate Gaming Enthusiast</p>
    </header>

    <section>
        <!-- Previous About Me and Gaming Genres content remains unchanged -->

        <!-- Game Section -->
        <h2>Play "FlameHoz Adventures"</h2>
        <div id="game-container">
            <canvas id="gameCanvas" width="800" height="400"></canvas>
        </div>

        <script>
            // Simple game logic for demonstration purposes
            const canvas = document.getElementById('gameCanvas');
            const ctx = canvas.getContext('2d');

            function drawGame() {
                ctx.clearRect(0, 0, canvas.width, canvas.height);

                // Draw game elements
                ctx.fillStyle = 'red';
                ctx.fillRect(50, 50, 50, 50);

                // Add more game elements and logic as needed
            }

            setInterval(drawGame, 1000 / 60); // Update the game every 60 frames per second
        </script>
    </section>

    <section>
        <!-- Key Skills and other sections remain unchanged -->
    </section>

    <footer>
        <p>Contact: your@email.com</p>
    </footer>

</body>

</html>
