<template>
  <svg class="mv-icon mv-fast-rewind" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><title v-if="title">{{title}}</title><desc v-if="desc">{{desc}}</desc><path d="M11 18V6l-8.5 6 8.5 6zm.5-6l8.5 6V6l-8.5 6z"/></svg>
</template>
<script>
  export default {
    name: 'MVIconFastRewind',
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
