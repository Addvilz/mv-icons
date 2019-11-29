<template>
  <svg class="mv-icon mv-signal-cellular-connected-no-internet-4-bar" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><title v-if="title">{{title}}</title><desc v-if="desc">{{desc}}</desc><path d="M20 18h2v-8h-2v8zm0 4h2v-2h-2v2zM2 22h16V8h4V2L2 22z"/></svg>
</template>
<script>
  export default {
    name: 'MVIconSignalCellularConnectedNoInternet4Bar',
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
