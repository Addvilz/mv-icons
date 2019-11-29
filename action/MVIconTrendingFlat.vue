<template>
  <svg class="mv-icon mv-trending-flat" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><title v-if="title">{{title}}</title><desc v-if="desc">{{desc}}</desc><path d="M22 12l-4-4v3H3v2h15v3z"/></svg>
</template>
<script>
  export default {
    name: 'MVIconTrendingFlat',
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
