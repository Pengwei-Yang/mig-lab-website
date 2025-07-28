---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

We are continuously recruiting postdoctoral researchers, Ph.D., and Master's students. If you are interested, please send an email to gqwang0420@uestc.edu.cn and cc gqwang0420@hotmail.com.


<link rel="stylesheet" href="https://unpkg.com/leaflet/dist/leaflet.css" />
<script src="https://unpkg.com/leaflet/dist/leaflet.js"></script>

<div id="map" style="height: 500px;"></div>

<script>
  var map = L.map('map').setView([30.7495247, 103.9220401], 17);

  L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
    attribution: '&copy; OpenStreetMap contributors'
  }).addTo(map);

  L.marker([30.7495247, 103.9220401])
    .addTo(map)
    .bindPopup("国际创新中心")
    .openPopup();
</script>


