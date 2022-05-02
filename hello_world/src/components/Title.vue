<template>
    <div class="vue_cli">
        <h1>La mia prima app con Vue CLI!</h1>
    </div>
</template>

<script>
export default {
  name: 'Title_1',
  props: {
    msg: String
  }
}
</script>

<style scoped lang="scss">

h1{
    font-size: 5rem;
    text-align: center;
    color: red;
}
</style>