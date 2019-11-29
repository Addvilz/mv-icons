<template>
  <svg class="mv-icon mv-brightness-1" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><title v-if="title">{{title}}</title><desc v-if="desc">{{desc}}</desc><circle cx="12" cy="12" r="10"/></svg>
</template>
<script>
  export default {
    name: 'MVIconBrightness1',
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
