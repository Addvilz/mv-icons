<template>
  <svg class="mv-icon mv-details" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><title v-if="title">{{title}}</title><desc v-if="desc">{{desc}}</desc><path d="M3 4l9 16 9-16H3zm3.38 2h11.25L12 16 6.38 6z"/></svg>
</template>
<script>
  export default {
    name: 'MVIconDetails',
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
