---
layout: single
title: "GIS & Environmental Science Portfolio"
permalink: /portfolio/
author_profile: true
---

## Featured Projects

<div class="portfolio-grid">
  <!-- Water Scarcity Analysis Project -->
  <div class="portfolio-item">
    <div class="portfolio-preview">
      <img src='/images/Screenshot.png' alt='Water Scarcity Map' class="img-preview">
      <div class="overlay">
        <span class="view-full">View Project</span>
      </div>
    </div>
    <h3>Water Scarcity Analysis for EV Battery Materials</h3>
    <p>A comprehensive geospatial analysis conducted in partnership with Rivian Automotive, evaluating water resource impacts of mining operations for battery minerals.</p>
    <div class="portfolio-links">
      <a href="https://dukespace.lib.duke.edu/dspace/bitstream/handle/10161/27165/Duke_MP_2023_Allen-Katayama-MacDonald-Thornton.pdf?sequence=1&isAllowed=y" target="_blank" class="btn-link">View Full Report</a>
      <a href="https://dukeuniv.maps.arcgis.com/apps/dashboards/47a5c479b8854bda9d2bb817986ae758" target="_blank" class="btn-link">Interactive Dashboard</a>
    </div>
  </div>
  
  <!-- Waterville Fast Food Analysis -->
  <div class="portfolio-item">
    <div class="portfolio-preview">
      <img src='/images/waterville.jpeg' alt='Waterville Fast Food Map' class="img-preview">
      <div class="overlay">
        <span class="view-full">View Project</span>
      </div>
    </div>
    <h3>Fast Food Density in Waterville, Maine</h3>
    <p>Using spatial analysis techniques to investigate the urban legend of Waterville as the 'Fast Food Capital of the United States.'</p>
    <div class="portfolio-links">
      <a href="https://storymaps.arcgis.com/stories/8902d7ea4fd34bf3b7079dd8e9df9931" target="_blank" class="btn-link">View StoryMap</a>
    </div>
  </div>
  
  <!-- Fog Monitoring Project -->
  <div class="portfolio-item">
    <a href="/images/fog.gif" target="_blank" class="portfolio-link">
      <div class="portfolio-preview">
        <img src="/images/fog.gif" class="gif-preview" alt="Fog occurrence visualization">
        <div class="overlay">
          <span class="view-full">View Full GIF</span>
        </div>
      </div>
    </a>
    <h3>Fog Monitoring System</h3>
    <p>Innovative monitoring system to measure fog that coastal plant species need to thrive at Cabrillo National Monument.</p>
    <div class="portfolio-links">
      <a href="/file/CABR_FogMon_Annual.pdf" target="_blank" class="btn-link">View Annual Report</a>
      <a href="https://www.nps.gov/articles/000/psv39n1_innovative-system-measures-fog-that-beloved-plants-need-to-thrive.htm" target="_blank" class="btn-link">Read NPS Article</a>
    </div>
  </div>
</div>

## Technical Maps & Visualizations

<div class="portfolio-grid">
  <!-- Advanced Spatial Analysis -->
  <div class="portfolio-item">
    <a href="/files/81943Map1.pdf" target="_blank" class="portfolio-link">
      <div class="portfolio-preview">
        <iframe src="/files/81943Map1.pdf" class="pdf-preview"></iframe>
        <div class="overlay">
          <span class="view-full">View Full PDF</span>
        </div>
      </div>
    </a>
    <h3>Water Rights Transfer Analysis</h3>
    <p>Water rights transfer maps at John Day Fossil Beds National Monument showcasing advanced spatial analysis techniques.</p>
  </div>
  
  <!-- Land Use Classification -->
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
    <p>Temporal analysis of land use changes across a 10-year period using remote sensing and GIS classification techniques.</p>
  </div>

  <!-- Fog Monitoring Annual Report -->
  <div class="portfolio-item">
    <a href="/file/CABR_FogMon_Annual.pdf" target="_blank" class="portfolio-link">
      <div class="portfolio-preview">
        <iframe src="/file/CABR_FogMon_Annual.pdf" class="pdf-preview"></iframe>
        <div class="overlay">
          <span class="view-full">View Full PDF</span>
        </div>
      </div>
    </a>
    <h3>Fog Monitoring Annual Report</h3>
    <p>Detailed annual analysis of fog patterns and their impact on native plant communities at Cabrillo National Monument.</p>
  </div>
</div>

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

<style>
/* Skills styling */
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
.portfolio-link {
  text-decoration: none;
  color: inherit;
  display: block;
}
.pdf-preview, .gif-preview, .img-preview {
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
  padding: 0 15px;
  margin: 0;
  font-size: 14px;
  color: #666;
}
.portfolio-links {
  padding: 5px 15px 15px;
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}
.btn-link {
  display: inline-block;
  background: #f1f1f1;
  color: #333;
  padding: 6px 12px;
  border-radius: 4px;
  text-decoration: none;
  font-size: 13px;
  transition: all 0.2s ease;
}
.btn-link:hover {
  background: #4285f4;
  color: white;
}

/* Responsive adjustments */
@media (max-width: 768px) {
  .portfolio-grid {
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
  }
  .portfolio-links {
    flex-direction: column;
  }
}
</style>