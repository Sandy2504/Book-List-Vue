<script>
import HeaderLayout from "./components/HeaderLayout.vue";
import Booklist from "./components/Booklist.vue";
export default {
  name: "app",
  components: {
    HeaderLayout,
    Booklist,
  },
};
</script>
<template>
  <HeaderLayout />
  <Booklist />
</template>

<style>
:root {
  --primary: #6a1cc3;
  --primary-dark: #370b68;
  --secondary: #f39c12;
}

body {
  font-family: Arial, Helvetica, sans-serif;
}

h1,
h2,
h3,
h4 {
  color: var(--primary);
  margin-bottom: 15px;
}

.inside {
  margin: 10px;
}

@media only screen and (min-width: 1140px) {
  .inside {
    width: 960px;
    margin: 0 auto;
  }
}
</style>
