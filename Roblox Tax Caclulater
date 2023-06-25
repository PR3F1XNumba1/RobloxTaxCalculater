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
