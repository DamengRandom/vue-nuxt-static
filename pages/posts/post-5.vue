<template lang="md">
  ### This is a markdown template demo
  Current route is {{ $route.path }}

  ```js
  <script>
    const markdown = 'write some code block';
    console.log(markdown);
  </script>
  ```
</template>

<script>
  export default {
    layout: 'markdown-posts'
  }
</script>
