<template>
  <svg class="mv-icon mv-eject" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><title v-if="title">{{title}}</title><desc v-if="desc">{{desc}}</desc><path d="M5 17h14v2H5zm7-12L5.33 15h13.34z"/></svg>
</template>
<script>
  export default {
    name: 'MVIconEject',
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
