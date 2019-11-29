<template>
  <svg class="mv-icon mv-flash-on" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><title v-if="title">{{title}}</title><desc v-if="desc">{{desc}}</desc><path d="M7 2v11h3v9l7-12h-4l4-8z"/></svg>
</template>
<script>
  export default {
    name: 'MVIconFlashOn',
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
