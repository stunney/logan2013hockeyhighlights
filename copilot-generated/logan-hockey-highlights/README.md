### Project Structure
```
hockey-highlights/
│
├── index.html
├── styles.css
└── script.js
```

### 1. `index.html`
This is the main HTML file for your project.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Son's Youth Hockey Highlights</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>My Son's Youth Hockey Highlights</h1>
        <nav>
            <ul>
                <li><a href="#highlights">Highlights</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="highlights">
            <h2>Highlights</h2>
            <div class="video-container">
                <video controls>
                    <source src="highlights/video1.mp4" type="video/mp4">
                    Your browser does not support the video tag.
                </video>
                <p>Highlight 1: Scoring a goal!</p>
            </div>
            <div class="video-container">
                <video controls>
                    <source src="highlights/video2.mp4" type="video/mp4">
                    Your browser does not support the video tag.
                </video>
                <p>Highlight 2: Amazing save!</p>
            </div>
            <!-- Add more highlights as needed -->
        </section>

        <section id="about">
            <h2>About</h2>
            <p>This website showcases the hockey highlights of my son, who plays youth hockey. Here, you can find videos of his best moments on the ice!</p>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p>If you have any questions or would like to get in touch, please email me at <a href="mailto:your-email@example.com">your-email@example.com</a>.</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2023 My Son's Youth Hockey Highlights</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
```

### 2. `styles.css`
This CSS file will style your HTML content.

```css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background: #007BFF;
    color: white;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

main {
    padding: 20px;
}

.video-container {
    margin-bottom: 20px;
}

video {
    width: 100%;
    max-width: 600px;
}

footer {
    text-align: center;
    padding: 10px 0;
    background: #007BFF;
    color: white;
    position: relative;
    bottom: 0;
    width: 100%;
}
```

### 3. `script.js`
This JavaScript file can be used for any interactive features you might want to add later. For now, it can be left empty.

```javascript
// script.js
// You can add any JavaScript functionality here if needed
```

### Instructions to Set Up
1. **Create the Project Folder**: Create a folder named `hockey-highlights` on your computer.
2. **Create Files**: Inside this folder, create the three files: `index.html`, `styles.css`, and `script.js`.
3. **Add Video Files**: Create a subfolder named `highlights` inside the `hockey-highlights` folder and place your video files (e.g., `video1.mp4`, `video2.mp4`) there.
4. **Open in Browser**: Open `index.html` in your web browser to view your project.

### Customization
Feel free to customize the text, styles, and videos to better fit your needs. You can also add more sections or features as you see fit!