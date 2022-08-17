<template>
  <h1 class="bg-gray-600" @click="count++;">Working!</h1>
  <p>{{count}}</p>
</template>

<script>
export default {
  name: 'MainApp.vue',
  data() {
    return {
      count: 1
    }
  },
}

</script>