# ayuastira.github.io.ayu
web ayu astira untuk pembuatan kalkulator sederhana

<!DOCTYPE html >
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculator</title>
    <link rel="stylesheet" href="stylesheet.css">
  </head>
  <body>
    <div class="calculator">
      <input type="text" class="calculator-screen" value="0" disable />
      <div class="calculator-keys">
        <div class="row">
          <button class="all-clear">AC</button>
          <button class="percentage">%</button>
          <button class="operator" value="/">&divide;</button>
        </div>
        <div class="row">
          <button class="number" value="7">7</button>
          <button class="number" value="8">8</button>
          <button class="number" value="9">9</button>
          <button class="operator" value="*">&times;</button>
        </div>
        <div class="row">
          <button class="number" value="4">4</button>
          <button class="number" value="5">5</button>
          <button class="number" value="6">6</button>
          <button class="operator" value="-">-</button>
        </div>
        <div class="row">
          <button class="number" value="1">1</button>
          <button class="number" value="2">2</button>
          <button class="number" value="3">3</button>
          <button class="operator" value="+">+</button>
        </div>
        <div class="row">
          <button class="number zero-btn" value="0">0</button>
          <button class="decimal" value=".">.</button>
          <button class="equal-sign">=</button>
        </div>
      </div>
    </div>
    <script type="text/javascript" src="JavaScript.js"></script>
  </body>
  </head>
</html>
