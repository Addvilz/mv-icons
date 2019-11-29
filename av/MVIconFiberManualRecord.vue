<template>
  <svg class="mv-icon mv-fiber-manual-record" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><title v-if="title">{{title}}</title><desc v-if="desc">{{desc}}</desc><circle fill="#010101" cx="12" cy="12" r="8"/></svg>
</template>
<script>
  export default {
    name: 'MVIconFiberManualRecord',
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
