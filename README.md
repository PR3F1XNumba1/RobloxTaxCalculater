<html>
<head>
  <title>Roblox Tax Calculator</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
    }

    h1 {
      text-align: center;
    }

    .input-group {
      margin-bottom: 10px;
    }

    label {
      display: inline-block;
      width: 200px;
    }

    input[type="number"] {
      width: 200px;
    }

    button {
      padding: 10px 20px;
      font-size: 16px;
      background-color: #337ab7;
      color: #fff;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }

    .result {
      margin-top: 20px;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <h1>Roblox Tax Calculator</h1>

  <div class="input-group">
    <label for="robux-desired">Robux Desired:</label>
    <input type="number" id="robux-desired">
  </div>

  <button onclick="calculateAmount()">Calculate Amount</button>

  <div class="result" id="amount-needed"></div>

  <script>
    function calculateAmount() {
      var robuxDesired = document.getElementById("robux-desired").value;
      var taxRate = 0.3; // Assuming a 30% tax rate
      var amountNeeded = robuxDesired / (1 - taxRate);

      document.getElementById("amount-needed").textContent = "Amount Needed: " + amountNeeded.toFixed(2) + " Robux";
    }
  </script>
</body>
</html>
/* Styles for the donation button */
.donate-button {
  display: block;
  margin: 20px auto;
  padding: 10px 20px;
  font-size: 18px;
  color: #fff;
  background-color: #337ab7;
  border: none;
  border-radius: 4px;
  text-decoration: none;
  cursor: pointer;
  text-align: center;
}
.donate-button:hover {
  background-color: #23527c;
}

    .donate-button {
      display: block;
      margin: 10px auto;
      padding: 10px 20px;
      font-size: 18px;
      text-align: center;
      color: #fff;
      background-color: #337ab7;
      border: none;
      border-radius: 4px;
      text-decoration: none;
      cursor: pointer;
    }
  </style>
</head>
<body>

  <a class="donate-button" href="https://www.roblox.com/catalog/6735118737/Dark-Blue-Fendi-Hoodie" target="_blank">Donate Robux💎</a>

</body>
</html>
</body>
<html>
<head>
  <title>Donate Button</title>
  <style>
    .donate-button {
      display: inline-block;
      padding: 10px 20px;
      font-size: 16px;
      text-align: center;
      color: #fff;
      background-color: #337ab7;
      border: none;
      border-radius: 4px;
      text-decoration: none;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <a class="donate-button" href="https://paypal.me/gametime910?country.x=US&locale.x=en_US" target="_blank">Donate money💰</a>
</body>
</html>
