---
layout: page
title: Portfolio
subtitle: ♻️🍕💻💧💀🎮🌱🎧🍟🦷🎬✨
permalink: /portfolio/
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #f4f4f4;
        }
        .portfolio-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        .portfolio-item {
            flex: 1 1 300px;
            margin: 10px;
            background: #fff;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            border-radius: 8px;
            overflow: hidden;
            transition: transform 0.3s;
        }
        .portfolio-item:hover {
            transform: scale(1.05);
        }
        .portfolio-image {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        .portfolio-content {
            padding: 15px;
        }
        .portfolio-title {
            font-size: 1.5em;
            margin: 10px 0;
        }
        .portfolio-description {
            font-size: 1em;
            color: #666;
        }
        @media (max-width: 768px) {
            .portfolio-item {
                flex: 1 1 100%;
            }
        }
    </style>
</head>
<body>

    <div class="portfolio-container">
        <!-- Portfolio Item 1 -->
        <div class="portfolio-item">
            <img src="/path/to/your/image1.jpg" alt="Project 1" class="portfolio-image">
            <div class="portfolio-content">
                <h3 class="portfolio-title">Project 1</h3>
                <p class="portfolio-description">Brief description of Project 1. A modern, responsive portfolio item example.</p>
            </div>
        </div>
        
        <!-- Portfolio Item 2 -->
        <div class="portfolio-item">
            <img src="/path/to/your/image2.jpg" alt="Project 2" class="portfolio-image">
            <div class="portfolio-content">
                <h3 class="portfolio-title">Project 2</h3>
                <p class="portfolio-description">Brief description of Project 2. Highlight key features or skills used.</p>
            </div>
        </div>
        
        <!-- Add more portfolio items as needed -->
        
    </div>

</body>
</html>