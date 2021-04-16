<template>
    <div style='background-color:purple'>
      <div class='miboton'>
        {{ text }}
      </div>
    </div>
</template>

<script>
export default {
    props: ['text']
}
</script>

<style>
.miboton {
    color: white;
    padding: 10px
}
</style>