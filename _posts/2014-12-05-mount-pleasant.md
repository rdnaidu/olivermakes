---
title: 'Mount Pleasant photowalk'
layout: contrast
option:
  - feature
  - map-meta
  - srcset
category: 'photo'
date: 2014-12-05 22:01
updated: 2014-12-05 01:28
drafted: 2014-11-14 22:01
unique-id: 2014-11-14:mount-pleasant
description: 'Photos from a neighborhood in Washington, DC; processed with VSCO Film 04.'
feature-description: 'These are some of my favorite photos from a walk around the Mount Pleasant neighborhood in January 2014, shot with a Fujifilm X-E2 and Fujinon XF35mmF1.4 R lens, re-processed with VSCO Film 04.'
image:
  - src: 2014-01-20-orange-leaves-olivermakes-ccbync.jpg
    alt: 'Backlit orange leaves'
    date: 2014-01-20
    camera: 'Fujifilm X-E2'
    lens: 'Fujinon XF35mmF1.4 R'
    focal: '35mm'
    aperture: 'f/5'
    shutter: '1/800'
    iso: 500
    location: 'Mount Pleasant, Washington DC'
    latitude: 38.9298
    longitude: -77.0438
    zoom: 16
    description: 'VSCO Film Kodak E200'
  - src: 2014-01-20-bark-close-olivermakes-ccbync.jpg
    alt: 'Close view of tree bark in a residential neighborhood'
    date: 2014-01-20
    camera: 'Fujifilm X-E2'
    lens: 'Fujinon XF35mmF1.4 R'
    focal: '35mm'
    aperture: 'f/5'
    shutter: '1/210'
    iso: 200
    location: 'Mount Pleasant, Washington DC'
    latitude: 38.9329
    longitude: -77.0413
    zoom: 16
    description: 'VSCO Film Kodak E200'
  - src: 2014-01-20-sidewalk-olivermakes-ccbync.jpg
    alt: 'Small green leaves growing from a rocky wall next to a sidewalk'
    date: 2014-01-20
    camera: 'Fujifilm X-E2'
    lens: 'Fujinon XF35mmF1.4 R'
    focal: '35mm'
    aperture: 'f/2.5'
    shutter: '1/640'
    iso: 200
    location: 'Mount Pleasant, Washington DC'
    latitude: 38.9298
    longitude: -77.0438
    zoom: 16
    description: 'VSCO Film Kodak E200'

---

<figure class="wide">
  <input type="radio" role="radio" name="shift0" class="shift-back" id="shift-back0" checked>
  <input type="radio" role="radio" name="shift0" class="shift-overlay" id="shift-overlay0">
  <input type="radio" role="radio" name="shift0" class="shift-map" id="shift-map0">
  <div class="container map-background" id="i0">
    <img
      src="{{ site.image-url }}/{{ page.image[0].src }}" 
      sizes="{{ site.wide-sizes }}"
      srcset="{% for srcset1440 in site.srcset1440 %}{{ site.image-url }}/{{ site.srcset1440[forloop.index0] }}/{{ page.image[0].src }} {{ site.srcset1440[forloop.index0] }}w{% if forloop.last == false %}, {% endif %}{% endfor %}"
       alt="{{ page.image[0].alt }}"
    >
    <label for="shift-back0" class="shift-back-label"></label>
    <label for="shift-overlay0" class="shift-overlay-label"></label>
    <div class="photo-meta overlay">
      <div class="camera-icon {% if page.image[0].camera contains 'iPhone 5S' %}icon-iphone5s{% elsif page.image[0].camera contains 'X-E2' %}icon-fxe2{% endif %}"></div>
      <ul class="camera-details">
        <li>Camera: {{ page.image[0].camera }}</li>
        <li>Lens: {{ page.image[0].lens }} at {{ page.image[0].focal }}</li>
        <li>Exposure: {{ page.image[0].aperture }} | {{ page.image[0].shutter }} s | ISO {{ page.image[0].iso }}</li>
        <li>Date: {{ page.image[0].date }}</li>
        <li>Location: {{ page.image[0].location }}</li>
      </ul>
      <label for="shift-map0" class="shift-map-label">View map{% include icon/location.html %}</label>
    </div>
  </div>
</figure>

