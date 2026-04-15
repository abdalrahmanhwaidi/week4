<!DOCTYPE html>
<html>
<head>
  <title>Frontend</title>
</head>
<body>
  <h1>My Frontend 🚀</h1>

  <button onclick="getData()">Click Me</button>

  <p id="result"></p>

  <script>
    async function getData() {
      const res = await fetch("/api");
      const data = await res.text();
      document.getElementById("result").innerText = data;
    }
  </script>
</body>
</html>
