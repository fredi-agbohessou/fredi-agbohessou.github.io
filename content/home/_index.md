---
## Configure header of page
text_align_right: false
show_title_as_headline: false
toc: true
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

</style>

<div>
  <p id="description">About me</p>
  <p id="toggle-button" onclick="toggleTOC()">Table of Contents <span id="arrow">➤</span></p>
  <div id="toc">
    <ul>
      <li><a href="#hello-and-welcome-">👋 Hello and Welcome!</a></li>
      <li><a href="#interests-">🌿 Interests</a></li>
      <li><a href="#experience-">💼 Experience</a></li>
      <li><a href="#training-">📚 Training</a></li>
      <li><a href="#leadership-service-and-community-engagement-">🤝 Leadership, service and community engagement</a></li>
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

### Hello and Welcome! 👋
I am a researcher at [UPR aïda](https://www.cirad.fr/nous-connaitre/unites-de-recherche/aida)/[Cirad](https://www.cirad.fr/en), working on agronomy, climate change adaptation and mitigation, with a focus on tropical ecosystems. 

My current research focuses on designing agricultural systems that are more productive, resilient to climate change, and emit significantly fewer greenhouse gases. Specifically, I aim to generate insights into the biogeophysical impacts (e.g., albedo, surface infrared radiation, evapotranspiration) of various agricultural practices. The goal is to better understand how these practices can contribute to both mitigating and adapting to climate change in tropical regions. To achieve this, my approach combines field experiments with modeling techniques and upscaling to examine the broader implications of these practices on a larger, more applicable scale.

My previous works focused on modeling the energy budget and the water, carbon, and nitrogen cycles in tropical ecosystems (in West-Africa and South-East Asia) with an emphasis on GHG emissions, climate change, productivity, and food security.

I integrate data from field experiments, eddy covariance systems, and remote sensing with process-based models to analyze ecosystem responses and adaptation strategies from local to regional scales.

---

### Interests 🌿
- 🌳 Agronomy & Agroforestry
- 🌡️ Climate Change 
- 🌱 Biogeosciences
- 🌎 Field experimentation & Modeling
- 📈 Data analytics and digital tools
- 🛰️ Remote sensing
- 🥗 Food security
- ♻️ Sustainable Development
- 🌍 Africa
- 🌏 South-East Asia

---

### Experience 💼
- **Researcher** &#8729; agronomy, climate change adaptation & mitigation in tropical ecosystems &#8729; *Cirad (Montpellier, France)* &#8729; 05/2025 - ongoing
- **Postdoctoral Researcher** &#8729; modeling the impact of climatic stresses on the functioning of rubber trees (*Hevea brasiliensis*) &#8729; *Cirad (Montpellier, France)* &#8729; 05/2024 - 04/2025
- **PhD Researcher** &#8729; Modeling greenhouse gas balance in agro-silvo-pastoral systems of the Sahel: from plot to landscape &#8729; *ISRA / LMI IESOL / Lero (Dakar, Senegal and Toulouse, France)* &#8729; 01/2021 - 03/2024
- **Internship in Agronomy/Remote Sensing/Biostatistics** &#8729; Using drones to upscale yield and land-equivalent-ratio (LER) from
plot to stand in an agro-silvo-pastoral system through a geostatistical-based method &#8729; *IRD / ISRA (Dakar, Senegal)* &#8729; 04/2019 - 12/2020
- **Forestry Technician** &#8729; Management of Teak (Tectona grandis) and Gmelina arborea plantations &#8729; *National Office of Wood (Bohicon, Benin)* &#8729; 02/2017 - 08/2018
- **Internship in Meteorology** &#8729; Introduction to tools for measuring meteorological parameters &#8729; *Asecna (Kandi, Benin)* &#8729; 04/2014 - 04/2014

---

### Training 📚

- 2024: **Fortran Programming Complete Course**, Udemy, Online, [Course](https://www.udemy.com/course/fortran-course/)

- 2023: **Explore Data Science with Julia**, Udemy, Online, [See certificate of completion](https://www.udemy.com/certificate/UC-464f0a38-4ab3-4906-97f1-6b354a5c8e71/)

- 2022: **Modelling approaches for climate risk and climate change adaptations in the context of sustainable intensification in semi-arid West Africa: Case study with the APSIM model**, CMRA 2022 Summer School organised by ZALF and ICRISAT, Thies, Senegal, [See certificate of completion](Modellingworkshop.pdf) 

- 2021: **Data Visualization and Geospatial Analysis with R**, Leah Kocian, Shubham Jain, Alan Lewis & Vinit Sehgal (Texas A&M University), New Orleans, USA

- 2021: **Data Manipulation with pandas**, Datacamp, Online, [See certificate of completion](certificate_python4.pdf) 

- 2021: **Introduction to Shell**, Udemy, Online, [See certificate of completion](certificate_python3.pdf) 

- 2021: **Intermediate Python**, Udemy, Online, [See certificate of completion](certificate_python2.pdf) 

- 2021: **Introduction to Python**, Udemy, Online, [See certificate of completion](certificate_python1.pdf) 

- 2021: **Introduction to Time Series Analysis and Forecasting in R**, Udemy, Online, [See certificate of completion](https://www.udemy.com/certificate/UC-bd146d69-9c75-45ab-8542-92a1796d65a1/)

- 2021: **R Programming for Statistics and Data Science 2021**, Udemy, Online, [See certificate of completion](https://www.udemy.com/certificate/UC-017e4eeb-b45b-4718-83de-d3ba951c654f/)

- 2021: **Applied Statistical Modeling for Data Analysis in R**, Udemy, Online, [See certificate of completion](https://www.udemy.com/certificate/UC-bcc89c9c-7a42-43c1-a79b-cadc290e4109/)

- 2021: **Complete Google Earth Engine for Remote Sensing & GIS**, Udemy, Online, [See certificate of completion](https://www.udemy.com/certificate/UC-39582869-fc1d-497e-99f3-7b1ecab7c982/)

- 2020: **Using process-based models to simulate the soil-plant-atmosphere system (STICS & MAESPA models)**, Remi Vezy, Olivier Roupsard & Guerric le Maire (Cirad), Dakar and Online

- 2019: **Design of experimental databases for modeling in STICS**, Michel Giner (CIRAD), Dakar, Senegal

- 2016: **Drone Setup and Usage for Park Conservation**, Abdelaziz Lawani (Eastern Kentucky University), Tanguiéta, Benin

---

### Leadership, service and community engagement 🤝

- Since 2022: **Member of European Geosciences Union**, Vienna, Austria

- 2021: **Member of American Geophysical Union**, USA

- 2017: **Volunteer - reforestation campaign in Zogbodomey**, ONAB Zogbodomey, Benin

- 2017: **Member of the Young African Leaders Initiative**, (YALY) Network Dakar, Senegal

- 2015: **Volunteer - reforestation campaign in Djidja**, Forest Station of Abomey Djidja, Benin

- From 2014 to 2016: **Children's instructor on biblical studies** at MEF (Mission Evangélique de la Foi) Church Kandi, Benin
