<template>
  <ons-splitter v-on="unrecognizedListeners">
    <slot></slot>
  </ons-splitter>
</template>

<script>
  /* This file is generated automatically */
  import 'onsenui/esm/elements/ons-splitter';
  import { deriveEvents, selfProvider, deriveDBB } from '../mixins';

  export default {
    name: 'v-ons-splitter',
    mixins: [deriveEvents, selfProvider, deriveDBB]
  };
</script>