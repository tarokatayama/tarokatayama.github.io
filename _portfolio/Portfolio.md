<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GIS & Environmental Science Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      color: #333;
      margin: 0;
      padding: 0;
    }
    
    .container {
      max-width: 1000px;
      margin: 0 auto;
      padding: 40px;
    }
    
    h1 {
      font-size: 2.5rem;
      margin-bottom: 1.5rem;
    }
    
    h2 {
      font-size: 1.8rem;
      margin: 2rem 0 1rem;
      border-bottom: 2px solid #4285f4;
      padding-bottom: 0.5rem;
    }
    
    h3 {
      font-size: 1.5rem;
      margin: 1.5rem 0 0.5rem;
      color: #333;
    }
    
    p {
      margin-bottom: 1rem;
      font-size: 16px;
    }
    
    /* Portfolio styling */
    .portfolio-item {
      background: #ffffff;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 4px 15px rgba(0,0,0,0.1);
      transition: transform 0.3s ease;
      margin-bottom: 40px;
    }
    
    .portfolio-item:hover {
      transform: translateY(-5px);
    }
    
    .portfolio-content {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 20px;
    }
    
    .portfolio-preview {
      height: 300px;
      overflow: hidden;
      position: relative;
      background: #f5f5f5;
    }
    
    .portfolio-details {
      padding: 20px;
    }
    
    .img-preview {
      width: 100%;
      height: 100%;
      object-fit: cover;
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
      padding: 10px 20px;
      border-radius: 5px;
      font-weight: bold;
      text-transform: uppercase;
      font-size: 14px;
    }
    
    .portfolio-description {
      padding: 25px;
      background: #f9f9f9;
      border-top: 1px solid #eee;
    }
    
    .portfolio-links {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
      margin-top: 20px;
    }
    
    .btn-link {
      display: inline-block;
      background: #4285f4;
      color: white;
      padding: 10px 20px;
      border-radius: 5px;
      text-decoration: none;
      font-size: 14px;
      font-weight: bold;
      transition: all 0.2s ease;
    }
    
    .btn-link:hover {
      background: #3367d6;
      transform: translateY(-2px);
    }
    
    /* Skills styling */
    .skills-container {
      width: 100%;
      margin: 30px 0 40px;
    }
    
    .skill-bar {
      margin-bottom: 20px;
      position: relative;
      background: #f1f1f1;
      border-radius: 5px;
      padding: 10px 0;
    }
    
    .skill-name {
      position: absolute;
      left: 15px;
      z-index: 1;
      font-weight: bold;
    }
    
    .skill-level {
      background: #4285f4;
      color: white;
      padding: 10px 0;
      text-align: right;
      padding-right: 15px;
      border-radius: 5px;
    }
    
    /* Responsive adjustments */
    @media (max-width: 768px) {
      .portfolio-content {
        grid-template-columns: 1fr;
      }
      
      .container {
        padding: 20px;
      }
    }
  </style>
</head>

