<template>
<div>
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