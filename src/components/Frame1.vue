<template>
  <div class="id-screen-is-provided-by-north-parent">
    <div class="id-screen-is">
      ID Screen is provided by Northwest Innovations Ltd, which is a company
      registered in England and Wales at Companies House. Our registered office
      is Northwest Innovations Limited, Bentley Suite, The Motorworks,
      Chestergate, Macclesfield, Cheshire, United Kingdom, SK11 6DU and our
      registered number is 14425558. Northwest Innovations Ltd is registered for
      VAT under VAT Registration number GB428679449.
    </div>
    <div class="image-2-parent">
      <img class="image-2-icon" alt="" src="/undefined5.png" />
      <img class="image-1-icon" alt="" src="/undefined6.png" />
    </div>
  </div>
</template>
<script>
  import { defineComponent, ref } from "vue";

  export default defineComponent({
    name: "Frame1",
  });
</script>
<style scoped>
  .id-screen-is {
    position: relative;
    display: flex;
    align-items: center;
    justify-content: center;
    width: 23.88rem;
    height: 7.94rem;
    flex-shrink: 0;
  }
  .image-2-icon {
    position: relative;
    width: 5.6rem;
    height: 2.21rem;
    object-fit: cover;
  }
  .image-1-icon {
    position: relative;
    width: 6.07rem;
    height: 2.34rem;
    object-fit: cover;
  }
  .image-2-parent {
    width: 13.19rem;
    height: 2.34rem;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    gap: var(--gap-5xl);
    margin-top: -0.56rem;
  }
  .id-screen-is-provided-by-north-parent {
    position: absolute;
    top: 152.44rem;
    left: 0.25rem;
    width: 23.88rem;
    height: 9.72rem;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: flex-start;
    text-align: center;
    font-size: var(--font-size-3xs);
    color: var(--color-black);
    font-family: var(--font-inter);
  }
</style>