<body>
  <div class="container">
    <h1>GIS & Environmental Science Portfolio</h1>
    
    <h2>Featured Projects</h2>
    
    <!-- Water Scarcity Analysis Project -->
    <div class="portfolio-item">
      <div class="portfolio-content">
        <div class="portfolio-preview">
          <img src='/images/Screenshot.png' alt='Water Scarcity Map' class="img-preview">
          <div class="overlay">
            <span class="view-full">View Project</span>
          </div>
        </div>
        <div class="portfolio-details">
          <h3>Water Scarcity Analysis for EV Battery Materials</h3>
          <p>A comprehensive geospatial analysis conducted in partnership with Rivian Automotive, evaluating water resource impacts of mining operations for battery minerals.</p>
          <div class="portfolio-links">
            <a href="https://dukespace.lib.duke.edu/dspace/bitstream/handle/10161/27165/Duke_MP_2023_Allen-Katayama-MacDonald-Thornton.pdf?sequence=1&isAllowed=y" target="_blank" class="btn-link">View Full Report</a>
            <a href="https://dukeuniv.maps.arcgis.com/apps/dashboards/47a5c479b8854bda9d2bb817986ae758" target="_blank" class="btn-link">Interactive Dashboard</a>
          </div>
        </div>
      </div>
      <div class="portfolio-description">
        <h3>Project Overview</h3>
        <p>This analysis was the cornerstone of my Master's Project at Duke University, focusing on the water-energy nexus within electric vehicle production. The project evaluated the water footprint of mineral extraction for EV batteries, identifying critical regions where mining operations intersect with water scarcity issues.</p>
        
        <h4>Key Components:</h4>
        <ul>
          <li>Development of comprehensive water scarcity maps using ArcGIS Pro</li>
          <li>Creation of an interactive dashboard for visualizing high-risk mining operations</li>
          <li>Analysis of water usage patterns across different mineral extraction processes</li>
          <li>Recommendations for sustainable water management in battery supply chains</li>
        </ul>
      </div>
    </div>
    
    <!-- Waterville Fast Food Analysis -->
    <div class="portfolio-item">
      <div class="portfolio-content">
        <div class="portfolio-preview">
          <img src='/images/waterville.jpeg' alt='Waterville Fast Food Map' class="img-preview">
          <div class="overlay">
            <span class="view-full">View Project</span>
          </div>
        </div>
        <div class="portfolio-details">
          <h3>Fast Food Density in Waterville, Maine</h3>
          <p>Using spatial analysis techniques to investigate the urban legend of Waterville as the 'Fast Food Capital of the United States.'</p>
          <div class="portfolio-links">
            <a href="https://storymaps.arcgis.com/stories/8902d7ea4fd34bf3b7079dd8e9df9931" target="_blank" class="btn-link">View StoryMap</a>
          </div>
        </div>
      </div>
      <div class="portfolio-description">
        <h3>Project Background</h3>
        <p>This investigation began as a curiosity-driven project to verify a local urban legend in Waterville, Maine. Using geospatial analysis tools, I examined the density of fast food establishments relative to population size to determine if the town truly deserved its unofficial title as the "Fast Food Capital of the United States."</p>
        
        <h4>Technical Approach:</h4>
        <ul>
          <li>Data collection and cleaning using Python in Jupyter Notebooks</li>
          <li>Spatial analysis of restaurant density patterns</li>
          <li>Population-based statistical comparisons with national averages</li>
          <li>Creation of an engaging, interactive narrative using ArcGIS StoryMaps</li>
        </ul>
      </div>
    </div>
    
    <!-- Fog Monitoring Project -->
    <div class="portfolio-item">
      <div class="portfolio-content">
        <div class="portfolio-preview">
          <img src="/images/fog.gif" class="img-preview" alt="Fog occurrence visualization">
          <div class="overlay">
            <span class="view-full">View Full GIF</span>
          </div>
        </div>
        <div class="portfolio-details">
          <h3>Fog Monitoring System</h3>
          <p>Innovative monitoring system to measure fog that coastal plant species need to thrive at Cabrillo National Monument.</p>
          <div class="portfolio-links">
            <a href="/file/CABR_FogMon_Annual.pdf" target="_blank" class="btn-link">View Annual Report</a>
            <a href="https://www.nps.gov/articles/000/psv39n1_innovative-system-measures-fog-that-beloved-plants-need-to-thrive.htm" target="_blank" class="btn-link">Read NPS Article</a>
          </div>
        </div>
      </div>
    </div>
    
    <h2>Technical Maps & Visualizations</h2>
    
    <!-- Technical maps section -->
    <div class="portfolio-item">
      <div class="portfolio-content">
        <div class="portfolio-preview">
          <iframe src="/files/81943Map1.pdf" class="img-preview"></iframe>
          <div class="overlay">
            <span class="view-full">View Full PDF</span>
          </div>
        </div>
        <div class="portfolio-details">
          <h3>Water Rights Transfer Analysis</h3>
          <p>Water rights transfer maps at John Day Fossil Beds National Monument showcasing advanced spatial analysis techniques.</p>
        </div>
      </div>
    </div>
    
    <div class="portfolio-item">
      <div class="portfolio-content">
        <div class="portfolio-preview">
          <iframe src="/files/example-map.pdf" class="img-preview"></iframe>
          <div class="overlay">
            <span class="view-full">View Full PDF</span>
          </div>
        </div>
        <div class="portfolio-details">
          <h3>Land Use Classification</h3>
          <p>Temporal analysis of land use changes across a 10-year period using remote sensing and GIS classification techniques.</p>
        </div>
      </div>
    </div>
    
    <div class="portfolio-item">
      <div class="portfolio-content">
        <div class="portfolio-preview">
          <iframe src="/file/CABR_FogMon_Annual.pdf" class="img-preview"></iframe>
          <div class="overlay">
            <span class="view-full">View Full PDF</span>
          </div>
        </div>
        <div class="portfolio-details">
          <h3>Fog Monitoring Annual Report</h3>
          <p>Detailed annual analysis of fog patterns and their impact on native plant communities at Cabrillo National Monument.</p>
        </div>
      </div>
    </div>
    
    <h2>Technical Skills</h2>
    
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
  </div>
</body>
</html>