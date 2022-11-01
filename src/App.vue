<template>
  <h1>{{ message }}</h1>
  <HelloWorld />
</template>

<script>

import HelloWorld from '~/components/HelloWorld'

export default {
  data() {
    return {
      message: 'heelo vue!!!'
    }
  }
}
</script>
