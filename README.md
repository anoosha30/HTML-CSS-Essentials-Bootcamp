# HTML-CSS-Essentials-Bootcamp
Assignment - HTML &amp; CSS Essentials Bootcamp

#HTML FILE
<!DOCTYPE html>
<html>
<head>
  <title>Contact Information</title>
  <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
  <header>
    <h1>Contact Information</h1>
  </header>

  <div id="contact-info">
    <h2>Name:</h2>
    <p>Your Name</p>

    <h2>Email:</h2>
    <p>yourname@example.com</p>

    <h2>Phone:</h2>
    <p>123-456-7890</p>
  </div>
</body>
</html>


#CSS FILE
body {
  background-color: #f2f2f2;
  font-family: Arial, sans-serif;
  color: #333;
  margin: 0;
  padding: 0;
}

header {
  background-color: #333;
  color: #fff;
  padding: 20px;
  text-align: center;
}

h1 {
  font-size: 24px;
  margin: 0;
}

#contact-info {
  margin: 50px auto;
  max-width: 400px;
  padding: 20px;
  background-color: #fff;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

h2 {
  font-size: 18px;
  margin-bottom: 5px;
}

p {
  margin-top: 0;
}

