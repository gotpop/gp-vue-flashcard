<template>
<div class="call">
    <h1>Call, Apply, Bind</h1>
    <p>Call runs a function on an object of your choice. It accepts arguments.</p>
    <p>Apply is the same as call except it can accept an array.</p>
    <p>Bind creates but does not call the function.</p>
    <hr />
    <p>Call changes context.</p>
</div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator';

@Component
export default class CallApplyBind extends Vue {}
</script>

<style scoped lang="scss">

</style>
