<script setup lang="ts">

</script>

<template>
  
  <div class="greetings">
    
    <div class="me-title">
      <h1  id="typing-effect" class="green">I'm WCPE</h1>

    </div>

    <h3>
      <p>一条咸鱼</p>
      <p>爱好，捡垃圾</p>
      <p>瞎折腾浪费时间最在行</p>
    </h3>
  </div>
</template>

<style scoped>




h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
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