<figure class="wide">
  <input type="radio" role="radio" name="shift1" class="shift-back" id="shift-back1">
  <input type="radio" role="radio" name="shift1" class="shift-overlay" id="shift-overlay1">
  <input type="radio" role="radio" name="shift1" class="shift-map" id="shift-map1">
  <div class="container map-background" id="i1">
    <img
      src="{{ site.image-url }}/{{ page.image[1].src }}" 
      sizes="{{ site.wide-sizes }}"
      srcset="{% for srcset1440 in site.srcset1440 %}{{ site.image-url }}/{{ site.srcset1440[forloop.index0] }}/{{ page.image[1].src }} {{ site.srcset1440[forloop.index0] }}w{% if forloop.last == false %}, {% endif %}{% endfor %}"
      alt="{{ page.image[1].alt }}"
    >
    <label for="shift-back1" class="shift-back-label"></label>
    <label for="shift-overlay1" class="shift-overlay-label"></label>
    <div class="photo-meta overlay">
      <div class="camera-icon {% if page.image[1].camera contains 'iPhone 5S' %}icon-iphone5s{% elsif page.image[1].camera contains 'X-E2' %}icon-fxe2{% endif %}"></div>
      <ul class="camera-details">
        <li>Camera: {{ page.image[1].camera }}</li>
        <li>Lens: {{ page.image[1].lens }} at {{ page.image[1].focal }}</li>
        <li>Exposure: {{ page.image[1].aperture }} | {{ page.image[1].shutter }} s | ISO {{ page.image[1].iso }}</li>
        <li>Date: {{ page.image[1].date }}</li>
        <li>Location: {{ page.image[1].location }}</li>
      </ul>
      <label for="shift-map1" class="shift-map-label">View map{% include icon/location.html %}</label>
    </div>
  </div>
</figure>


<figure class="wide">
  <input type="radio" role="radio" name="shift2" class="shift-back" id="shift-back2">
  <input type="radio" role="radio" name="shift2" class="shift-overlay" id="shift-overlay2">
  <input type="radio" role="radio" name="shift2" class="shift-map" id="shift-map2">
  <div class="container map-background" id="i2">
    <img
      src="{{ site.image-url }}/{{ page.image[2].src }}" 
      sizes="{{ site.wide-sizes }}"
      srcset="{% for srcset1440 in site.srcset1440 %}{{ site.image-url }}/{{ site.srcset1440[forloop.index0] }}/{{ page.image[2].src }} {{ site.srcset1440[forloop.index0] }}w{% if forloop.last == false %}, {% endif %}{% endfor %}"
       alt="{{ page.image[2].alt }}"
    >
    <label for="shift-back2" class="shift-back-label"></label>
    <label for="shift-overlay2" class="shift-overlay-label"></label>
    <div class="photo-meta overlay">
      <div class="camera-icon {% if page.image[2].camera contains 'iPhone 5S' %}icon-iphone5s{% elsif page.image[2].camera contains 'X-E2' %}icon-fxe2{% endif %}"></div>
      <ul class="camera-details">
        <li>Camera: {{ page.image[2].camera }}</li>
        <li>Lens: {{ page.image[2].lens }} at {{ page.image[2].focal }}</li>
        <li>Exposure: {{ page.image[2].aperture }} | {{ page.image[2].shutter }} s | ISO {{ page.image[2].iso }}</li>
        <li>Date: {{ page.image[2].date }}</li>
        <li>Location: {{ page.image[2].location }}</li>
      </ul>
      <label for="shift-map2" class="shift-map-label">View map{% include icon/location.html %}</label>
    </div>
  </div>
</figure>

<section class="essay">
<h2>Photos from a neighborhood in Washington, DC</h2>
<p>These are some of my favorite photos from a walk around the Mount Pleasant neighborhood in January 2014, shot with a Fujifilm X-E2 and Fujinon XF35mmF1.4 R lens. I revisited the set in <time datetime="2014-11-14 21:00">November 2014</time>, and processed them with Kodak E200 settings from the <a href="http://vsco.co/film/04/lightroom">VSCO Film 04 pack</a> for Lightroom. Editing raw images in Lightroom and VSCO Film is now a core part of how I process my photos. I have found myself becoming more creative and loose with processing over time, with the realization that what comes out of a digital camera is not mechanically “true” to a scene.</p>
<p>An image from a digital camera should not be mistaken for an unfiltered nor an especially accurate take on a scene. Rather, the end result is heavily influenced by the camera’s software processing. In the moment of shooting, I can take care with light, composition, aperture, shutter, and those other physical aspects of photography. Beyond this input, the camera has its own “opinion” about how the shot may turn out, expressed in its software and color output, partially or sometimes even completely outside a photographer’s control.</p>
<p>I choose to shoot raw images so that my camera’s opinion is not hard-coded to a lossy and less flexible JPEG image. A raw image is quite malleable in post-processing software like Lightroom, without losing data. With only the constraints of my composition and exposure when the image was captured, post-processing in this way gives me virtual, creative headroom to take back control and reimagine the scene.</p>
</section>