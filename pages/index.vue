<template>
  <div class="container">
    <SelectInput label="whatever" :options="testArray" />
  </div>
</template>

<script>
export default {
  data() {
    return {
      testArray: ['testerino', 'fuck you all'],
    }
  },
}
</script>

<style></style>
