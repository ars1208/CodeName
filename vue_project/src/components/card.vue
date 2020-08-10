<template>
    <div class="card-content" v-on:click="isActivePushed=!isActivePushed" v-bind:class="{pushedColor:isActivePushed}">
        <p>word</p>
    </div>
</template>

<script>
export default {
  data () {
    return {
      isActivePushed: false
    }
  }
}
</script>

<style>
.card-content {
  height: 130px;
  width: 220px;
  background-color: #b5b5ac;
  font-size: 40px;
  text-align: center;
  border-radius: 20px;
  cursor: pointer;
  display: block;
}
.pushedColor {
  height: 130px;
  width: 220px;
  background-color: blue;
  font-size: 40px;
  text-align: center;
  border-radius: 20px;
  cursor: pointer;
  display: block;
}
</style>
