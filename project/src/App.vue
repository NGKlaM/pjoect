<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="container">
    <div class="box">
      <h1>
        Hello
      </h1>
      <img src="public/img/hinh-nen-may-tinh-4k-cong-nghe-4.jpg" alt="">
      <div class="text">
        <p>Họ Tên: Nguyễn Kiều Lâm</p>
        <p>Tuổi: 21</p>
        <p>Quê Quán: Ba Vì Hà Nội</p>
        <p>Định Hướng: Full-stack</p>
        <p>Ngôn ngũ đã học: Js, java, C# ,PHP</p>
      </div>
    </div>
  </div>
</template>

<style scoped>
* {
    margin: 0;
    padding: 0;
  }

  .container {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100vh;
  }

  .box {
    background-color: #f5f5f5;
    border: 1px solid #ccc;
    border-radius: 5px;
    padding: 20px;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .text p {
    margin: 5px 0;
  }

  .text img {
    max-width: 100%;
    height: auto;
  }
</style>
