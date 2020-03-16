<template
  ><div class="vControls">
    <vButton>restart</vButton>
    <vButton>kill</vButton>
    <vButton>+</vButton>
    <vButton>-</vButton>
  </div></template
>
<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import vButton from "../vAtom/vButton.vue";
@Component({
  components: {
    vButton
  }
})
export default class VControls extends Vue {}
</script>

<style lang="sass">
.vControls
  position:relative
  top: 0
  width: 300px
  height: 300px
  background-color: grey
</style>
