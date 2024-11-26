<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Design & Development</title>
  <syle>
    /* General styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background: linear-gradient(to bottom, #001f3f, #0074D9);
    color: white;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 20px;
    background: #111;
}

header .logo {
    font-size: 1.5rem;
    color: red;
    font-weight: bold;
}

header nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
}

header nav ul li {
    margin: 0 10px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 1rem;
}

header .search {
    color: white;
    font-size: 1rem;
}

/* Hero section */
.hero {
    text-align: center;
    padding: 60px 20px;
    background: url('https://via.placeholder.com/800x400') no-repeat center center/cover;
    color: white;
}

.hero h1 {
    font-size: 2.5rem;
    color: orange;
}

.hero h1 span {
    color: red;
}

.hero p {
    font-size: 1rem;
    margin: 20px 0;
}

.hero .join-btn {
    background: orange;
    color: white;
    border: none;
    padding: 10px 20px;
    font-size: 1rem;
    border-radius: 5px;
    cursor: pointer;
}

/* Login Section */
.login-section {
    background: rgba(0, 0, 0, 0.8);
    margin: 40px auto;
    padding: 20px;
    max-width: 300px;
    text-align: center;
    border-radius: 8px;
}

.login-section h2 {
    margin-bottom: 15px;
}

.login-section input {
    width: 100%;
    padding: 10px;
    margin: 10px 0;
    border: none;
    border-radius: 5px;
}

.login-section button {
    width: 100%;
    padding: 10px;
    margin-top: 10px;
    border: none;
    background: orange;
    color: white;
    font-size: 1rem;
    border-radius: 5px;
    cursor: pointer;
}

.login-section a {
    color: orange;
    text-decoration: none;
}

footer {
    text-align: center;
    color: gray;
    margin: 20px 0;
    font-size: 0.8rem;
}
  </syle>
</head>
<body>
    <header>
        <div class="logo">PraRoz</div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Service</a></li>
                <li><a href="#">Design</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
        <div class="search">Hello guys</div>
    </header>

    <section class="hero">
        <div class="content">
            <h1>Web Design & <span>Development</span> Course</h1>
            <p>
                Web Design is a specialization of the design stream. They also use HTML, CSS, WYSIWYG editing software, markup validators, etc., to create design elements.
            </p>
            <button class="join-btn">Join Us</button>
        </div>
    </section>

    <section class="login-section">
        <h2>Login Here</h2>
        <form>
            <input type="text" placeholder="Enter Username Here">
            <input type="password" placeholder="Enter Password Here">
            <button type="submit">Login</button>
        </form>
        <p>Don't have an account? <a href="#">Sign up here</a></p>
        <p>Log in with</p>
    </section>

    <footer>
        <p>Activate Windows - Go to Settings to activate Windows</p>
    </footer>
</body>
</html>

