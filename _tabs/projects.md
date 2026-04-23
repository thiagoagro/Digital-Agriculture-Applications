---
icon: fas fa-microchip
order: 2
---

## Open-Source Tutorials

<div class="featured-repo">
  <div class="featured-repo-header">
    <div class="featured-repo-icon">&#128218;</div>
    <div>
      <span class="agri-label">GitHub Repository &bull; MIT License</span>
      <h3>R Classification: Drone Image Processing</h3>
    </div>
  </div>
  <p>
    A comprehensive, hands-on course for processing drone-captured imagery using R.
    This tutorial covers the full pipeline from multispectral band importing to ML
    classification and vegetation index extraction &mdash; designed for researchers and
    agronomists working with precision agriculture data.
  </p>
  <div class="repo-features">
    <span class="repo-tag">R 4.4.3</span>
    <span class="repo-tag">Random Forest</span>
    <span class="repo-tag">SVM</span>
    <span class="repo-tag">XGBoost</span>
    <span class="repo-tag">Multispectral</span>
    <span class="repo-tag">Vegetation Indices</span>
    <span class="repo-tag">pliman</span>
    <span class="repo-tag">FieldImageR</span>
  </div>

  <div class="repo-steps">
    <h4>Course Workflow (11 Steps)</h4>
    <div class="steps-grid">
      <div class="step-card">
        <span class="step-num">01</span>
        <p>Package installation &amp; Rtools setup</p>
      </div>
      <div class="step-card">
        <span class="step-num">02</span>
        <p>Library loading</p>
      </div>
      <div class="step-card">
        <span class="step-num">03</span>
        <p>Multispectral band importing</p>
      </div>
      <div class="step-card">
        <span class="step-num">04</span>
        <p>Soil &amp; plant sample creation</p>
      </div>
      <div class="step-card">
        <span class="step-num">05</span>
        <p>ML model training (RF, SVM, XGBoost)</p>
      </div>
      <div class="step-card">
        <span class="step-num">06</span>
        <p>Classified map generation</p>
      </div>
      <div class="step-card">
        <span class="step-num">07</span>
        <p>Model metrics analysis</p>
      </div>
      <div class="step-card">
        <span class="step-num">08</span>
        <p>Soil background removal</p>
      </div>
      <div class="step-card">
        <span class="step-num">09</span>
        <p>Coordinate transformation &amp; buffer</p>
      </div>
      <div class="step-card">
        <span class="step-num">10</span>
        <p>Vegetation index calculation</p>
      </div>
      <div class="step-card">
        <span class="step-num">11</span>
        <p>Data extraction &amp; Excel export</p>
      </div>
    </div>
  </div>

  <div class="repo-prereqs">
    <h4>Requirements</h4>
    <ul>
      <li>R 4.4.3 with Rtools installed</li>
      <li>Multispectral imagery from Pix4D or Agisoft Metashape</li>
      <li>Validated coordinate system for geospatial data</li>
    </ul>
  </div>

  <a class="hero-btn hero-btn-primary" href="https://github.com/thiagoagro/R_classification" target="_blank" rel="noopener">
    Access the Course on GitHub &rarr;
  </a>
</div>

---

## Research Projects

### 1. Peanut Maturity Prediction with AI

<div class="project-card">
  <div class="project-meta">
    <span class="repo-tag">Machine Learning</span>
    <span class="repo-tag">Remote Sensing</span>
    <span class="repo-tag">Precision Agriculture</span>
  </div>

  **Goal:** Predict peanut maturity using climatic variables and satellite-derived vegetation indices.

  **Methods:** SVM, Random Forest, XGBoost, LightGBM, and ANN models with NASA-POWER data and Sentinel-2 indices. Achieved R&sup2; > 0.88 and RMSE < 10%.

  **Impact:** Supports harvest timing decisions in environments where field-level maturity assessment is costly and time-sensitive. Eliminates the need for destructive sampling.
</div>

---

### 2. Corn Plant Detection from UAV Imagery

<div class="project-card">
  <div class="project-meta">
    <span class="repo-tag">YOLOv9</span>
    <span class="repo-tag">Computer Vision</span>
    <span class="repo-tag">UAV</span>
  </div>

  **Goal:** Detect and count corn plants under different soil backgrounds, growth stages, and flight heights.

  **Methods:** YOLOv9-based object detection with UAV imagery preprocessing and evaluation across variable field conditions at the University of Georgia.

  **Impact:** Moves computer vision closer to robust real-world deployment in crop monitoring and stand counting.
</div>

---

### 3. Marigold Flower Detection with YOLOv8

<div class="project-card">
  <div class="project-meta">
    <span class="repo-tag">YOLOv8</span>
    <span class="repo-tag">Deep Learning</span>
    <span class="repo-tag">Ornamental Horticulture</span>
  </div>

  **Goal:** Detect and count marigold flowers using drone images in complex environments.

  **Methods:** YOLOv8-based detection pipeline for high-resolution drone imagery with varying background complexity.

  **Impact:** Demonstrates deep learning applicability beyond row crops into ornamental horticulture.
</div>

---

### 4. Drone Spraying Optimization in Coffee Systems

<div class="project-card">
  <div class="project-meta">
    <span class="repo-tag">Application Technology</span>
    <span class="repo-tag">Drone Spraying</span>
    <span class="repo-tag">DJI Agras</span>
  </div>

  **Goal:** Optimize flight height, volume, and nozzle type for spraying performance in Arabica coffee.

  **Methods:** Experimental design with deposition validation, droplet spectrum analysis, and volumetric distribution evaluation using water-sensitive paper.

  **Impact:** Improves technical decisions in drone-based crop protection operations with direct applicability for field technicians.
</div>

---

### 5. Satellite & Weather Data for Yield Intelligence

<div class="project-card">
  <div class="project-meta">
    <span class="repo-tag">Sentinel-2</span>
    <span class="repo-tag">NASA POWER</span>
    <span class="repo-tag">Machine Learning</span>
  </div>

  **Goal:** Use multispectral satellite data, vegetation indices, and climatic information for crop yield estimation.

  **Methods:** Integration of Sentinel-2 imagery with weather data, regression models, and ML algorithms for sorghum, corn, and sugarcane.

  **Impact:** Enables scalable crop intelligence in regions with limited surface monitoring infrastructure.
</div>

---

### 6. Variable-Rate Nitrogen with Biofertilizers

<div class="project-card">
  <div class="project-meta">
    <span class="repo-tag">Ph.D. Research</span>
    <span class="repo-tag">Variable Rate</span>
    <span class="repo-tag">Azospirillum</span>
  </div>

  **Goal:** Develop variable-rate nitrogen fertilization protocols combining satellite imagery and plant growth-promoting microorganisms.

  **Methods:** Sentinel-2 based prescription maps with Azospirillum spp. inoculation in irrigated maize systems across Brazil and the USA.

  **Impact:** Advancing precision nutrient management toward sustainable and efficient crop production.
</div>

---

## Coming Soon

<div class="callout-panel">
  <p>
    Interactive tutorials for <strong>ML/DL in Digital Agriculture</strong>,
    public notebooks in <strong>Python and R</strong>,
    open datasets with reproducible workflows,
    and practical web applications for crop monitoring and model experimentation.
  </p>
</div>
