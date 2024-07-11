<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header>
    <div class="wrapper">
      <HelloWorld msg="You did it!" />
      <div>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Labore voluptatum praesentium, veritatis harum velit repudiandae temporibus fuga soluta nisi obcaecati dicta nulla eligendi quisquam quo nemo pariatur? Praesentium asperiores animi obcaecati modi dicta inventore ad ab possimus velit esse quis vero accusamus voluptate, rerum alias numquam eveniet excepturi consequuntur ipsa maiores perspiciatis delectus. Explicabo corporis aspernatur odio, vero eos nam? Corporis neque, iure perferendis molestiae soluta atque possimus, velit praesentium veritatis quae, ratione a sapiente? Harum exercitationem iste blanditiis eaque accusamus rem maxime eum aliquam! Id maxime fuga autem, voluptate praesentium saepe eum nihil facilis dolores qui? Est, nobis ducimus.</div>
    </div>
  </header>

  
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
