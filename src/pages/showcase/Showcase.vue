<template>
  <q-page class="flex flex-center">
    <div class="q-gutter-md row items-start">
      <q-date v-model="date" />
    </div>
  </q-page>

</template>

<script>
export default {
  data () {
    return {
      date: '2019/02/01'
    }
  }
}
</script>

<style>

</style>
