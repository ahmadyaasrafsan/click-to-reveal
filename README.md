# click-to-reveal
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Click to Reveal</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      display: flex;
      height: 100vh;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      background-color: #f9f9f9;
    }
    #note {
      display: none;
      margin-top: 20px;
      padding: 15px 25px;
      background-color: #fff0f0;
      border: 1px solid #ffcccc;
      border-radius: 8px;
      color: #cc0000;
      font-size: 1.2em;
    }
    button {
      padding: 30px 30px;
      font-size: 1em;
      background-color: #ff6666;
      color: white;
      border: none;
      border-radius: 8px;
      cursor: pointer;
    }
    button:hover {
      background-color: #ff4c4c;
    }
  </style>
</head>
<body>

  <button onclick="revealNote()">Click me</button>
  <div id="note">sorry for what i did even tho ami jani na ki korsi i still sorry may you forgive me and womp womp loser may you get a bit taller eto short hoye beche aso kemne tf . 💔</div>

  <script>
    function revealNote() {
      document.getElementById("note").style.display = "block";
    }
  </script>

  <h1>phor geb mehh </h1>
  <p>TwT </p>

</body>
</html>
