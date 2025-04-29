<script setup>
import { ref } from 'vue';
const text = ref('');

const btnText = ref('點我');
const isShow = ref(false);
// const msg = ref('我剛剛按了一下'); 多此一舉！
const msgToggle = () => {
  isShow.value = !isShow.value ; 
  btnText.value = isShow.value ? '清空' : '點我';
}

</script>

<template>
  <section class="wrap">
    <h3>01 — 練習題目：資料綁定 (v-model)</h3>
    <input type="text" v-model="text">
    <p>{{ text }}</p>
  </section>
  <section class="wrap">
    <h3>02 — 練習題目：條件渲染 (v-if / v-show) 練習</h3>
    <button class="btn" type="button" @click="msgToggle">{{ btnText }}</button>
    <span v-if="isShow">我剛剛按了一下</span>
  </section>
</template>


<style scoped>
.wrap {
  background-color: lightblue;
  padding: 0.75rem;
  margin: 0.75rem;
}

.btn  {
  background-color: slategray;
  color: lemonchiffon;
  font-size: 1.25rem;
  border-radius: 4px;
  padding-block: 0.5rem;
  padding-inline: 2rem;
  margin-right: 0.75rem;
}
</style>