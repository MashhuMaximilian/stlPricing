<template>
    <div ref="rendererContainer" style="width: 100%; height: 100%;"></div>
  </template>
  
  <script>
  import * as THREE from 'three';
  import { GLTFLoader } from 'three/examples/jsm/loaders/GLTFLoader';
  import { OrbitControls } from 'three/examples/jsm/controls/OrbitControls';
  import { RGBELoader } from 'three/examples/jsm/loaders/RGBELoader.js';
  import { STLLoader } from 'three/examples/jsm/loaders/STLLoader';

  export default {
  setup() {
    const container = ref(null);

    onMounted(() => {
      const scene = new THREE.Scene();
    });

    return {
      container,
    };
  },
};