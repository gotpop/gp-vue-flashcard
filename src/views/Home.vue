<template>
  <div class="home">
    <img src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App"/>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import CallApplyBind from '@/components/CallApplyBind.vue'; // @ is an alias to /src
import Closures from '@/components/Closures.vue'; // @ is an alias to /src

@Component({
  components: {
    CallApplyBind,
    Closures,
  },
})
export default class Home extends Vue {}
</script>
