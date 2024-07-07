---
## Configure header of page
text_align_right: false
show_title_as_headline: false
toc: true
---

<style>
#description {
  color: grey;
  font-size: 1.1em;
  font-weight: bold;
  text-align: center
}
#toc {
  display: none;
  margin-top: 10px;
  padding: 10px;
  border: 2px solid #f0f0f0;
  background-color: #f0f0f0;
  font-size: 0.9em;
}
#toggle-button {
  cursor: pointer;
  color: blue;
  text-decoration: underline;
  display: inline-flex;
  align-items: center;
  font-weight: bold;
}
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
      <li><a href="#education-">🎓 Education</a></li>
      <li><a href="#experience-">💼 Experience</a></li>
      <li><a href="#training-">📚 Training</a></li>
      <li><a href="#skills-">🎯 Skills</a></li>
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
I'm Yélognissè Frédi Agbohessou from Benin. I'm a research scientist with a love for history, nature, photography, and football (because who doesn't love a good game?). My research focuses on the application of modeling and spatial data science to address challenges in agroforestry, agronomy, and forestry. My work aims to tackle issues related to food security and the impact of climate change on ecosystems.

I am currently working as a postdoctoral researcher at [UMR Eco&Sols](https://www.umr-ecosols.fr/)/[Cirad](https://www.cirad.fr/en), focusing on modeling the impact of climatic stresses on the functioning of rubber trees (*Hevea brasiliensis*).

---

### Interests 🌿
- 🌳 Agroforestry
- 🌎 Ecological modeling
- 🌡️ Climate Change
- 🌱 Biogeosciences
- 🛰️ Remote sensing
- 🥗 Food security 
- 🌍 West Africa
- 🌏 South-East Asia

---

### Education 🎓
- **PhD in Ecology and Agroforestry** &#8729; Cheikh Anta Diop University &#8729; 2024
- **MSc in Agroforestry Ecology and Adaptation** &#8729; Cheikh Anta Diop University &#8729; 2020
- **BSc in Wildlife and Protected Area Management** &#8729; University of Parakou &#8729; 2016

---

### Experience 💼
- **Postdoctoral Researcher** &#8729; modeling the impact of climatic stresses on the functioning of rubber trees (*Hevea brasiliensis*) &#8729; *Cirad (Montpellier, France)* &#8729; ongoing
- **PhD Researcher** &#8729; Modeling greenhouse gas balance in agro-silvo-pastoral systems of the Sahel: from plot to landscape &#8729; *ISRA / LMI IESOL / Lero (Dakar, Senegal and Toulouse, France)* &#8729; 01/2021 - 03/2024
- **Internship in Agronomy/Remote Sensing/Biostatistics** &#8729; Using drones to upscale yield and land-equivalent-ratio (LER) from
plot to stand in an agro-silvo-pastoral system through a geostatistical-based method &#8729; *IRD / ISRA (Dakar, Senegal)* &#8729; 04/2019 - 12/2020
- **Forestry Technician** &#8729; Management of Teak (Tectona grandis) and Gmelina arborea plantations &#8729; *National Office of Wood (Bohicon, Benin)* &#8729; 02/2017 - 08/2018
- **Internship in Meteorology** &#8729; Introduction to tools for measuring meteorological parameters &#8729; *Asecna (Kandi, Benin)* &#8729; 04/2014 - 04/2014

---

### Training 📚
- **May 2023 to August 2023**: Online Course, Udemy Online - **Explore Data Science with Julia**, [See certificate](https://www.udemy.com/certificate/UC-464f0a38-4ab3-4906-97f1-6b354a5c8e71/)
- **May 2021 to July 2021**: Online Course, Udemy Online - **Introduction to Time Series Analysis and Forecasting in R**, [See certificate](https://www.udemy.com/certificate/UC-bd146d69-9c75-45ab-8542-92a1796d65a1/)
- **March 2021 to August 2021**: Online Course, Udemy Online - **R Programming for Statistics and Data Science 2021**, [See certificate](https://www.udemy.com/certificate/UC-017e4eeb-b45b-4718-83de-d3ba951c654f/)
- **January 2021 to February 2021**: Online Course, Udemy Online - **Applied Statistical Modeling for Data Analysis in R**: Complete guide to statistical data analysis & visualization for practical applications in R, [See certificate](https://www.udemy.com/certificate/UC-bcc89c9c-7a42-43c1-a79b-cadc290e4109/)
- **December 2020 to January 2021**: Online Course, Udemy Online - **Complete Google Earth Engine for Remote Sensing & GIS**: Hands-on training with real remote sensing and GIS data analysis with Google Earth Engine, [See certificate](https://www.udemy.com/certificate/UC-39582869-fc1d-497e-99f3-7b1ecab7c982/)
- **Since October 2020**: Online Course, CIRAD Dakar, Senegal - **STICS and MAESPA** (initialization, calibration, and simulations)
- **October 2019**: One-week training with Michel Giner (CIRAD) in Dakar, Senegal - **Design of experimental databases for modeling in STICS**: (1) Designing a database with Microsoft Access, (2) Importing/exporting data between Access and Excel, (3) Queries in Access


---

### Skills 🎯
<style>
table {
    width: 100%; /* Ensures the table takes full width */
    margin-left: auto;
    margin-right: auto;
    font-size: 17px; /* Adjust the size as needed */
}
</style>

<div style="margin: 0 auto; width: fit-content;">

|      🌟 **Skill**                | **Proficiency** |
|---------------------------------|-----------------|
| 📈 **Statistics**               | ██████████░░░░ | 70%
| 💻 **Programming**              | ███████░░░░░░░ | 50%
| 🗺️ **GIS**                     | ██████████░░░░ | 70%
| 🌳 **Ecology & Agroforestry**   | ██████████████░ | 90%
| 🧩 **Modelling**                | ██████████░░░░ | 70%
| 🗣️ **Scientific Communication**| ██████████░░░░ | 70%

</div>