<template>
  <svg class="mv-icon mv-sort" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><title v-if="title">{{title}}</title><desc v-if="desc">{{desc}}</desc><path d="M3 18h6v-2H3v2zM3 6v2h18V6H3zm0 7h12v-2H3v2z"/></svg>
</template>
<script>
  export default {
    name: 'MVIconSort',
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
