---
layout: default  # Use your site's default layout, or set to "none" if you have no layout
title: Portfolio
subtitle: ♻️🍕💻💧💀🎮🌱🎧🍟🦷🎬✨
permalink: /portfolio/
---

## My Portfolio
Here are some casestudies of the projects and designs I've worked on. 

---
layout: default  # or any layout you are using
title: Portfolio
permalink: /portfolio/
---

<style>
/* Portfolio Container Styles */
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

/* Modal Styles */
.modal {
    display: none; 
    position: fixed; 
    z-index: 1; 
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    overflow: auto; 
    background-color: rgba(0,0,0,0.9); 
}
.modal-content {
    margin: auto;
    display: block;
    width: 80%;
    max-width: 700px;
}
.modal-content, .close {
    animation-name: zoom;
    animation-duration: 0.6s;
}
@keyframes zoom {
    from {transform: scale(0)}
    to {transform: scale(1)}
}
.close {
    position: absolute;
    top: 15px;
    right: 35px;
    color: #f1f1f1;
    font-size: 40px;
    font-weight: bold;
    transition: 0.3s;
}
.close:hover,
.close:focus {
    color: #bbb;
    text-decoration: none;
    cursor: pointer;
}
</style>

<div class="portfolio-container">
    <!-- Portfolio Item 1 -->
    <div class="portfolio-item">
        <div class="portfolio-summary" onclick="toggleCaseStudy('project1')">
            <img src="/img/image1.jpg" alt="Project 1" class="portfolio-image" onclick="openImageModal('/img/image1.jpg')">
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
            <img src="/img/image2.jpg" alt="Project 2" class="portfolio-image" onclick="openImageModal('/img/image2.jpg')">
            <div class="portfolio-content">
                <h3 class="portfolio-title">Project 2</h3>
                <p class="portfolio-description">Brief description of Project 2.</p>
            </div>
        </div>
        <div id="project2" class="portfolio-details">
            <p>Here are the details of Project 2. This section will expand with more information when clicked.</p>
            <p><strong>Technologies Used:</strong> HTML, CSS, JavaScript</p>
            <p><strong>Challenges:</strong> Detail some challenges faced during the project.</p>
            <p><strong>Outcome:</strong> Describe the outcome and impact of the project.</p>
        </div>
    </div>

    <!-- Portfolio Item 3 -->
    <div class="portfolio-item">
        <div class="portfolio-summary" onclick="toggleCaseStudy('project3')">
            <img src="/img/image3.jpg" alt="Project 3" class="portfolio-image" onclick="openImageModal('/img/image3.jpg')">
            <div class="portfolio-content">
                <h3 class="portfolio-title">Project 3</h3>
                <p class="portfolio-description">Brief description of Project 3.</p>
            </div>
        </div>
        <div id="project3" class="portfolio-details">
            <p>Here are the details of Project 3. This section will expand with more information when clicked.</p>
            <p><strong>Technologies Used:</strong> HTML, CSS, JavaScript</p>
            <p><strong>Challenges:</strong> Detail some challenges faced during the project.</p>
            <p><strong>Outcome:</strong> Describe the outcome and impact of the project.</p>
        </div>
    </div>

    <!-- Portfolio Item 4 -->
    <div class="portfolio-item">
        <div class="portfolio-summary" onclick="toggleCaseStudy('project4')">
            <img src="/img/image4.jpg" alt="Project 4" class="portfolio-image" onclick="openImageModal('/img/image4.jpg')">
            <div class="portfolio-content">
                <h3 class="portfolio-title">Project 4</h3>
                <p class="portfolio-description">Brief description of Project 4.</p>
            </div>
        </div>
        <div id="project4" class="portfolio-details">
            <p>Here are the details of Project 4. This section will expand with more information when clicked.</p>
            <p><strong>Technologies Used:</strong> HTML, CSS, JavaScript</p>
            <p><strong>Challenges:</strong> Detail some challenges faced during the project.</p>
            <p><strong>Outcome:</strong> Describe the outcome and impact of the project.</p>
        </div>
    </div>

    <!-- Portfolio Item 5 -->
    <div class="portfolio-item">
        <div class="portfolio-summary" onclick="toggleCaseStudy('project5')">
            <img src="/img/image5.jpg" alt="Project 5" class="portfolio-image" onclick="openImageModal('/img/image5.jpg')">
            <div class="portfolio-content">
                <h3 class="portfolio-title">Project 5</h3>
                <p class="portfolio-description">Brief description of Project 5.</p>
            </div>
        </div>
        <div id="project5" class="portfolio-details">
            <p>Here are the details of Project 5. This section will expand with more information when clicked.</p>
            <p><strong>Technologies Used:</strong> HTML, CSS, JavaScript</p>
            <p><strong>Challenges:</strong> Detail some challenges faced during the project.</p>
            <p><strong>Outcome:</strong> Describe the outcome and impact of the project.</p>
        </div>
    </div>

    <!-- Portfolio Item 6 -->
    <div class="portfolio-item">
        <div class="portfolio-summary" onclick="toggleCaseStudy('project6')">
            <img src="/img/image6.jpg" alt="Project 6" class="portfolio-image" onclick="openImageModal('/img/image6.jpg')">
            <div class="portfolio-content">
                <h3 class="portfolio-title">Project 6</h3>
                <p class="portfolio-description">Brief description of Project 6.</p>
            </div>
        </div>
        <div id="project6" class="portfolio-details">
            <p>Here are the details of Project 6. This section will expand with more information when clicked.</p>
            <p><strong>Technologies Used:</strong> HTML, CSS, JavaScript</p>
            <p><strong>Challenges:</strong> Detail some challenges faced during the project.</p>
            <p><strong>Outcome:</strong> Describe the outcome and impact of the project.</p>
        </div>
    </div>
</div>

<!-- The Modal for Full-Size Image -->
<div id="imageModal" class="modal" onclick="closeModal()">
  <span class="close" onclick="closeModal()">&times;</span>
  <img class="modal-content" id="modalImage">
</div>

<script>
/* Toggle case study details */
function toggleCaseStudy(caseStudyId) {
    var element = document.getElementById(caseStudyId);
    if (element.style.display === "none" || element.style.display === "") {
        element.style.display = "block";
    } else {
        element.style.display = "none";
    }
}

/* Open the modal with the image */
function openImageModal(imageUrl) {
    var modal = document.getElementById("imageModal");
    var modalImg = document.getElementById("modalImage");
    modal.style.display = "block";
    modalImg.src = imageUrl;
}

/* Close the modal */
function closeModal() {
    var modal = document.getElementById("imageModal");
    modal.style.display = "none";
}
</script>
