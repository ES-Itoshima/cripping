<template>
  <div id="app">
    <h1>画像トリミングアプリケーション</h1>
    <ImageCropper 
      :image-url="selectedImage"
      :width="400"
      :height="300"
    />
    <div class="image-selection">
      <h2>サンプル画像を選択</h2>
      </div>
    </div>
</template>

<script setup>
import { ref } from 'vue'
import ImageCropper from '@/components/cropping.vue'

</script>