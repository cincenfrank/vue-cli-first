<template>
  <h1 class="title">{{text}}</h1>
</template>

<script>
export default {
name: "Title",
props: {
    text: String,
}
}
</script>

<style>
.title{
    color: red;
    font-weight: bold;
}
</style>