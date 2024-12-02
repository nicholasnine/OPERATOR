<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>New Portfolio</title>

<h1 class="portfolio-title">My Portfolio</h1>

    <!-- Link to an external stylesheet (optional) -->
    <link rel="stylesheet" href="styles.css">
    <!-- Add a favicon (optional) -->
    <link rel="icon" href="favicon.ico" type="image/x-icon">
    
    <section class="image-container">
        <img src="your-image.jpg" alt="Description of the image">
        <p>Caption: This is my portfolio image.</p>
    </section>

</head>
<body>
    <button id="clickMeButton">Precision Vase</button>

    <script>
        document.getElementById('clickMeButton').addEventListener('click', function () {
            const photoUrl = 'precisevaseofgranite.jpg'; // Replace with the actual photo URL
            const popupOptions = 'width=800,height=600,scrollbars=no,resizable=yes';
            window.open(photoUrl, 'PhotoPopup', popupOptions);
        });
    </script>
    
    <!-- Header Section -->
    <header>
        <h1>Welcome to My New Portfolio</h1>
    </header>
    
    <section class="image-container">
        <img src="your-image.jpg" alt="Description of the image">
        <p>Caption: This is my portfolio image.</p>
    </section>
    <!-- Main Content -->
    <main>
        <p>This is the beginning of a new portfolio project.</p>
        <!-- Add your content here -->
    </main>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Your Name. All rights reserved.</p>
    </footer>

    <!-- Link to an external JavaScript file (optional) -->
    <script src="script.js"></script>
</body>
</html>
