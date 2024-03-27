<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Stopwatch</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <div class="heading">
            <b>Stopwatch</b>
        </div>
        <div class="container">
            <div class="timer-display">
                00 : 00 : 00 : 000
            </div>
            <div class="buttons">
                <button id="start-timer">Start</button>
                <button id="pause-timer">Pause</button>
                <button id="reset-timer">Reset</button>
                <button id="lap-time">Lap</button>
            </div>
            <ul id="lap-list"></ul>
        </div>
        <script src="script.js"></script>
    </body>
</html>
