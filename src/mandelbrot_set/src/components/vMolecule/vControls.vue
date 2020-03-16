<template>
  <div class="vControls">
    <vButton>restart</vButton>
    <vButton>kill</vButton>
    <vButton>+</vButton>
    <vButton>-</vButton>
  </div>
</template>
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
$min-top: 125px
$min-left: 75px
.vControls
  position:relative
  top: 0
  width: 300px
  height: 300px
  background-color: grey

  .vButton:nth-child(1)
    top: $min-top
    left: $min-left
  .vButton:nth-child(2)
    top: $min-top
    left: $min-left + 100px
  .vButton:nth-child(3)
    top: $min-top + 100px
    left: $min-left
  .vButton:nth-child(4)
    top: $min-top + 100px
    left: $min-left + 100px
</style>
