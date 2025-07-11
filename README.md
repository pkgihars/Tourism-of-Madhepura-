
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Madhepura Tourism</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f5f6fa;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #2e86de;
      color: white;
      padding: 20px;
      text-align: center;
    }

    .container {
      max-width: 1000px;
      margin: 20px auto;
      padding: 0 20px;
    }

    .place {
      background-color: white;
      margin-bottom: 20px;
      padding: 15px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    .place h2 {
      margin-top: 0;
      color: #2e86de;
    }

    .place img {
      width: 100%;
      max-height: 250px;
      object-fit: cover;
      border-radius: 6px;
      margin-bottom: 10px;
    }

    .map-button {
      display: inline-block;
      margin-top: 10px;
      padding: 8px 12px;
      background-color: #27ae60;
      color: white;
      text-decoration: none;
      border-radius: 4px;
      font-size: 14px;
    }

    footer {
      text-align: center;
      background-color: #2e86de;
      color: white;
      padding: 15px 0;
      margin-top: 40px;
    }
  </style>
</head>
<body>
<button id="installApp" style="padding:10px 20px; font-size:16px;">📲 Install App</button>

<script>
  let deferredPrompt;

  window.addEventListener('beforeinstallprompt', (e) => {
    e.preventDefault();
    deferredPrompt = e;
    document.getElementById('installApp').style.display = 'inline-block';
  });

  document.getElementById('installApp').addEventListener('click', () => {
    if (deferredPrompt) {
      deferredPrompt.prompt();
      deferredPrompt.userChoice.then(choice => {
        if (choice.outcome === 'accepted') {
          console.log('App installed');
        }
        deferredPrompt = null;
      });
    }
  });
</script>

<header>
  <h1>Tourist Places of Madhepura, Bihar</h1>
  <p>Explore the culture, heritage, and spirituality of Madhepura</p>
</header>

<div class="container">

  <!-- 1 -->
  <div class="place">
    <h2>Singheshwar Dham</h2>
    <img src="https://via.placeholder.com/800x300?text=Singheshwar+Dham" alt="Singheshwar Dham">
    <p>A famous religious site dedicated to Lord Shiva. Attracts devotees, especially during Maha Shivratri Mela.</p>
    <a class="map-button" href="https://www.google.com/maps/place/Singheshwar+Dham/" target="_blank">View on Google Maps</a>
  </div>

  <!-- 2 -->
  <div class="place">
    <h2>Kosi River Banks</h2>
    <img src="https://via.placeholder.com/800x300?text=Kosi+River" alt="Kosi River">
    <p>The scenic beauty of the Kosi River and its surroundings offer a peaceful and natural escape.</p>
    <a class="map-button" href="https://www.google.com/maps/search/Kosi+river+madhepura/" target="_blank">View on Google Maps</a>
  </div>

  <!-- 3 -->
  <div class="place">
    <h2>Bhimnagar (Kosi Barrage)</h2>
    <img src="https://via.placeholder.com/800x300?text=Kosi+Barrage" alt="Kosi Barrage">
    <p>Kosi Barrage near Bhimnagar is a major dam near the Nepal border with engineering and scenic importance.</p>
    <a class="map-button" href="https://www.google.com/maps/place/Kosi+Barrage,+Bhimnagar/" target="_blank">View on Google Maps</a>
  </div>

  <!-- 4 -->
  <div class="place">
    <h2>Uda Kishanganj</h2>
    <img src="https://via.placeholder.com/800x300?text=Uda+Kishanganj" alt="Uda Kishanganj">
    <p>Historic village known for old temples and rural heritage of the region.</p>
    <a class="map-button" href="https://www.google.com/maps/place/Uda+Kishanganj/" target="_blank">View on Google Maps</a>
  </div>

  <!-- 5 -->
  <div class="place">
    <h2>Durga Sthan Madhepura</h2>
    <img src="https://via.placeholder.com/800x300?text=Durga+Sthan" alt="Durga Sthan">
    <p>A well-known temple in Madhepura town, visited frequently during Navratri.</p>
    <a class="map-button" href="https://www.google.com/maps/place/Durga+Sthan+Madhepura/" target="_blank">View on Google Maps</a>
  </div>

  <!-- 6 -->
  <div class="place">
    <h2>Rambagh Palace (Heritage Site)</h2>
    <img src="https://via.placeholder.com/800x300?text=Rambagh+Palace" alt="Rambagh Palace">
    <p>A historic structure symbolizing the region’s royal past. Needs restoration.</p>
    <a class="map-button" href="https://www.google.com/maps/search/Rambagh+Palace+Madhepura/" target="_blank">View on Google Maps</a>
  </div>

  <!-- 7 -->
  <div class="place">
    <h2>Chhath Puja Ghats</h2>
    <img src="https://via.placeholder.com/800x300?text=Chhath+Ghat" alt="Chhath Ghat">
    <p>Popular during Chhath Puja where people offer prayers to the Sun God at riversides and ponds.</p>
    <a class="map-button" href="https://www.google.com/maps/search/Chhath+Ghat+Madhepura/" target="_blank">View on Google Maps</a>
  </div>

  <!-- 8 -->
  <div class="place">
    <h2>Parasmani Temple</h2>
    <img src="https://via.placeholder.com/800x300?text=Parasmani+Temple" alt="Parasmani Temple">
    <p>A serene and spiritual destination for local devotees outside the town area.</p>
    <a class="map-button" href="https://www.google.com/maps/search/Parasmani+Temple+Madhepura/" target="_blank">View on Google Maps</a>
  </div>

  <!-- 9 -->
  <div class="place">
    <h2>Vishnu Mandir, Madhepura</h2>
    <img src="https://via.placeholder.com/800x300?text=Vishnu+Mandir" alt="Vishnu Mandir">
    <p>Dedicated to Lord Vishnu, this temple is a peaceful spot in Madhepura town.</p>
    <a class="map-button" href="https://www.google.com/maps/search/Vishnu+Mandir+Madhepura/" target="_blank">View on Google Maps</a>
  </div>

  <!-- 10 -->
  <div class="place">
    <h2>Teliya Pokhar</h2>
    <img src="https://via.placeholder.com/800x300?text=Teliya+Pokhar" alt="Teliya Pokhar">
    <p>Historic pond surrounded by temples, popular during local festivals.</p>
    <a class="map-button" href="https://www.google.com/maps/search/Teliya+Pokhar+Madhepura/" target="_blank">View on Google Maps</a>
  </div>

  <!-- 11 -->
  <div class="place">
    <h2>Manokamna Temple, Alamnagar</h2>
    <img src="https://via.placeholder.com/800x300?text=Manokamna+Temple" alt="Manokamna Temple">
    <p>Devotees come here to fulfill wishes (manokamna), especially on auspicious days.</p>
    <a class="map-button" href="https://www.google.com/maps/search/Manokamna+Mandir+Alamnagar/" target="_blank">View on Google Maps</a>
  </div>

  <!-- 12 -->
  <div class="place">
    <h2>Sahugarh Fort (Ruins)</h2>
    <img src="https://via.placeholder.com/800x300?text=Sahugarh+Fort" alt="Sahugarh Fort">
    <p>Ruins of an old fort — a hidden gem for heritage lovers.</p>
    <a class="map-button" href="https://www.google.com/maps/search/Sahugarh+Fort+Madhepura/" target="_blank">View on Google Maps</a>
  </div>

  <!-- 13 -->
  <div class="place">
    <h2>Murliganj Market & Temple Area</h2>
    <img src="https://via.placeholder.com/800x300?text=Murliganj+Temples" alt="Murliganj Temples">
    <p>A lively town center with many small temples and cultural activity.</p>
    <a class="map-button" href="https://www.google.com/maps/place/Murliganj/" target="_blank">View on Google Maps</a>
  </div>

  <!-- 14 -->
  <div class="place">
    <h2>BNMU Campus Garden</h2>
    <img src="https://via.placeholder.com/800x300?text=BNMU+Campus" alt="BNMU Campus">
    <p>Bhupendra Narayan Mandal University’s campus offers a peaceful walking and studying area.</p>
    <a class="map-button" href="https://www.google.com/maps/place/BNMU+Madhepura/" target="_blank">View on Google Maps</a>
  </div>

  <!-- 15 -->
  <div class="place">
    <h2>Puraini Ghat</h2>
    <img src="https://via.placeholder.com/800x300?text=Puraini+Ghat" alt="Puraini Ghat">
    <p>Less crowded ghat used during Chhath and for peaceful riverside views.</p>
    <a class="map-button" href="https://www.google.com/maps/place/Puraini+Ghat/" target="_blank">View on Google Maps</a>
  </div>

</div>

<footer>
  &copy; 2025 Madhepura Tourism | Designed with ❤️
</footer>

</body>
</html>
