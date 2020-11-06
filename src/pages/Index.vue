<template>
  <q-page>
    <h4>Main</h4>
    <p>This is main page :)</p>
    <q-btn
      @click="HelloWorld"
      color="primary"
      label="Showing norify."
    />
  </q-page>
</template>

<script>
export default {
  methods: {
    HelloWorld () {
      this.$q.notify('Hello,World!')
    }
  }
}
</script>
