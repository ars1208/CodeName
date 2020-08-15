<template>
    <div class="card-content" v-on:click="isActivePushed=!isActivePushed" v-bind:class="{pushedColor:isActivePushed}">
        <p>word</p>
    </div>
</template>

<script>
export default {
  data: () => {
    return {
      isActivePushed: false
    }
  }
}
</script>

<style>
:root {
  --red-team-color: #f62e36;
  --blue-team-color: #009bbf;
  --npc-color: #9c5e31;
  --spy-color: #000000;
}

.card-content {
  height: 130px;
  width: 220px;
  background-color: #b5b5ac;
  font-size: 30px;
  text-align: center;
  border-radius: 20px;
  cursor: pointer;
  display: block;
  margin: 20px;
  float: left;
}
.pushedColor {
  height: 130px;
  width: 220px;
  background-color: var(--red-team-color);
  font-size: 30px;
  text-align: center;
  border-radius: 20px;
  cursor: pointer;
  display: block;
  margin: 20px;
  float: left;
}

.--red-team-color {
  background-color: var(--red-team-color);
}

.--blue-team-color {
  background-color: var(--blue-team-color);
}

.--npc-color {
  background-color: var(--npc-color);
}

.--spy-color {
  background-color: var(--spy-color);
}
</style>
