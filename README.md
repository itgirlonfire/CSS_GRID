CSS_GRID/
├── index.html
├── products.html
├── employees.html
├── students.html
├── contact.html
├── css/
│   └── styles.css
└── Docs: README.md

index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/styles.css">
    <title>Main Landing Page</title>
</head>
<body>
    <header>
        <h1>Welcome to Our Website</h1>
        <nav>
            <ul>
                <li><a href="products.html">Products</a></li>
                <li><a href="employees.html">Employees</a></li>
                <li><a href="students.html">Students</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main class="grid-container">
        <section class="grid-item">
            <h2>Featured Product</h2>
            <p>Check out our latest product offering!</p>
        </section>
        <section class="grid-item">
            <h2>Our Team</h2>
            <p>Meet our dedicated team of professionals.</p>
        </section>
        <section class="grid-item">
            <h2>Student Success</h2>
            <p>Learn about our students and their achievements.</p>
        </section>
        <section class="grid-item">
            <h2>Contact Us</h2>
            <p>Get in touch for more information.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Our Website. All rights reserved.</p>
    </footer>
</body>
</html>

style.css
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/styles.css">
    <title>Main Landing Page</title>
</head>
<body>
    <header>
        <h1>Welcome to Our Website</h1>
        <nav>
            <ul>
                <li><a href="products.html">Products</a></li>
                <li><a href="employees.html">Employees</a></li>
                <li><a href="students.html">Students</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main class="grid-container">
        <section class="grid-item">
            <h2>Featured Product</h2>
            <p>Check out our latest product offering!</p>
        </section>
        <section class="grid-item">
            <h2>Our Team</h2>
            <p>Meet our dedicated team of professionals.</p>
        </section>
        <section class="grid-item">
            <h2>Student Success</h2>
            <p>Learn about our students and their achievements.</p>
        </section>
        <section class="grid-item">
            <h2>Contact Us</h2>
            <p>Get in touch for more information.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Our Website. All rights reserved.</p>
    </footer>
</body>
</html>

products.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/styles.css">
    <title>Products</title>
</head>
<body>
    <header>
        <h1>Products</h1>
    </header>
    <main class="grid-container">
        <div class="grid-item">Product 1</div>
        <div class="grid-item">Product 2</div>
        <div class="grid-item">Product 3</div>
        <div class="grid-item">Product 4</div>
        <div class="grid-item">Product 5</div>
    </main>
</body>
</html>

css/style.css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

.grid-container {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 20px;
    padding: 20px;
}

.grid-item {
    background-color: #f2f2f2;
    border: 1px solid #ccc;
    padding: 20px;
    text-align: center;
}
