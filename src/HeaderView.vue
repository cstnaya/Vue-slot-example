<template>
  <header>
  	<ul>
      <li v-for="(page, idx) in pages" :key="idx">
      	{{ page }}
      </li>
    </ul>
  </header>
</template>

<script>  
  export default {
    data() {
      return {
        pages: ["home", 'about', 'shop', 'Q&A', 'Address', 'Cart'],
      };
    },
  };
</script>