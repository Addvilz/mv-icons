<template>
  <svg class="mv-icon mv-short-text" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><title v-if="title">{{title}}</title><desc v-if="desc">{{desc}}</desc><path d="M4 9h16v2H4zm0 4h10v2H4z"/></svg>
</template>
<script>
  export default {
    name: 'MVIconShortText',
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
