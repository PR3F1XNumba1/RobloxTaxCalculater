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
<html>
<head>
  <title>Round to Next Whole Number</title>
  <script>
    function roundNumbers() {
      var numbers = document.getElementById("numbers").value;
      var numbersArray = numbers.split(",");

      var roundedNumbers = numbersArray.map(function(number) {
        return Math.ceil(parseFloat(number));
      });

      document.getElementById("result").textContent = "Rounded Numbers: " + roundedNumbers.join(", ");
    }
  </script>
</head>
<body>
  <h1>Round to Next Whole Number</h1>

  <div>
    <label for="numbers">Enter a set of numbers (separated by commas):</label>
    <input type="text" id="numbers">
  </div>

  <button onclick="roundNumbers()">Round</button>

  <div id="result"></div>
</body>
</html>
<html>
<head>
  <title>Donations To support creator</title>
  <style>
    /* Add your CSS styles here */
    /* ... */

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
  <h1>Roblox DevEx Calculator</h1>


  <a class="donate-button" href="https://www.roblox.com/catalog/6735118737/Dark-Blue-Fendi-Hoodie" target="_blank">Donate Robux💎</a>


</body>
</html>
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
  <a class="donate-button" href="https://paypal.me/gametime910?country.x=US&locale.x=en_US" target="_blank">Donate Money💰</a>
</body>
</html>
