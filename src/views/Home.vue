<template>
  <div class="specific">
    <h1>home</h1>
  </div>
  <h1>you can see subdirectories here:</h1>
  <ul>
    <li>products</li>
    <li>posts</li>
  </ul>
  {{ this.$route }}

  	<button onclick="$router.push('/')">go to home</button><br/>
</template>

<style lang="scss" scoped>
$blue: #0403ea;
$pink: #ff5ecb;

.specific {
  h1 {
    color: $blue;
    background-color: $pink;
    padding: 1rem 2rem;
    border-radius: 0.5rem;
    display: inline-block;
  }
}

</style>
