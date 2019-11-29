<template>
  <svg class="mv-icon mv-network-cell" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><title v-if="title">{{title}}</title><desc v-if="desc">{{desc}}</desc><path fill-opacity=".3" d="M2 22h20V2z"/><path d="M17 7L2 22h15z"/></svg>
</template>
<script>
  export default {
    name: 'MVIconNetworkCell',
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
