<template>
    <h1>{{ title }}</h1>
</template>

<script lang="ts">
import { Vue, Component, Prop } from "vue-property-decorator";

@Component
export default class Counter extends Vue {
    @Prop() private title!: string;
}
</script>


<style lang="scss" scoped>
    h1 {
        color: red;
    }
</style>


