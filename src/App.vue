<template>
<div id="app">
  <Button>Slot</Button>
  <Button text="text"></Button>
</div>
</template>

<script>

import Button from "@/components/button.vue"

export default {
  name: "App",

  components: { Button }
}

</script>
