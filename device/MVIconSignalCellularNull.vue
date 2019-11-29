<template>
  <svg class="mv-icon mv-signal-cellular-null" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><title v-if="title">{{title}}</title><desc v-if="desc">{{desc}}</desc><path d="M20 6.83V20H6.83L20 6.83M22 2L2 22h20V2z"/></svg>
</template>
<script>
  export default {
    name: 'MVIconSignalCellularNull',
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
