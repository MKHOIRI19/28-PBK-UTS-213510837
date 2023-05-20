<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <h1 class="black">{{ msg }}</h1>
    <h3>
      <a href="https://instagram.com/sembilan.boleh19?igshid=ZGUzMzM3NWJiOQ==" target="_blank" rel="noopener"><img src="@/assets/IG.png" alt=""></a> &
      <a href="https://github.com/MKHOIRI19/28-PBK-UTS-213510837" target="_blank" rel="noopener"><img src="@/assets/github.png" alt=""></a>
    </h3>
  </div>
</template>

<style scoped>
img{
  width: 8%;
}

h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
