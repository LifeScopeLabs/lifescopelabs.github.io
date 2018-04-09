# LIFESCOPE-XR
This repo contains a series of AR/VR Views written to extend lifescope-app codebase as JS/Vue/Nuxt plugins.

# Augmented Reality

### LIFESCOPE AR Marker
![marker]

### LIFESCOPE AR Marker Pattern file. 

Notice how the pattern encodes the variance of the bitmap
![patternar]

## 1. AR Floor Topography Map (development phase, medium priority)

![armap][armap]
![armap][armap2]

### Requirements
- **MVP**: See a trail of gateways left behind from LIFESCOPE location objects.
- Shows the current location (GPS) tile and database LIFESCOPE objects using markers.
- See location of other lifLIFESCOPEescope objects.
- See geo-polygons drawn from LIFESCOPE places objects.
- Able to select locations, zoom, objects
- Ability to see AR Globe (See VR Globe)
- Able to work without marker. Using compass, accelerometer, gyroscope, camera (slam), etc…
- Able to see other LIFESCOPE users with permissions.

### Dependencies
- Vue/Nuxt compatible
- [AR.JS](https://github.com/jeromeetienne/AR.js/tree/master/aframe/demos/demo-mapbox)
- [AFrame (0.8+)](https://aframe.io/)
- [Mapbox (0.44.1+)](https://www.mapbox.com/mapbox-gl-js/api/)

### Examples
- [AR.JS Mapbox with marker](https://github.com/jeromeetienne/AR.js/tree/master/aframe/demos/demo-mapbox)
- [AR.JS markerless](https://github.com/1d10t/test)
- [Web Geo adapter (De-noise web GPS data](https://github.com/Esri/html5-geolocation-tool-js/blob/master/js/GeolocationHelper.js)
- [Marker Maker](https://jeromeetienne.github.io/AR.js/three.js/examples/marker-training/examples/generator.html)
- [BitScoop Marker](https://github.com/LifeScopeLabs/lifescopelabs.github.io/tree/master/assets/xr)
- [Networked AFrame](https://github.com/networked-aframe/networked-aframe#more-examples)

## 2. Phone AR Gateways (concept phase, low priority)

![argateway]

### Requirements
- **MVP**: Shows AR gateways around the current location (GPS) from the LIFESCOPE database
- Able to select gateways, zoom, objects
- Able to see friends

### Dependencies
- Vue/Nuxt compatible
- [AR.JS](https://github.com/jeromeetienne/AR.js/tree/master/aframe/demos/demo-mapbox)
- [AFrame (0.8+)](https://aframe.io/)
- [Mapbox (0.44.1+)](https://www.mapbox.com/mapbox-gl-js/api/)

### Examples
- [AR.JS markerless](https://github.com/1d10t/test)
- [Web Geo adapter (De-noise web GPS data](https://github.com/Esri/html5-geolocation-tool-js/blob/master/js/GeolocationHelper.js)
- [Marker Maker](https://jeromeetienne.github.io/AR.js/three.js/examples/marker-training/examples/generator.html)
- [BitScoop Marker](https://github.com/LifeScopeLabs/lifescopelabs.github.io/tree/master/assets/xr)
- [Networked AFrame](https://github.com/networked-aframe/networked-aframe#more-examples)

## 3. Facial recognition (concept phase, low priority)
## Requirements
- **MVP**: Able to recognize faces from LIFESCOPE data
- Capture store photo/video/location/speech of “AR encounter” in LIFESCOPE api
Dependencies
 - Vue/Nuxt compatible
Examples
- [JS Facial tracking experiment](https://tastenkunst.github.io/brfv4_javascript_examples/)

# Virtual Reality

## 1. Globe of LIFESCOPE trails (development phase, medium priority)

![vrglobe]

![vrmapbox]

### Requirements
- MVP: Shows the current location (GPS) on globe and database LIFESCOPE objects using marker
- Able to select locations, zoom, objects
- Able to see friends

### Dependencies
- Vue/Nuxt compatible
- [AR.JS](https://github.com/jeromeetienne/AR.js/tree/master/aframe/demos/demo-mapbox)
- [AFrame (0.8+)](https://aframe.io/)
- [Mapbox (0.44.1+)](https://www.mapbox.com/mapbox-gl-js/api/)

### Examples
- [Aframe Earth](https://github.com/leemark/aframe-earth)
- [Networked AFrame](https://github.com/networked-aframe/networked-aframe#more-examples)

## 2. Infinite procedural walls (concept phase, low priority)

![infinitewalls]

### Requirements
- **MVP**: Show an infinite "gallery" of content from your lifescope data.
- Able to sort, search, curate, modify content shown.
- Able to draw in the gallery.
- Able to see friends.

### Dependencies
- Vue/Nuxt compatible
- [AR.JS](https://github.com/jeromeetienne/AR.js/tree/master/aframe/demos/demo-mapbox)
- [AFrame (0.8+)](https://aframe.io/)
- [GURI VR](https://gurivr.com/)

### Examples
- [AFrame Room Component](https://github.com/omgitsraven/aframe-room-component)
- [3d.io Room Objects](https://3d.io/docs/api/1/aframe-components.html)
- [Networked AFrame](https://github.com/networked-aframe/networked-aframe#more-examples)

## 3. Memory palace (concept phase, low priority)

![proceduralvr1]

![proceduralvr2]

### Requirements
- **MVP**: Show an infinite "gallery" of content from your lifescope data.
- Able to sort, search, curate, modify content shown.
- Able to draw in the gallery.
- Able to see friends.

### Dependencies
- Vue/Nuxt compatible
- [AR.JS](https://github.com/jeromeetienne/AR.js/tree/master/aframe/demos/demo-mapbox)
- [AFrame (0.8+)](https://aframe.io/)
- [GURI VR](https://gurivr.com/)

### Examples
- [AFrame Room Component](https://github.com/omgitsraven/aframe-room-component)
- [3d.io Room Objects](https://3d.io/docs/api/1/aframe-components.html)
- [Networked AFrame](https://github.com/networked-aframe/networked-aframe#more-examples)

# BitScoop WebXR Examples

## [BitScoop VR Social Login Demo](https://github.com/mrhegemon/bitscoop-vr-demo)

Social Wars in React VR. A VR demo using the BitScoop Platform for Social Login. Filled with demo data.

## BitScoop AR Marker
![markerbs]

BitScoop Marker Pattern File. Notice how the bitmap matches the file.
![patternarbs]

[armap]:https://lifescopelabs.github.io/assets/maps/ar-phone-topo-mapbox.jpg
[armap2]:https://lifescopelabs.github.io/assets/maps/ar-phone-topo-mapbox2.jpg
[patternar]:https://lifescopelabs.github.io/assets/xr/marker-patt-file.png
[marker]:https://lifescopelabs.github.io/assets/xr/marker.png
[patternarbs]:https://lifescopelabs.github.io/assets/xr/bitscoop-marker-patt-file.png
[markerbs]:https://lifescopelabs.github.io/assets/xr/bitscoop-marker.png
[vrglobe]:https://lifescopelabs.github.io/assets/xr/arglobe.gif
[vrmapbox]:https://lifescopelabs.github.io/assets/wireframes/vr-maps-aframe-mapbox.png
[argateway]:https://lifescopelabs.github.io/assets/wireframes/ar-phone-gateway.png
[infinitewalls]:https://lifescopelabs.github.io/assets/wireframes/PlayCanvasLifeScopeGalleryWireframes.png
[proceduralvr1]:https://lifescopelabs.github.io/assets/wireframes/ProceduralAFrame1.png
[proceduralvr2]:https://lifescopelabs.github.io/assets/wireframes/ProceduralAFrame2.png
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIwMDIwOTQ4NzYsMTY3Mjc5NTE4OSwtOT
Y5MzkwMzI2LC0yODc1MDcyNzRdfQ==
-->