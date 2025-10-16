<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Click Event Example</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 50px;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
        }
        #message {
            margin-top: 20px;
            font-size: 18px;
            color: #333;
        }
    </style>
</head>
<body>
    <h1>JavaScript Click Event</h1>
    <button id="myButton">Click Me</button>
    <div id="message"></div>

    <script>
        // Step 1: Select the button
        const button = document.getElementById('myButton');
        const messageDiv = document.getElementById('message');

        // Step 2: Add click event listener
        button.addEventListener('click', function() {
            messageDiv.textContent = "Hello! You clicked the button!";
            alert("Button clicked!"); // optional alert
        });
    </script>
</body>
</html>
