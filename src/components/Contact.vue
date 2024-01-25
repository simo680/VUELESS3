<template>
  <div class="wrapper">
    <h2>Contacts</h2>
    <p>Want to know more or just chat?</p>
    <p>You are welcome!</p>
    <button class="btn">Send message</button>

    <div v-for="images in image " :key="image"></div>
    <p>Like me on</p>
    <p>LinkedIn, Instagram, Behance, Dribble</p>
  </div>
</template>

<script></script>

<style scoped>
.wrapper {
  text-align: center;
}

.btn {
  background-color: black;
  border-radius: 40px;
  color: white;
  padding: 10px 35px;
  border: none;
  font-family: Abel;
  font-size: 18px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
}
</style>
