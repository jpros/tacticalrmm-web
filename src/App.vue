<template>
  <router-view />
</template>

<script>
export default {
  name: "App",
};
</script>

<style lang="sass">
body
  overflow-y: hidden

.tbl-sticky
  thead tr th
    position: sticky
    z-index: 1
  thead tr:first-child th
    top: 0

.tabs-tbl-sticky

  thead tr th
    position: sticky
    z-index: 1
  thead tr:first-child th
    top: 0

.remote-bg-tbl-sticky
  max-height: 70vh

  thead tr th
    position: sticky
    z-index: 1
  thead tr:first-child th
    top: 0

.audit-mgr-tbl-sticky
  max-height: 75vh

  thead tr th
    position: sticky
    z-index: 1
  thead tr:first-child th
    top: 0

.settings-tbl-sticky
  max-height: 60vh

  thead tr th
    position: sticky
    z-index: 1
  thead tr:first-child th
    top: 0

.agents-tbl-sticky
  thead tr th
    position: sticky
    z-index: 1
  thead tr:first-child th
    top: 0

.table-bgcolor
  .q-table__top,
  .q-table__bottom,
  thead tr:first-child th
    background-color: #f5f4f2

.table-bgcolor-dark
  .q-table__top,
  .q-table__bottom,
  thead tr:first-child th
    background-color: #1d1d1d

.bg-dark
  background-color: --q-page-dark

.bg-light
  background-color: #ffffff

.highlight
  background-color: #c9e6ff

.highlight-dark
  background-color: #404040

.action-completed
  background-color: $positive

.agent-offline
  background: gray !important

.agent-overdue
  background: red !important

.min-width
  min-width: 0px !important
</style>
