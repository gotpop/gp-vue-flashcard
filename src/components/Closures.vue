<template>
    <div class="closures">
        <h1>Closures demo</h1>
        <p>In it's broadest sense a closure is a method of controlling scope.</p>
        <p>On a practical level a closure is a nested inner function with access to the parent function's scope.</p>
        <p>It creates a kind of "scope bundle" active in memory.</p>
        <hr/>
        <p>In this case the example closure is invoked twice and each case it retains it's own scope.</p>
        <p>Retains state and scope after exectution.</p>
    </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator';

@Component
export default class CallApplyBind extends Vue {}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

</style>
