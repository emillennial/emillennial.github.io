---
layout: default  # Use your site's default layout, or set to "none" if you have no layout
title: Portfolio
subtitle: ♻️🍕💻💧💀🎮🌱🎧🍟🦷🎬✨
permalink: /portfolio/
---

<style>
/* Add your CSS styles here */
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
    cursor: pointer;
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
.portfolio-details {
    padding: 15px;
    background-color: #f9f9f9;
    margin: 10px 0;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    border-radius: 8px;
    display: none; /* Initially hidden */
}
.portfolio-summary {
    cursor: pointer;
}
</style>

<div class="portfolio-container">
    <!-- Portfolio Item 1 -->
    <div class="portfolio-item">
        <div class="portfolio-summary" onclick="toggleCaseStudy('project1')">
            <img src="/img/image1.jpg" alt="Project 1" class="portfolio-image">
            <div class="portfolio-content">
                <h3 class="portfolio-title">Project 1</h3>
                <p class="portfolio-description">Brief description of Project 1.</p>
            </div>
        </div>
        <div id="project1" class="portfolio-details">
            <p>Here are the details of Project 1. This section will expand with more information when clicked.</p>
            <p><strong>Technologies Used:</strong> HTML, CSS, JavaScript</p>
            <p><strong>Challenges:</strong> Detail some challenges faced during the project.</p>
            <p><strong>Outcome:</strong> Describe the outcome and impact of the project.</p>
        </div>
    </div>

    <!-- Portfolio Item 2 -->
    <div class="portfolio-item">
        <div class="portfolio-summary" onclick="toggleCaseStudy('project2')">
            <img src="/img/image2.jpg" alt="Project 2" class="portfolio-image">
            <div class="portfolio-content">
                <h3 class="portfolio-title">Project 2</h3>
                <p class="portfolio-description">Brief description of Project 2.</p>
            </div>
        </div>
        <div id="project2" class="portfolio-details">
            <p>Details for Project 2 go here.</p>
        </div>
    </div>

    <!-- Add more portfolio items as needed -->
</div>

<script>
/* Add your JavaScript here */
function toggleCaseStudy(caseStudyId) {
    var element = document.getElementById(caseStudyId);
    if (element.style.display === "none" || element.style.display === "") {
        element.style.display = "block";
    } else {
        element.style.display = "none";
    }
}
</script>