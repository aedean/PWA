<template>
    <picture>
        <source media="(min-width: 601px)" :srcset="'appimages/' + headerImage + '.webp'" type="image/webp">      
        <source media="(min-width: 1px)" :srcset="'appimages/' + headerImage + '_small.webp 1x, appimages/' + headerImage + '.webp 2x'" type="image/webp">
        <source media="(min-width: 601px)" :srcset="'appimages/' + headerImage + 'jpg'">      
        <img id="mainImg" :src="'appimages/' + headerImage + '.jpg'" :srcset="'appimages/' + headerImage + '_small.jpg 1x, appimages/' + headerImage + '.jpg 2x'" :alt="altText">
     </picture>
</template>
 
<script>
export default {
  name: 'HeroImage',
  props: {
    headerImage: {
      type: String,
      required: true
    },
    altText: {
      type: String,
      required: true
    }
  }
}
</script>
 
<style scoped>
#mainImg {
    width:100%;
    height: auto;
}
</style>
