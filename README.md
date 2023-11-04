<!DOCTYPE html>
<html>
<head>
  <title>Dummy Login Page</title>
</head>
<body>
  <h1>Dummy Login Page</h1>
  <form id="loginForm">
    <label for="username">Username:</label>
    <input type="text" id="username" name="username" required><br><br>
    <label for="password">Password:</label>
    <input type="password" id="password" name="password" required><br><br>
    <input type="submit" value="Login">
  </form>

  <script>
    document.getElementById("loginForm").addEventListener("submit", function (event) {
      event.preventDefault();
      // Here, you can add your validation logic, and if it's successful, perform the redirection.
      // For this example, we'll simply redirect to another page.
      window.location.href = "me.md"; // Replace with the actual Markdown file you want to redirect to.
    });
  </script>
</body>
</html>
