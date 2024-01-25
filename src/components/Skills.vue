<template>
  <div class="About">
    <h2>Skills</h2>
    <p>I work in such technologies as</p>
    <div v-for="language in languages">
      <img :src="language.image" alt="">
    <h4>{{ language.title }}</h4>

    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      languages: [
        { id: 1, title: 'HTML5', rate: 4, image: '/Users/erik/Documents/VUE/VUELESS3/src/assets/junior.png' },
        { id: 1, title: 'CSS3', rate: 3, image: 'getSrc' },
        { id: 1, title: 'JavaScript', rate: 4, image: 'getSrc' },
        { id: 1, title: 'React', rate: 5, image: 'getSrc' }
      ]
    }
  }
}
</script>

<style scoped>
.About {
  text-align: center;
}

h2 {
  font-size: 34px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
  padding: 50px 0 50px 0;
}

p {
  padding-bottom: 50px;
}


</style>
