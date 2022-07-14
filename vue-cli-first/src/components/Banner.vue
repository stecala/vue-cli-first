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
        width: 100%;
        height: 60vh;
        margin: 40px 0;
    }
    .img-container img{
        width: 100%;
        height: 100%;
        object-fit: cover;
        object-position: bottom;
    }
</style>