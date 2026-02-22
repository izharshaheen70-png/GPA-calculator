# GPA-calculator
Calculate your GPA easily
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GPA Calculator</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="calculator">
    <h1>GPA Calculator</h1>
    
    <div id="subjects">
      <div class="subject">
        <input type="text" class="grade" placeholder="Grade (A/B/C)">
        <input type="number" class="credit" placeholder="Credits">
      </div>
    </div>

    <button id="add-subject">+ Add Subject</button>
    <button id="calculate">Calculate GPA</button>

    <p>Your GPA: <span id="result">0.00</span></p>
  </div>

  <script src="script.js"></script>
</body>
</html>
