<template>
  <svg class="mv-icon mv-space-bar" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><title v-if="title">{{title}}</title><desc v-if="desc">{{desc}}</desc><path d="M18 9v4H6V9H4v6h16V9z"/></svg>
</template>
<script>
  export default {
    name: 'MVIconSpaceBar',
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
