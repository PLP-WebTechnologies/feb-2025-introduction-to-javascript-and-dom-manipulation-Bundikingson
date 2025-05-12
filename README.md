
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DOM Manipulation</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="header">
        <h1 id="main-heading">DOM Manipulation Demo</h1>
    </header>

    <main class="container">
        <section class="controls">
            <button id="change-text-btn" class="btn">Change Heading</button>
            <button id="change-style-btn" class="btn">Toggle Style</button>
            <button id="add-element-btn" class="btn">Add Item</button>
            <button id="remove-element-btn" class="btn">Remove Item</button>
        </section>

        <section class="content">
            <div id="dynamic-content">
                <p class="info-text">Original content loaded</p>
            </div>
            <ul id="item-list">
                <li>First item</li>
                <li>Second item</li>
            </ul>
        </section>
    </main>

    <footer class="footer">
        <p id="footer-text">© 2023 JavaScript DOM Demo</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    padding: 20px;
}

.header {
    text-align: center;
    margin-bottom: 30px;
    padding: 20px;
    background-color: #2c3e50;
    color: white;
}

.container {
    max-width: 800px;
    margin: 0 auto;
}

.controls {
    display: flex;
    gap: 10px;
    margin-bottom: 20px;
    flex-wrap: wrap;
}

.btn {
    padding: 10px 15px;
    background-color: #3498db;
    color: white;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    transition: background-color 0.3s;
}

.btn:hover {
    background-color: #2980b9;
}

.content {
    background-color: #f9f9f9;
    padding: 20px;
    border-radius: 8px;
}

.info-text {
    margin-bottom: 15px;
    color: #333;
}

#item-list {
    margin-top: 15px;
    padding-left: 20px;
}

#item-list li {
    margin-bottom: 8px;
}

.highlight {
    background-color: #ffeaa7;
    padding: 5px;
    border-left: 4px solid #fdcb6e;
}

.footer {
    text-align: center;
    margin-top: 30px;
    padding: 15px;
    background-color: #ecf0f1;
}
