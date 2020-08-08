<template>
  <div>
    <div class="top">
      <h1>Code Name</h1>
      <div class="play-area">
        <div class="play-area-col">
          <card></card>
          <card></card>
          <card></card>
          <card></card>
          <card></card>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import card from './card'

export default {
  components: {
    card
  }
}
</script>

<style>
.top {
  background-color: aqua;
  height: 800px;
}

</style>
