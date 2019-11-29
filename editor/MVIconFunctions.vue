<template>
  <svg class="mv-icon mv-functions" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><title v-if="title">{{title}}</title><desc v-if="desc">{{desc}}</desc><path d="M18 4H6v2l6.5 6L6 18v2h12v-3h-7l5-5-5-5h7z"/></svg>
</template>
<script>
  export default {
    name: 'MVIconFunctions',
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
