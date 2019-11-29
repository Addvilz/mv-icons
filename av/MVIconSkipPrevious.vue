<template>
  <svg class="mv-icon mv-skip-previous" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><title v-if="title">{{title}}</title><desc v-if="desc">{{desc}}</desc><path d="M6 6h2v12H6zm3.5 6l8.5 6V6z"/></svg>
</template>
<script>
  export default {
    name: 'MVIconSkipPrevious',
    props: {
      title: {
        required: false,
        type: String,
      },
      desc: {
        required: false,
        type: String
      }
    }
  }
</script>
