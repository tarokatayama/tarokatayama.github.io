---
layout: single
title: "GIS Portfolio & Visualizations"
permalink: /data/data_viz/
author_profile: true
---

## Technical Skills

<div class="skills-container">
  <div class="skill-bar">
    <span class="skill-name">ArcGIS Pro</span>
    <div class="skill-level" style="width: 95%;">95%</div>
  </div>
  <div class="skill-bar">
    <span class="skill-name">R Statistical Software</span>
    <div class="skill-level" style="width: 75%;">75%</div>
  </div>
  <div class="skill-bar">
    <span class="skill-name">Python</span>
    <div class="skill-level" style="width: 75%;">75%</div>
  </div>
  <div class="skill-bar">
    <span class="skill-name">Data Visualization</span>
    <div class="skill-level" style="width: 80%;">80%</div>
  </div>
</div>

## Portfolio Gallery

### Geospatial Analysis Projects

<div class="portfolio-grid">
  <!-- Portfolio Item 1 - Replace with your own files -->
  <div class="portfolio-item">
    <div class="portfolio-preview">
      <iframe src="/files/81943Map1.pdf" class="pdf-preview"></iframe>
    </div>
    <h3>Advanced Spatial Analysis</h3>
    <p>Comprehensive overlay analysis examining environmental factors in urban development.</p>
  </div>
  
  <!-- Portfolio Item 2 - Template for easy addition -->
  <div class="portfolio-item">
    <div class="portfolio-preview">
      <iframe src="/files/example-map.pdf" class="pdf-preview"></iframe>
    </div>
    <h3>Land Use Classification</h3>
    <p>Temporal analysis of land use changes across a 10-year period.</p>
  </div>
  
  <!-- Portfolio Item 3 - Template for GIF -->
  <div class="portfolio-item">
    <div class="portfolio-preview">
      <img src="/files/example-animation.gif" class="gif-preview" alt="Temporal data visualization">
    </div>
    <h3>Temporal Data Visualization</h3>
    <p>Animated visualization of seasonal precipitation patterns.</p>
  </div>
  
  <!-- Add more portfolio items following the same structure -->
</div>

<style>
/* Skill bars styling */
.skills-container {
  width: 100%;
  margin: 20px 0 40px;
}
.skill-bar {
  margin-bottom: 15px;
  position: relative;
  background: #f1f1f1;
  border-radius: 4px;
  padding: 5px 0;
}
.skill-name {
  position: absolute;
  left: 10px;
  z-index: 1;
  font-weight: bold;
}
.skill-level {
  background: #4285f4;
  color: white;
  padding: 5px 0;
  text-align: right;
  padding-right: 10px;
  border-radius: 4px;
}

/* Portfolio grid styling */
.portfolio-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
  gap: 30px;
  margin: 30px 0;
}
.portfolio-item {
  background: #ffffff;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 3px 10px rgba(0,0,0,0.1);
  transition: transform 0.3s ease;
}
.portfolio-item:hover {
  transform: translateY(-5px);
}
.portfolio-preview {
  height: 250px;
  overflow: hidden;
  position: relative;
  background: #f5f5f5;
}
.pdf-preview, .gif-preview {
  width: 100%;
  height: 100%;
  object-fit: cover;
  border: none;
}
.portfolio-item h3 {
  padding: 15px 15px 5px;
  margin: 0;
  font-size: 18px;
  color: #333;
}
.portfolio-item p {
  padding: 0 15px 15px;
  margin: 0;
  font-size: 14px;
  color: #666;
}

/* Responsive adjustments */
@media (max-width: 768px) {
  .portfolio-grid {
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
  }
}
</style>