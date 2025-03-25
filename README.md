<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Robux Claim</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #1c1c1c;
            text-align: center;
            color: white;
        }
        .container {
            width: 350px;
            margin: 50px auto;
            background: #262626;
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0px 0px 15px rgba(255, 255, 255, 0.1);
        }
        .logo {
            font-size: 40px;
            font-weight: bold;
            color: white;
        }
        .emoji {
            font-size: 50px;
        }
        .subtitle {
            font-size: 16px;
            margin-top: -10px;
        }
        .steps {
            background: black;
            padding: 10px;
            border-radius: 10px;
            text-align: left;
            margin-top: 20px;
        }
        .step {
            font-size: 14px;
            margin: 5px 0;
        }
        .code-box {
            background: #111;
            padding: 10px;
            margin-top: 15px;
            border-radius: 10px;
            font-size: 18px;
            color: #00ff99;
            display: inline-block;
        }
        .verify-btn {
            background: #00ff99;
            color: black;
            padding: 10px;
            margin-top: 10px;
            border: none;
            cursor: pointer;
            font-size: 16px;
            border-radius: 5px;
        }
        .confirmation {
            background: yellow;
            padding: 10px;
            border-radius: 5px;
            margin-top: 10px;
            display: none;
            font-size: 14px;
            color: black;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="logo">ROBLOX</div>
        <div class="emoji">😊</div>
        <p class="subtitle">Follow the steps below to claim your 5,000 Robux!</p>
        
        <div class="steps">
            <p class="step"><b>1.</b> Download the Temu App</p>
            <p class="step"><b>2.</b> Sign Up for an Account</p>
            <p class="step"><b>3.</b> Search Your Custom Code</p>
        </div>

        <p>Your Custom Code:</p>
        <div class="code-box" id="customCode">128178374</div>
        
        <button class="verify-btn" id="verifyBtn">✅ Verify Participation</button>

        <p class="confirmation" id="confirmationMessage">
            ✅ We will check if your custom code has been used, then you will receive your 5,000 Robux within 24-48hrs!
        </p>
    </div>

    <script>
        document.getElementById("verifyBtn").addEventListener("click", function() {
            document.getElementById("confirmationMessage").style.display = "block";
        });
    </script>
</body>
</html>
