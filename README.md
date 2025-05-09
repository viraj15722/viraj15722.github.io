/* --- File: styles.css (External CSS) --- */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f4f4f4;
  color: #333;
}

header {
  background-color: #333;
  color: #fff;
  padding: 1rem;
  text-align: center;
}

nav a {
  margin: 0 15px;
  text-decoration: none;
  color: white;
}

main {
  padding: 2rem;
}

footer {
  background-color: #333;
  color: #fff;
  text-align: center;
  padding: 1rem;
  position: fixed;
  bottom: 0;
  width: 100%;
}

/* --- File: index.html (Home Page) --- */
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Home - My Portfolio</title>
  <link rel="stylesheet" href="styles.css">
  <style>
    h1 {
      color: darkblue;
    }
  </style>
</head>
<body>
  <header>
    <nav>
      <a href="index.html">Home</a>
      <a href="about.html">About</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>
  <main>
    <h1>Welcome to My Portfolio</h1>
    <p style="font-size: 18px;">Explore my work, learn more about me, or get in touch.</p>
  </main>
  <footer>
    &copy; 2025 My Portfolio
  </footer>
</body>
</html>

/* --- File: about.html (About Page) --- */
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>About - My Portfolio</title>
  <link rel="stylesheet" href="styles.css">
  <style>
    h2 {
      color: darkgreen;
    }
  </style>
</head>
<body>
  <header>
    <nav>
      <a href="index.html">Home</a>
      <a href="about.html">About</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>
  <main>
    <h2>About Me</h2>
    <p style="line-height: 1.6;">I am a passionate developer with experience in web design, development, and digital creativity. I love creating clean and efficient solutions to digital problems.</p>
  </main>
  <footer>
    &copy; 2025 My Portfolio
  </footer>
</body>
</html>

/* --- File: contact.html (Contact Page) --- */
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Contact - My Portfolio</title>
  <link rel="stylesheet" href="styles.css">
  <style>
    form {
      background-color: #fff;
      padding: 1rem;
      border-radius: 5px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    label {
      display: block;
      margin: 0.5rem 0 0.2rem;
    }
    input, textarea {
      width: 100%;
      padding: 0.5rem;
      margin-bottom: 1rem;
    }
  </style>
</head>
<body>
  <header>
    <nav>
      <a href="index.html">Home</a>
      <a href="about.html">About</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>
  <main>
    <h2>Contact Me</h2>
    <form action="#" method="post">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name">

      <label for="email">vij_viraj@khalsaschool.ca:</label>
      <input type="email" id="email" name="email">

      <label for="message">Message:</label>
      <textarea id="message" name="message" rows="5"></textarea>

      <button type="submit" style="background-color: darkblue; color: white; padding: 0.5rem 1rem; border: none; border-radius: 4px;">Send</button>
    </form>
  </main>
  <footer>
    &copy; 2025 My Portfolio
  </footer>
</body>
</html>
