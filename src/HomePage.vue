<template>
  <Canvas>
    <template #header>
    	<HeaderView></HeaderView>
    </template>
    <template #main>
      <div class='main-content'>
        <div class='banner-content'>
          <img src="">
        </div>
        <div>
          <table>
            111
          </table>
        </div>
      </div>
    </template>
    <template #footer>
    	<FooterView></FooterView>
    </template>
  </Canvas>
</template>

<script>  
  import Canvas from './Canvas.vue';
  import HeaderView from './HeaderView.vue';
  import FooterView from './FooterView.vue';
  
  export default {
    components: { Canvas, HeaderView, FooterView },
  }
</script>