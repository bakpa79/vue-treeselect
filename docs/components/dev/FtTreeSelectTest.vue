<template>
  <div>
    <treeselect :options="options" :max-height="null" :hide-control="true" :dropdownpopover="false" :multiple="true" :collapse-menu-padding="true" />
  </div>
</template>

<script>
  import { generateOptions } from '../utils'

  export default {
    data: () => ({
      options: generateOptions(1, 500),
    }),
  }
</script>
