<template>
    <div class="misaka">
      <h1>{{ title }}</h1>
      <img :src="image" alt="Misaka Mikoto" />
      <p>{{ description }}</p>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        title: '御坂美琴应援网页',
        image: 'path/to/misaka/image.jpg', // 替换为御坂美琴的图片路径
        description: '御坂美琴是《魔法禁书目录》和《科学超电磁炮》的主要角色之一，是一名能力者，代号为“电磁炮”。'
      }
    }
  }
  </script>
  
  <style scoped>
  .misaka {
    text-align: center;
  }
  .misaka img {
    width: 300px;
    height: auto;
  }
  </style>
  