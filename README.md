<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Submit a Recommendation</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f4f4;
      margin: 0;
      padding: 0;
      text-align: center;
    }
    header {
      background: #333;
      color: white;
      padding: 20px;
    }
    h1 {
      margin: 0;
    }
    form {
      margin: 40px auto;
      background: white;
      padding: 20px;
      border-radius: 8px;
      width: 90%;
      max-width: 500px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    input, textarea, button {
      width: 100%;
      margin: 10px 0;
      padding: 10px;
      font-size: 1em;
    }
    button {
      background: #4CAF50;
      border: none;
      color: white;
      cursor: pointer;
      font-size: 1.1em;
    }
    button:hover {
      background: #45a049;
    }
  </style>
</head>
<body>
  <header>
    <h1>💡 Submit a Recommendation</h1>
  </header>

  <form action="https://formspree.io/f/mblzdjvl" method="POST">
    <input type="text" name="name" placeholder="Your Name" required>
    <input type="email" name="_replyto" placeholder="Your Email" required>
    <textarea name="message" placeholder="Your Recommendation..." rows="5" required></textarea>
    <button type="submit">Submit</button>
  </form>
</body>
</html>
