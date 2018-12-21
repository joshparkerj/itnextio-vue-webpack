<template>
  <div class="app full-width center-content">
    <hello-component name="World" />
    <h1>Hello World (Jesus? Is that you?)</h1>
    <h2>black comedy amirite lmao</h2>
    <h3>I'm cooler than a ...</h3>
    <p>i ain't sayin nuffin</p>
    <h5>I love you so much</h5>
  </div>
</template>

<script>
import HelloComponent from './components/HelloComponent.vue'

export default {
  components: {
    HelloComponent
  }
}
</script>

<style scoped>
.app {
  background-color: beige;
  border: solid black;
  padding: 1%;
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}
.app h1 {
  color: blue;
  font-family: 'Comic Sans MS';
  display: block;
  width: 50%;
  margin: auto;
  border-bottom: dashed orange;
  padding: 5%;
}
p {
  font-size: 8px;
  margin-left: 10%;
}
</style>

