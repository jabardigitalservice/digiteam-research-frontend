<template>
  <div class="flex flex-col bg-green-700 rounded-lg py-5 px-5 mx-3">
    <span>
      Welcome, <slot />
    </span>
  </div>
</template>

<script setup>
defineComponent({
  name: "BaseSample",
});
</script>
