<script setup>
  import { text } from "../data/1_data"

  const formattedText = text.split("\n");
  console.log(formattedText);
</script>

<template>
  <pre>{{formattedText}}</pre>
</template>