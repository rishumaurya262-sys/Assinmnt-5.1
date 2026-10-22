## Assignment 5.1 — Convert an HTML Page into a Styled Page

### File 1: `index.html`

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>College Club</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <nav>
        <a href="index.html">Home</a>
        <a href="about.html">About</a>
        <a href="registration.html">Registration</a>
        <a href="contact.html">Contact</a>
    </nav>

    <h1>Welcome to Our College Club</h1>

    <p>Our college club helps students learn new skills, share ideas, and work together.</p>

    <h2>Our Activities</h2>

    <p>We organize cultural programs, technical workshops, sports activities, and social service events.</p>

    <p>Join our club to learn, participate, and develop your skills.</p>

    <a href="registration.html">Register Now</a>

</body>
</html>
```

### File 2: `style.css`

```css
body {
    background-color: #f0f4f8;
    color: #333333;
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 20px;
}

nav {
    background-color: #243b55;
    padding: 15px;
}

nav a {
    color: white;
    text-decoration: none;
    margin-right: 20px;
    font-weight: bold;
}

nav a:hover {
    color: #ffd700;
}

h1 {
    color: #243b55;
    text-align: center;
}

h2 {
    color: #0077b6;
}

p {
    font-size: 16px;
    line-height: 1.6;
}

a {
    color: #0077b6;
}

a:hover {
    color: #d62828;
}
```