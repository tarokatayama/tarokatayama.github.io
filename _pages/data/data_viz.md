---
layout: single
title: "GIS Portfolio & Visualizations"
permalink: /data/data_viz/
author_profile: true
---

## Portfolio Gallery

<div class="portfolio-grid">
  <!-- Portfolio Item 1 - PDF with clickable preview -->
  <div class="portfolio-item">
    <a href="/files/81943Map1.pdf" target="_blank" class="portfolio-link">
      <div class="portfolio-preview">
        <iframe src="/files/81943Map1.pdf" class="pdf-preview"></iframe>
        <div class="overlay">
          <span class="view-full">View Full PDF</span>
        </div>
      </div>
    </a>
    <h3>Advanced Spatial Analysis</h3>
    <p>Water rights transfer maps at John Day Fossil Beds National Monument</p>
  </div>
  
  <!-- Portfolio Item 2 - PDF with clickable preview -->
  <div class="portfolio-item">
    <a href="/files/example-map.pdf" target="_blank" class="portfolio-link">
      <div class="portfolio-preview">
        <iframe src="/files/example-map.pdf" class="pdf-preview"></iframe>
        <div class="overlay">
          <span class="view-full">View Full PDF</span>
        </div>
      </div>
    </a>
    <h3>Land Use Classification</h3>
    <p>Temporal analysis of land use changes across a 10-year period.</p>
  </div>
  
  <!-- Portfolio Item 3 - GIF with clickable preview -->
  <div class="portfolio-item">
    <a href="/images/fog.gif" target="_blank" class="portfolio-link">
      <div class="portfolio-preview">
        <img src="/images/fog.gif" class="gif-preview" alt="Temporal data visualization">
        <div class="overlay">
          <span class="view-full">View Full GIF</span>
        </div>
      </div>
    </a>
    <h3>Temporal Data Visualization</h3>
    <p>Animated visualization of fog occurence at Cabrillo National Monument with real time camera footage overlayed.</p>
  </div>
  
  <!-- Add more portfolio items following the same structure -->
</div>

<style>

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
.portfolio-link {
  text-decoration: none;
  color: inherit;
  display: block;
}
.pdf-preview, .gif-preview {
  width: 100%;
  height: 100%;
  object-fit: cover;
  border: none;
}
.overlay {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: rgba(0, 0, 0, 0.5);
  display: flex;
  align-items: center;
  justify-content: center;
  opacity: 0;
  transition: opacity 0.3s ease;
}
.portfolio-preview:hover .overlay {
  opacity: 1;
}
.view-full {
  background: #4285f4;
  color: white;
  padding: 8px 15px;
  border-radius: 4px;
  font-weight: bold;
  text-transform: uppercase;
  font-size: 14px;
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