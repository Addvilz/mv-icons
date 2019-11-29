<template>
  <svg class="mv-icon mv-call-received" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><title v-if="title">{{title}}</title><desc v-if="desc">{{desc}}</desc><path d="M20 5.41L18.59 4 7 15.59V9H5v10h10v-2H8.41z"/></svg>
</template>
<script>
  export default {
    name: 'MVIconCallReceived',
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
