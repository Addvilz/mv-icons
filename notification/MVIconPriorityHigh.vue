<template>
  <svg class="mv-icon mv-priority-high" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><title v-if="title">{{title}}</title><desc v-if="desc">{{desc}}</desc><circle cx="12" cy="19" r="2"/><path d="M10 3h4v12h-4z"/></svg>
</template>
<script>
  export default {
    name: 'MVIconPriorityHigh',
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
