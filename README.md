<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>News App</title>
    <link rel="stylesheet" href="style.css">
    <link rel="shortcut icon" href="./pics/favic.jpg" type="image/x-icon">
</head>
<body>

    <nav>
        <div class="main-nav container flex">
            <!-- <img src="./img/hamburger.svg" alt="" class="hamburger"> -->
            <a href="#easynews" onclick="reload()" class="company-logo">
                <img src="./pics/logo.png" alt="company logo">
            </a>
            <div class="nav-links">
                <ul class="flex">
                    <li class="hover-link nav-item" id="ipl" onclick="onNavItemClick('ipl')">IPL</li>
                    <li class="hover-link nav-item" id="bollywood" onclick="onNavItemClick('bollywood')">Bollywood</li>
                    <li class="hover-link nav-item" id="technology" onclick="onNavItemClick('technology')">Technology</li>
                </ul>
            </div>
            <div class="search-bar flex">
                <div class="searched">
                    <input id="search-text" type="text" class="news-input" placeholder="e.g. Science">
                    <button id="search-button" class="search-button">Search</button>
                </div>
                <div class="searching">
                    <img src="./img/search.svg" alt="scan" class="searching-img">
            </div>
            </div>
        </div>
    </nav>
    

    <main>
        <div class="cards-container container flex" id="cards-container">
            
        </div>
    </main>

    <template id="template-news-card">
        <div class="card">
            <div class="card-header">
                <img src="https://via.placeholder.com/400x200" alt="news-image" id="news-img">
            </div>
            <div class="card-content">
                <h3 id="news-title">This is the Title</h3>
                <h6 class="news-source" id="news-source">End Gadget 26/08/2023</h6>
                <p class="news-desc" id="news-desc">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Recusandae saepe quis voluptatum quisquam vitae doloremque facilis molestias quae ratione cumque!</p>
            </div>
        </div>
    </template>

    <script src="script.js"></script>
</body>
</html> 
