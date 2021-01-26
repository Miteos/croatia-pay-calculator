<template>
  <div class="custom-select">
    <label for="select">
      {{ label }}
    </label>
    <select id="select" :value="chosenValue">
      <option v-for="option in options" :key="option" :value="chosenValue">
        {{ option }}
      </option>
    </select>
  </div>
</template>

<script>
export default {
  props: {
    label: {
      type: String,
      default: '',
    },
    options: {
      type: Array,
      default: () => [],
    },
    chosenValue: {
      type: String,
      default: 'Click to choose...',
    },
  },
  data() {
    return {}
  },
}
</script>
