<template>
  <svg class="mv-icon mv-signal-cellular-0-bar" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><title v-if="title">{{title}}</title><desc v-if="desc">{{desc}}</desc><path fill-opacity=".3" d="M2 22h20V2z"/></svg>
</template>
<script>
  export default {
    name: 'MVIconSignalCellular0Bar',
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
