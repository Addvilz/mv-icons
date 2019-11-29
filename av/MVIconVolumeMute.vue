<template>
  <svg class="mv-icon mv-volume-mute" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><title v-if="title">{{title}}</title><desc v-if="desc">{{desc}}</desc><path d="M7 9v6h4l5 5V4l-5 5H7z"/></svg>
</template>
<script>
  export default {
    name: 'MVIconVolumeMute',
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
