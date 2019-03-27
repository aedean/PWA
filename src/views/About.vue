<template>
<div>
  <HeroImage altText="About Kitties" headerImage="catheader2" />
<main>
  <h2>About Us</h2>
  <p>
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus dignissim venenatis consequat. Praesent quis odio a neque venenatis ornare. Nam vel sem sed magna porttitor ultrices. Nunc nec turpis vitae lacus efficitur pulvinar in id nibh. Praesent sed mi vel ipsum faucibus ultrices iaculis eget dui. Praesent ultricies velit vel vestibulum convallis. Praesent accumsan luctus sem, at consectetur erat convallis pretium. Nunc pulvinar nec nibh a mollis. Donec a metus in sapien sollicitudin fermentum vitae eu eros.
  </p>
  <div id='myMap'></div>
</main>
</div>
</template>

<script>
import HeroImage from '@/components/HeroImage.vue'
 
export default {
  name: 'About',
  components: {
    HeroImage
  }
}
</script>
