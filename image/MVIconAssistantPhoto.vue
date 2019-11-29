<template>
  <svg class="mv-icon mv-assistant-photo" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><title v-if="title">{{title}}</title><desc v-if="desc">{{desc}}</desc><path d="M14.4 6L14 4H5v17h2v-7h5.6l.4 2h7V6z"/></svg>
</template>
<script>
  export default {
    name: 'MVIconAssistantPhoto',
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
