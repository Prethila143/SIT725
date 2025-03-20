<!DOCTYPE html>
<html lang="en">
<head>
 
    <title>SIT 725</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 50px;
        }
        #textToChange {
            margin: 20px;
            font-size: 24px;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
        }
    </style>
</head>
<body>

    <h1>Welcome to SIT 725</h1>
    <p id="textToChange">Applied Software Engineering</p>
    <button onclick="changeText()">Change Text</button>

    <script>
        function changeText() {
            var textElement = document.getElementById("textToChange");
            textElement.style.fontWeight = "bold";
        }
    </script>

</body>
</html>
