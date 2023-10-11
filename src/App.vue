<script setup>
import {OneDumbButton, ThreeDumbButtons} from 'my-dumb-vue-lib'
</script>

<template>

  <!-- You can add your own Bulma styling to the components, on top of what is defined in the lib -->
  <OneDumbButton prefix="Welcome to this dumb app" class="is-large is-fullwidth is-info" />

  <!--
    However such styling can only be defined on the top-level component :
    the following won't impact the individual buttons styling,
    because there is no such cascading logic defined in the ThreeDumbButtons component
    (see https://vuejs.org/guide/essentials/class-and-style.html)
   -->
  <ThreeDumbButtons class="is-info" />

  <ThreeDumbButtons />
  <ThreeDumbButtons direction="column" />

</template>