<template>
  <svg class="mv-icon mv-remove" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><title v-if="title">{{title}}</title><desc v-if="desc">{{desc}}</desc><path d="M19 13H5v-2h14v2z"/></svg>
</template>
<script>
  export default {
    name: 'MVIconRemove',
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
