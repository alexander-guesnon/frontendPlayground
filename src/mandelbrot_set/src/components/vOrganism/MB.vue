<template>
  <div>
   <div> Mandlebroght set</div>
   <VControls />
   <vImage />
   </div>
</template>
<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import vImage from "../vAtom/vImage.vue";
import VControls from "../vMolecule/vControls.vue"
@Component({
  components: {
    VControls,
    vImage
  }
})
export default class MB extends Vue {}
</script>
