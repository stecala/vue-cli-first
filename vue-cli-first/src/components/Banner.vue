<template>
  <div>
    <div class="img-container">
        <img src="https://www.ocean-net.es/catalogo/wp-content/uploads/2014/12/img_banner-thin_mountains-2.jpg" alt="">
    </div>
  </div>
</template>

<script>
export default {
  name: 'MainJumbo',
}
</script>

<style scoped>
    .img-container{
        width: 100vw;
        height: 30vh;
        margin: 40px 0;
    }
    .img-container img{
        object-fit: cover; 
    }
</style>