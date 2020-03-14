<template>

</template>

<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";

@Component
export default class molecule extends Vue {
  @Prop() private msg!: string;
}

</script>

</style>

