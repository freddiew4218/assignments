### Problem 1: Website Header

#### HTML (index.html)
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Website Header</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <a href="https://antra.net">
            <img src="logo.png" alt="Antra Logo">
        </a>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#services">Services</a>
                    <ul class="dropdown">
                        <li><a href="#web">Web Development</a></li>
                        <li><a href="#app">App Development</a></li>
                    </ul>
                </li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
        <div class="search">
            <input type="text" placeholder="Search...">
            <button type="button">Search</button>
        </div>
    </header>
</body>
</html>
```

#### CSS (styles.css)
```css
body {
    font-family: Arial, sans-serif;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px;
    background-color: #333;
    color: white;
}

header img {
    height: 50px;
}

nav ul {
    list-style: none;
    padding: 0;
    display: flex;
}

nav ul li {
    position: relative;
    margin: 0 15px;
}

nav ul li a {
    text-decoration: none;
    color: white;
}

nav ul li .dropdown {
    display: none;
    position: absolute;
    top: 100%;
    left: 0;
    background-color: #444;
    padding: 10px;
}

nav ul li:hover .dropdown {
    display: block;
}

.search {
    display: flex;
}

.search input {
    padding: 5px;
}

.search button {
    padding: 5px;
}
```

### Problem 2: Website Footer

#### HTML (footer.html)
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Website Footer</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <footer>
        <section>
            <h3>About Us</h3>
            <p>Information about the company.</p>
        </section>
        <section>
            <h3>Quick Links</h3>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </section>
        <section>
            <h3>Follow Us</h3>
            <!-- Facebook like box -->
            <div class="fb-like" data-href="https://www.facebook.com/yourpage" data-width="" data-layout="standard" data-action="like" data-size="small" data-share="true"></div>
        </section>
    </footer>
</body>
</html>
```

#### CSS (styles.css)
```css
footer {
    display: flex;
    justify-content: space-around;
    padding: 20px;
    background-color: #333;
    color: white;
}

footer section {
    width: 30%;
}

footer section h3 {
    margin-top: 0;
}

footer ul {
    list-style: none;
    padding: 0;
}

footer ul li {
    margin: 5px 0;
}

footer ul li a {
    text-decoration: none;
    color: white;
}
```

### Problem 3: The Antra News

#### HTML (news.html)
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>The Antra News</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="news-container">
        <article>
            <h2>News Title 1</h2>
            <p>Summary of the news article...</p>
        </article>
        <article>
            <h2>News Title 2</h2>
            <p>Summary of the news article...</p>
        </article>
        <article>
            <h2>News Title 3</h2>
            <p>Summary of the news article...</p>
        </article>
    </div>
    <ul class="paging">
        <li><a href="#prev">Previous</a></li>
        <li><a href="#1">1</a></li>
        <li><a href="#2">2</a></li>
        <li><a href="#3">3</a></li>
        <li><a href="#next">Next</a></li>
    </ul>
</body>
</html>
```

#### CSS (styles.css)
```css
.news-container {
    display: flex;
    justify-content: space-between;
    padding: 20px;
}

.news-container article {
    width: 30%;
    border: 1px solid #ccc;
    padding: 10px;
}

.paging {
    list-style: none;
    display: flex;
    justify-content: center;
    padding: 0;
}

.paging li {
    margin: 0 5px;
}

.paging li a {
    text-decoration: none;
    color: #333;
}
```

### Problem 4: Pretty Website

#### HTML (pretty.html)
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Pretty Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1>Welcome to Our Pretty Website</h1>
    <p>This is a beautifully styled webpage.</p>
</body>
</html>
```

#### CSS (styles.css)
```css
body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    color: #333;
    padding: 20px;
}

h1 {
    color: #0056b3;
}

p {
    font-size: 16px;
    line-height: 1.5;
}
```
