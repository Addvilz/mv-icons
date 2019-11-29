<template>
  <svg class="mv-icon mv-forward" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><title v-if="title">{{title}}</title><desc v-if="desc">{{desc}}</desc><path d="M12 8V4l8 8-8 8v-4H4V8z"/></svg>
</template>
<script>
  export default {
    name: 'MVIconForward',
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
