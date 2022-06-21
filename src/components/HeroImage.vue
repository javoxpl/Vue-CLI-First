<template>
<div class="jumbotron">
</div>
</template>
<script>
export default {
    name: 'HeroImage'
}
</script>
<style scoped>
.jumbotron  {
    height: 99vh;
    width: 99vw;
    background-image: url('https://picsum.photos/2048/1080'); 
    background-repeat: no-repeat;
    background-size: cover;   
    position: absolute; 
    filter: brightness(50%) blur(5px);
}
</style>