
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Countdown Timer</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <div class="container">
        <h1>Countdown Timer</h1>
        <label for="timeInput">Please input a timer (1-60 seconds):</label>
        <input type="number" id="timeInput" min="1" max="60" inputmode="numeric">
        <button id="startButton">Start Countdown</button>
        <div id="timerDisplay">00:00</div>
    </div>
    <script src="scripts/script.js"></script>
</body>
</html>
