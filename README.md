# YAHOODPRIVACY
the basics

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Privacy Consent</title>
</head>
<body>
  <h1>Bot Privacy Consent</h1>
  <p>Please read and agree to use the bot.</p>
  <form action="/submit" method="post">
    <label for="name">Your Name:</label><br>
    <input type="text" id="name" name="name" required><br><br>

    <label for="agree">I agree to the privacy terms:</label>
    <input type="checkbox" id="agree" name="agree" value="yes" required><br><br>

    <button type="submit">Submit</button>
  </form>
  
  <h2>Privacy Terms</h2>
  <p>We do not share your data. We only use your name to make the bot work. You can stop using the bot at any time.</p>
</body>
</html>
```
