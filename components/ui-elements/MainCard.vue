<template>
  <div class="main-card">
    <div class="card-banner"></div>
    <div class="card-content">
      <SelectInput label="Vrsta izračuna:" :options="testArray" />
      <SelectInput label="Vaša netto plaća:" :options="testArray" />
      <SelectInput label="Mjesto prebivališta:" :options="testArray" />
      <SelectInput
        label="Broj djece kao porezna olakšica:"
        :options="testArray"
      />
      <SelectInput label="Broj uzdržavanih članova" :options="testArray" />
      <SelectInput label="Stupanj invaliditeta:" :options="testArray" />
    </div>
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
