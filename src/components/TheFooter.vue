<template>
  <footer>
    <div class="container">
      <router-link class="logo-font" :to="{ name: 'home', params: {} }">
        the collective brain
      </router-link>
      <span class="attribution">
        I totally stole this from the folks at 
        <a rel="noopener noreferrer" target="blank" href="https://thinkster.io"
          >Thinkster</a
        >. Code &amp; MIT licensed.
      </span>
    </div>
  </footer>
</template>

<script>
export default {
  name: "RwvFooter"
};
</script>
