<template>
  <span class="nova-link">
    <a :href="field.value.url" target="_blank">{{ field.value.title }}</a>
  </span>
</template>


<script>
export default {
  props: ["resourceName", "field"]
};
</script>
