<template>
  <ii :class="'el-icon-' + name"></ii>
</template>

<script>
  export default {
    name: 'ElIcon',

    props: {
      name: String
    }
  };
</script>
