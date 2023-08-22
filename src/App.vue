<template>
  <div class="app-wrapper">
    <BioCard />
  </div>
</template>

<script>
import BioCard from "./widgets/BioCard/BioCard.widget";

export default {
  name: "App",
  components: {
    BioCard,
  },
};
</script>

<style>
html,
body {
  font-family: Fira Code;
  margin: 0;
  background-color: black;
  --main-color: #fff;
  --important-text: orange;
  font-size: 13px;
}
.app-wrapper {
  width: 100vw;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
