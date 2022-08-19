---
layout: page-fullwidth
title: "Map"
subheadline: ""
teaser: ""
permalink: "/our_work/map"
header:
    image_fullwidth: "header_banner_larger.jpg"
---
<p>Our immersive, interactive map aggregates two-dimensional and 360° representations of the people, places, and events that constitute Black Philly in the past and present.</p>

<p>Navigate your way through the city using various map overlays and search filters, which allow you to filter map points according to Philadelphia neighborhoods, time periods, kinds of locations, and themes. You can also filter according to whether a site is “endangered,” or at risk of closure.</p>

<p>If you hover over a map point, a small pop-up window will preview the location details. If you click on a map point, an information panel will emerge that provides a longer description of the site, information sources, and media related to the site, such as: images, audio, video, and 360° images and videos.</p>

<h2>Google My Maps</h2>

<br>

<iframe src="https://www.google.com/maps/d/u/0/embed?mid=1HogSzzYyS0fDeRtxboVDvxJ8cHUTM2fI&ehbc=2E312F" width="100%" height="480" frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe>

<h2>Leaflet.js</h2>

<br>

<div id="map" style="width: 100%; height: 400px;"></div>
<script>
    var map = L.map('map').setView([40.02277338780419, -75.15872603120033], 13);

    L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
    maxZoom: 19,
    attribution: '© OpenStreetMap'
    }).addTo(map);

</script>
