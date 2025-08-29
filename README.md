

<html>
<head>
<title>AR.js Location-Based</title>
<script src="https://aframe.io/releases/1.3.0/aframe.min.js"></script>
<script src="https://raw.githack.com/AR-js-org/AR.js/3.4.5/three.js/build/ar-threex-location-only.js"></script>
<script src="https://raw.githack.com/AR-js-org/AR.js/3.4.5/aframe/build/aframe-ar.js"></script>
</head>
<body>
<a-scene vr-mode-ui='enabled: false' arjs='sourceType: webcam; videoTexture: true; debugUIEnabled: false' renderer='antialias: true; alpha: true'>
    <a-camera gps-new-camera='gpsMinDistance: 5'></a-camera>
    <a-entity gltf-model="url" gps-new-entity-place="latitude: TU_LATITUD; longitude: TU_LONGITUD" scale="10 10 10"></a-entity>
</a-scene>
</body>
</html>
