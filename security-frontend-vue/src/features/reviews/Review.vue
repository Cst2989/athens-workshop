<template>
  <div v-html="safeContent"></div>
</template>

<script>
const ReviewComponent = {
  props: ['reviewContent'],
  computed: {
    safeContent() {
      return this.reviewContent;
    }
  }
};

export default ReviewComponent
</script>



