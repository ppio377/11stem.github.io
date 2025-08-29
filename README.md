<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Science Learning Hub</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #0d1117;
      color: #e6edf3;
      margin: 0;
      padding: 0;
    }
    header {
      background: #161b22;
      padding: 1rem;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 1.5rem;
      color: #58a6ff;
    }
    .search-box {
      margin-top: 1rem;
    }
    input[type="text"] {
      width: 80%;
      padding: 0.5rem;
      border-radius: 5px;
      border: none;
    }
    button {
      padding: 0.5rem 1rem;
      background: #238636;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background: #2ea043;
    }
    .container {
      padding: 1rem;
    }
    .chapter {
      background: #161b22;
      border-radius: 10px;
      margin-bottom: 1rem;
      box-shadow: 0 0 10px rgba(0,0,0,0.3);
      overflow: hidden;
    }
    .chapter h2 {
      margin: 0;
      padding: 1rem;
      background: #21262d;
      cursor: pointer;
      font-size: 1.2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .chapter h2:hover {
      background: #30363d;
    }
    .chev {
      display: inline-block;
      transition: transform 0.3s;
    }
    .chapter.open .chev {
      transform: rotate(90deg);
    }
    .content {
      display: none;
      padding: 1rem;
    }
    .chapter.open .content {
      display: block;
    }
    iframe {
      width: 100%;
      aspect-ratio: 16/9;
      border-radius: 10px;
      margin: 1rem 0;
    }
    ul {
      padding-left: 1.2rem;
    }
    mark {
      background: #ffdd33;
      color: black;
      padding: 0 2px;
      border-radius: 3px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Grade 11-STEM</h1>
    <div class="search-box">
      <input type="text" id="search" placeholder="Search topics..." onkeyup="searchContent()">
      <button onclick="searchContent()">Search</button>
    </div>
  </header>

  <div class="container">

    <!-- Chapter 1 -->
    <section class="chapter">
      <h2 onclick="toggleChapter(this)">Chapter 1: Introduction & Evidence <span class="chev">▶</span></h2>
      <div class="content">
        <h3>A. Introduction to Matter</h3>
        <p>Matter is anything with mass and volume. It includes solids, liquids, gases, and plasma.</p>
        <ul>
          <li><b>Mass:</b> amount of matter in an object.</li>
          <li><b>Volume:</b> space occupied by matter.</li>
          <li><b>Occupies Space:</b> matter always takes up space.</li>
        </ul>
        <iframe src="https://www.youtube.com/embed/QQsybALJoew" allowfullscreen></iframe>

        <h3>B. Historical Development</h3>
        <p>Democritus proposed "atomos". Dalton gave the first atomic theory. Robert Brown observed Brownian Motion, later explained by Einstein. These led to the modern atomic theory.</p>
        <iframe src="https://www.youtube.com/embed/9WNFwOqb_24" allowfullscreen></iframe>

        <h3>C. Nature of Particles</h3>
        <ul>
          <li>Tiny and invisible to the naked eye</li>
          <li>Always moving</li>
          <li>Spaces exist between particles</li>
          <li>Collisions and forces of attraction occur</li>
        </ul>
        <iframe src="https://www.youtube.com/embed/npv74D2MO6Q" allowfullscreen></iframe>
      </div>
    </section>

    <!-- Chapter 2 -->
    <section class="chapter">
      <h2 onclick="toggleChapter(this)">Chapter 2: Evidence & Kinetic Molecular Theory <span class="chev">▶</span></h2>
      <div class="content">
        <h3>D. Evidence Supporting PNM</h3>
        <ul>
          <li>Brownian Motion (pollen in water)</li>
          <li>Diffusion (perfume in air, ink in water)</li>
          <li>Osmosis (raisin swelling in water)</li>
          <li>Gas Compression (syringe example)</li>
        </ul>
        <iframe src="https://www.youtube.com/embed/EkToa-7tXnw" allowfullscreen></iframe>

        <h3>E. Kinetic Molecular Theory</h3>
        <ul>
          <li>Particles are in constant random motion</li>
          <li>Collisions are elastic</li>
          <li>Volume of particles negligible compared to container</li>
          <li>Higher temperature = faster motion</li>
        </ul>
        <iframe src="https://www.youtube.com/embed/o3f_VJ87Df0" allowfullscreen></iframe>
      </div>
    </section>

    <!-- Chapter 3 -->
    <section class="chapter">
      <h2 onclick="toggleChapter(this)">Chapter 3: States & Changes of Matter <span class="chev">▶</span></h2>
      <div class="content">
        <h3>F. States of Matter</h3>
        <ul>
          <li><b>Solid:</b> tightly packed particles, fixed shape</li>
          <li><b>Liquid:</b> particles close but can flow</li>
          <li><b>Gas:</b> particles far apart, free movement</li>
          <li><b>Plasma:</b> ionized gas</li>
          <li><b>BEC:</b> super-particle state near absolute zero</li>
        </ul>
        <iframe src="https://www.youtube.com/embed/184eP_KuXek" allowfullscreen></iframe>

        <h3>G. Changes of State</h3>
        <p>Melting, freezing, evaporation, condensation, sublimation, deposition. Explained by energy absorption/release.</p>
        <p><b>Endothermic:</b> absorbs heat. <b>Exothermic:</b> releases heat.</p>
        <iframe src="https://www.youtube.com/embed/oIYyeFhZ7eE" allowfullscreen></iframe>
      </div>
    </section>

    <!-- Chapter 4 -->
    <section class="chapter">
      <h2 onclick="toggleChapter(this)">Chapter 4: Gas Laws, Mixtures & Intermolecular Forces <span class="chev">▶</span></h2>
      <div class="content">
        <h3>H. Gas Laws</h3>
        <p>These laws describe relationships between pressure, volume, temperature, and number of gas particles.</p>
        <p><b>Boyle’s Law:</b> P ∝ 1/V at constant T</p>
        <iframe src="https://www.youtube.com/embed/YQmv272-4yU" allowfullscreen></iframe>

        <p><b>Charles’s Law:</b> V ∝ T at constant P</p>
        <iframe src="https://www.youtube.com/embed/twCcSsHmMgI" allowfullscreen></iframe>

        <p><b>Gay-Lussac’s Law:</b> P ∝ T at constant V</p>
        <iframe src="https://www.youtube.com/embed/f3lthm64J5M" allowfullscreen></iframe>

        <p><b>Avogadro’s Law:</b> V ∝ n at constant P, T</p>
        <iframe src="https://www.youtube.com/embed/QafV2Zms_Nw" allowfullscreen></iframe>

        <p><b>Ideal Gas Law:</b> PV = nRT</p>
        <iframe src="https://www.youtube.com/embed/robEY-idcLU" allowfullscreen></iframe>

        <h3>I. Mixtures and Solutions</h3>
        <p>Solutions are homogeneous mixtures of solute and solvent. Solubility depends on temperature, pressure, and polarity.</p>
        <iframe src="https://www.youtube.com/embed/1MVpXOoEcys" allowfullscreen></iframe>

        <h3>J. Intermolecular Forces</h3>
        <p>These forces affect boiling point, melting point, and solubility.</p>
        <ul>
          <li>Van der Waals forces</li>
          <li>Dipole–Dipole interactions</li>
          <li>Hydrogen bonding</li>
          <li>Ion–Dipole interactions</li>
        </ul>
        <iframe src="https://www.youtube.com/embed/08kGgrqaZXA" allowfullscreen></iframe>
      </div>
    </section>

    <!-- Chapter 5 -->
    <section class="chapter">
      <h2 onclick="toggleChapter(this)">Chapter 5: References <span class="chev">▶</span></h2>
      <div class="content">
        <p><b>Video References:</b></p>
        <ul>
          <li>Introduction to Matter – <i>Socratica Kids</i>. <a href="https://youtu.be/QQsybALJoew" target="_blank">Watch here</a></li>
          <li>Historical Development – <i>FuseSchool</i>. <a href="https://youtu.be/9WNFwOqb_24" target="_blank">Watch here</a></li>
          <li>Nature of Particles – <i>Smile and Learn</i>. <a href="https://youtu.be/npv74D2MO6Q" target="_blank">Watch here</a></li>
          <li>Evidence Supporting PNM – <i>Free Animated Education</i>. <a href="https://youtu.be/EkToa-7tXnw" target="_blank">Watch here</a></li>
          <li>Kinetic Molecular Theory – <i>Manocha Academy</i>. <a href="https://youtu.be/o3f_VJ87Df0" target="_blank">Watch here</a></li>
          <li>States of Matter – <i>Smart Learning for All</i>. <a href="https://youtu.be/184eP_KuXek" target="_blank">Watch here</a></li>
          <li>Changes of State – <i>Socratica</i>. <a href="https://youtu.be/oIYyeFhZ7eE" target="_blank">Watch here</a></li>
          <li>Boyle’s Law – <i>FuseSchool</i>. <a href="https://youtu.be/YQmv272-4yU" target="_blank">Watch here</a></li>
          <li>Charles’s Law – <i>Bozeman Science</i>. <a href="https://youtu.be/twCcSsHmMgI" target="_blank">Watch here</a></li>
          <li>Gay-Lussac’s Law – <i>Khan Academy</i>. <a href="https://youtu.be/f3lthm64J5M" target="_blank">Watch here</a></li>
          <li>Avogadro’s Law – <i>Simple Science</i>. <a href="https://youtu.be/QafV2Zms_Nw" target="_blank">Watch here</a></li>
          <li>Ideal Gas Law – <i>Tyler DeWitt</i>. <a href="https://youtu.be/robEY-idcLU" target="_blank">Watch here</a></li>
          <li>Mixtures & Solutions – <i>SciShow Kids</i>. <a href="https://youtu.be/1MVpXOoEcys" target="_blank">Watch here</a></li>
          <li>Intermolecular Forces – <i>CrashCourse</i>. <a href="https://youtu.be/08kGgrqaZXA" target="_blank">Watch here</a></li>
        </ul>
      </div>
    </section>

  </div>

  <script>
    function toggleChapter(el) {
      el.parentElement.classList.toggle("open");
    }

    function removeHighlights(element) {
      const marks = element.querySelectorAll("mark");
      marks.forEach(mark => {
        mark.replaceWith(document.createTextNode(mark.textContent));
      });
    }

    function highlightText(element, query) {
      if (!query) return;
      const regex = new RegExp(`(${query})`, "gi");
      element.childNodes.forEach(node => {
        if (node.nodeType === 3) {
          const replaced = node.textContent.replace(regex, "<mark>$1</mark>");
          if (replaced !== node.textContent) {
            const span = document.createElement("span");
            span.innerHTML = replaced;
            node.replaceWith(span);
          }
        } else {
          highlightText(node, query);
        }
      });
    }

    function searchContent() {
      let input = document.getElementById("search").value.toLowerCase();
      let chapters = document.querySelectorAll(".chapter");

      chapters.forEach(chap => {
        removeHighlights(chap);
        if (!input) {
          chap.style.display = "block";
        } else if (chap.innerText.toLowerCase().includes(input)) {
          chap.style.display = "block";
          highlightText(chap, input);
          chap.classList.add("open");
        } else {
          chap.style.display = "none";
        }
      });
    }
  </script>
</body>
</html>
