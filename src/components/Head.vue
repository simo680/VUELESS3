<template>
  <nav>
    <ul class="menu">
      <li>Home</li>
      <li>About me</li>
      <li>Skills</li>
      <li>Portfolio</li>
      <li>Contacts</li>
    </ul>
  </nav>
  <div class="group">
    <div>
      <h1 class="name">Alex</h1>
      <h1 class="name">William</h1>
    </div>
    <div class="years">
      <p>web developer</p>
      <p>28 years old, Karaganda</p>
    </div>
    <div class="lang">
      <p class="lang__item_grey">RU</p>
      <p class="lang__item">|</p>
      <p class="lang__item">EN</p>
    </div>
  </div>
  <img src="../assets/junior.png" alt="interest man" />
</template>

<script></script>

<style scoped>
.menu {
  display: flex;
  justify-content: space-between;
  list-style-type: none;
  padding: 33px 0 31px 0;
  border-bottom: 1px solid black;
}

.group {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.lang {
  transform: rotate(270deg);
}

.name {
  font-size: 47.339px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
}

img {
  width: 1000px;
}
</style>
