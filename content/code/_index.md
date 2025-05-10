---
title: "Code"
description: "Code, package, and modeling framework I developed"
view: 2
---

<style>
  /* Force overall text size reduction */
body, p, div, span, li, td, th {
  font-size: 1.0em !important;
}

#description {
  color: grey;
  font-size: 1.1em;
  text-align: center
}

/* Table of contents box styling */
#toc {
  display: none;
  margin-top: 10px;
  padding: 10px;
  border: 2px solid #f0f0f0;
  background-color: #f0f0f0;
  font-size: 0.8em;
}

/* TOC toggle button */
#toggle-button {
  cursor: pointer;
  color: blue;
  text-decoration: underline;
  display: inline-flex;
  align-items: center;
  font-size: 0.9em;
}

/* TOC arrow */
#arrow {
  margin-left: 5px;
  transition: transform 0.3s;
}
#arrow.rotate {
  transform: rotate(90deg);
}

.model-item {
  display: flex;
  align-items: center;
  margin-bottom: 10px;
}

.model-description {
  margin-left: 10px;
  font-size: 0.9em;
}

.model-logo {
  width: 100px; /* Adjust size as needed */
  height: auto; /* Ensure aspect ratio is maintained */
  margin-left: auto; /* Push logo to the right */
}
</style>

<div>
  <p id="description">Models I use, and my custom codes and package</p>
  <p id="toggle-button" onclick="toggleTOC()">Table of Contents <span id="arrow">➤</span></p>
  <div id="toc">
    <ul>
      <li><a href="#model">Models I use</a></li>
      <li><a href="#rpackage">R package I developed</a></li>
      <li><a href="#custom-code">My scripts</a></li>
    </ul>
  </div>
</div>

<script>
function toggleTOC() {
  var toc = document.getElementById("toc");
  var arrow = document.getElementById("arrow");
  if (toc.style.display === "none") {
    toc.style.display = "block";
    arrow.classList.add("rotate");
  } else {
    toc.style.display = "none";
    arrow.classList.remove("rotate");
  }
}
</script>

---

### <a id="model">Models I use 🔄</a>

<div class="model-item">
  <div class="model-description">
    <p><a href="https://zenodo.org/record/7973200">1D-STEP-GENDEC-CN</a> simulates in Sahelian herbaceous savannas the water, C and N cycling between the atmosphere, vegetation, and soil</p>
  </div>
  <div class="model-logo">
    <img src="step1d.png" alt="STEP 1D">
  </div>
</div>

<div class="model-item">
  <div class="model-description">
    <p><a href="https://zenodo.org/record/7866674">2D-STEP-GENDEC-CN</a> is the spatialized version of 1D-STEP-GENDEC-CN</p>
  </div>
  <div class="model-logo">
    <img src="step2d.png" alt="STEP 2D">
  </div>
</div>

<div class="model-item">
  <div class="model-description">
    <p><a href="https://vezy.github.io/DynACof/">DynACof:</a> The Dynamic Agroforestry Coffee Crop Model, is a generic tree-growth model </p>
  </div>
  <div class="model-logo">
    <img src="Dynacof.png" alt="Dynacof">
  </div>
</div>

<div class="model-item">
  <div class="model-description">
    <p><a href="https://stics.inrae.fr/">STICS:</a> Simulateur mulTIdisciplinaire pour les Cultures Standard (Multidisciplinary simulator for standard crops)</p>
  </div>
  <div class="model-logo">
    <img src="stics.jpg" alt="STICS">
  </div>
</div>

<div class="model-item">
  <div class="model-description">
    <p><a href="https://www.ipef.br/publicacoes/stecnica/nr48/ipef-sertec-48-109.pdf">Castanea-Maespa</a> is a coupled model that simulates carbon, water and energy balances of a monospecific forest stand.</p>
  </div>
  <div class="model-logo">
    <img src="maespa.png" alt="Maespa">
  </div>
</div>

---

### <a id="rpackage">R package I developed 📊</a>

<div class="model-item">
  <div class="model-description">
    <p><a href="https://github.com/fredi-agbohessou/rstep">rstep</a> is a workflow package that I developed to perform STEP-GENDEC-CN model simulations within the RStudio environment</p>
  </div>
  <div class="model-logo">
    <img src="rstep.png" alt="Maespa">
  </div>
</div>

---

### <a id="custom-code">My scripts 📄</a>

<div class="model-item">
  <div class="model-description">
    <p><a href="https://github.com/fredi-agbohessou/my_scripts/tree/main/BG_Agbohessou_et_al_2024/data_extraction_processing_and_mapping">Codes [data extraction, processing and mapping in]</a>  "Modelling CO2 and N2O emissions from soils in silvopastoral systems of the West African Sahelian band (Agbohessou et al. 2024)"</p>
  </div>
  <div class="model-logo">
    <img src="BG.png" alt="Maespa">
  </div>
</div>


<div class="model-item">
  <div class="model-description">
    <p><a href="https://github.com/fredi-agbohessou/my_scripts/tree/main/AFM_Agbohessou_et_al_2023">Codes [plots, sensitivity and uncertainty analysis in]</a>  "To what extent are greenhouse-gas emissions offset by trees in a Sahelian silvopastoral system? (Agbohessou et al. 2023)"</p>
  </div>
  <div class="model-logo">
    <img src="AFM.png" alt="Maespa">
  </div>
</div>


<div class="model-item">
  <div class="model-description">
    <p><a href="https://github.com/fredi-agbohessou/my_scripts/blob/main/code_delon_et_al_2022/plot_delon_et_al_2022.R">Codes [plots in]</a>  "Nitrogen budget and critical load determination at a Sahelian grazed grassland site (Delon et al. 2022)"</p>
  </div>
  <div class="model-logo">
    <img src="delon_et_al2022.png" alt="Maespa">
  </div>
</div>

