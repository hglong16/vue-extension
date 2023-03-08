<template lang="">
        <div class="overlay">
            <div class="popup">
              <h1>Legen .. wait for it.. dary</h1>

            </div>
        </div>
</template>
<script>
import { defineComponent } from 'vue';
export default defineComponent({
  setup() {
    const visible = ref(false)
    return {
      visible
    }
  }
})
</script>
<style lang="">
.overlay {
  @apply fixed  inset-0 w-full h-full bg-black bg-opacity;
}
</style>