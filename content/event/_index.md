<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Photos Collections</title>
  
  <style>
    #description {
      color: grey;
      font-size: 1.1em;
      font-weight: bold;
      text-align: center;
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
</head>
<body>

<div>
  <p id="description">Photos collections</p>
  <p id="toggle-button" onclick="toggleTOC()">Table of Contents <span id="arrow">➤</span></p>
  <div id="toc">
    <ul>
      <li><a href="#new-orleans-usa">🇺🇸 New Orleans, USA</a></li>
      <li><a href="#vienna-austria">🇦🇹 Vienna, Austria</a></li>
      <li><a href="#hautes-pyrenees-france">🏔 Hautes Pyrénées, France</a></li>
      <li><a href="#toulouse-france">🏛 Toulouse, France</a></li>
      <li><a href="#paris-france">🗼 Paris, France</a></li>
      <li><a href="#montpellier-france">🌳 Montpellier, France</a></li>
      <li><a href="#strasbourg-france">🏰 Strasbourg, France</a></li>
      <li><a href="#niamey-niger">🇳🇪 Niamey, Niger</a></li>
      <li><a href="#dakar-senegal">🇸🇳 Dakar, Senegal</a></li>
      <li><a href="#cotonou-benin">🇧🇯 Cotonou, Benin</a></li>
      <li><a href="#grand-popo-benin">🐢 Grand-popo, Benin</a></li>
    </ul>
  </div>
</div>

---

<section id="new-orleans-usa">
  <h2>New Orleans - USA</h2>
  <figure>
    <img src="IMG_5225.jpg" alt="Mammoth teeth from Alaska displayed at AGU 2021">
    <figcaption>Mammoth teeth from Alaska displayed at AGU 2021</figcaption>
  </figure>
  <figure>
    <img src="IMG_5352.jpg" alt="The National WWII Museum">
    <figcaption>The National WWII Museum</figcaption>
  </figure>
</section>

---

<section id="vienna-austria">
  <h2>Vienna - Austria</h2>
  <figure>
    <img src="presentation.jpg" alt="Presenting at EGU 2022">
    <figcaption>Presenting at EGU 2022</figcaption>
  </figure>
  <figure>
    <img src="mus.JPG" alt="Schönbrunn Palace">
    <figcaption>Schönbrunn Palace</figcaption>
  </figure>
  <figure>
    <img src="IMG_9762.jpg" alt="St. Stephen's Cathedral">
    <figcaption>St. Stephen's Cathedral</figcaption>
  </figure>
</section>

---

<section id="hautes-pyrenees-france">
  <h2>Hautes Pyrénées - France</h2>
  <figure>
    <img src="IMG_3832.JPG" alt="Visiting the research station of the Pic du Midi, Observatoire Midi-Pyrénées">
    <figcaption>Visiting the research station of the Pic du Midi, Observatoire Midi-Pyrénées</figcaption>
  </figure>
  <figure>
    <img src="IMG_3934.JPG" alt="The summits at Pic du Midi">
    <figcaption>The summits at Pic du Midi</figcaption>
  </figure>
</section>

<section id="toulouse-france">
  <h2>Toulouse - France</h2>
  <figure>
    <img src="IMG_6532.jpg" alt="Long Ma at La Halle de La Machine">
    <figcaption>Long Ma at La Halle de La Machine</figcaption>
  </figure>
</section>

<section id="paris-france">
  <h2>Paris - France</h2>
  <figure>
    <img src="IMG_4275.JPG" alt="Musée du Louvre">
    <figcaption>Musée du Louvre</figcaption>
  </figure>
</section>

<section id="montpellier-france">
  <h2>Montpellier - France</h2>
  <figure>
    <img src="pye.jpg" alt="Promenade du Peyrou">
    <figcaption>Promenade du Peyrou</figcaption>
  </figure>
</section>

<section id="strasbourg-france">
  <h2>Strasbourg - France</h2>
  <figure>
    <img src="stra1.jpg" alt="A photograph of a building">
    <figcaption>A photograph of a building</figcaption>
  </figure>
  <figure>
    <img src="stra2.jpg" alt="A bee enjoying a flower's nectar">
    <figcaption>A bee enjoying a flower's nectar</figcaption>
  </figure>
</section>

---

<section id="niamey-niger">
  <h2>Niamey - Niger</h2>
  <figure>
    <img src="niger.jpg" alt="Skeleton of a dinosaur at Diori Hamani International Airport">
    <figcaption>Skeleton of a dinosaur at Diori Hamani International Airport</figcaption>
  </figure>
</section>

---

<section id="dakar-senegal">
  <h2>Dakar - Senegal</h2>
  <figure>
    <img src="dakar.jpg" alt="Monument de la Renaissance africaine">
    <figcaption>Monument de la Renaissance africaine</figcaption>
  </figure>
  <figure>
    <img src="dkr.jpg" alt="Representations of diverse cultures inside the African Renaissance Monument">
    <figcaption>Representations of diverse cultures inside the African Renaissance Monument</figcaption>
  </figure>
</section>

---

<section id="cotonou-benin">
  <h2>Cotonou - Benin</h2>
  <figure>
    <img src="IMG_7798.jpg" alt="Place de l'amazone">
    <figcaption>Place de l'amazone</figcaption>
  </figure>
</section>

<section id="grand-popo-benin">
  <h2>Grand-popo - Benin</h2>
  <figure>
    <img src="IMG_7874.jpg" alt="A small marine turtle">
    <figcaption>A small marine turtle</figcaption>
  </figure>
</section>

---

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

</body>
</html>
