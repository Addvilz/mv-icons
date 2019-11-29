<template>
  <svg class="mv-icon mv-signal-cellular-1-bar" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><title v-if="title">{{title}}</title><desc v-if="desc">{{desc}}</desc><path fill-opacity=".3" d="M2 22h20V2z"/><path d="M12 12L2 22h10z"/></svg>
</template>
<script>
  export default {
    name: 'MVIconSignalCellular1Bar',
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
