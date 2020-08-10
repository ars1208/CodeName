<template>
  <div>
    <div class="top">
      <div class="play-area">
        <div class="play-area-col">
          <card id="card_1"></card>
          <card id="card_2"></card>
          <card id="card_3"></card>
          <card id="card_4"></card>
          <card id="card_5"></card>
        </div>
        <div class="play-area-col">
          <card id="card_6"></card>
          <card id="card_7"></card>
          <card id="card_8"></card>
          <card id="card_9"></card>
          <card id="card_10"></card>
        </div>
        <div class="play-area-col">
          <card id="card_11"></card>
          <card id="card_12"></card>
          <card id="card_13"></card>
          <card id="card_14"></card>
          <card id="card_15"></card>
        </div>
        <div class="play-area-col">
          <card id="card_16"></card>
          <card id="card_17"></card>
          <card id="card_18"></card>
          <card id="card_19"></card>
          <card id="card_20"></card>
        </div>
        <div class="play-area-col">
          <card id="card_21"></card>
          <card id="card_22"></card>
          <card id="card_23"></card>
          <card id="card_24"></card>
          <card id="card_25"></card>
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
  height: 850px;
  width: 1300px;
  margin: auto;
}

.play-area-col {
  overflow: hidden;
}

.card-content {
  margin: 20px;
  float: left;
}

</style>
