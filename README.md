# ejemplo-programacion-III
Esto es una prueba de git hub

import CameraPhoto, { FACING_MODES, IMAGE_TYPES } from 'jslib-html5-camera-photo';

// get your video element with his corresponding id from the html
let videoElement = document.getElementById('videoId');

// pass the video element to the constructor.
let cameraPhoto = new CameraPhoto(videoElement);
