<template lang="pug">
  article
    section
      .cols
        .grid.bg-white.grid-cols.w-100.p-4.grid-space-3.mb-6(style="--grid-columns: repeat(auto-fill, minmax(14rem, 1fr))")
          div
            nuxt-link(to="/")
              img(src="~/static/headshotA.jpg")
              .h4 Diana Alessandrini
              .h5 Executive Assistant
          div
            nuxt-link(to="/")
              img(src="~/static/headshotB.jpg")
              .h4 Sandrine Bitton
              .h5 Fulfillment Lead
          div
            nuxt-link(to="/")
              img(src="~/static/headshotC.jpg")
              .h4 Will Rickard
              .h5 Sales Development Rep
          div
            nuxt-link(to="/")
              img(src="~/static/headshotD.jpg")
              .h4 Caprice Turner
              .h5 Account Manager
</template>
<style>
  :root {
    --bkg: auto;
  }
  .img-background {
    background: url('~/static/headshotA.jpg') center 25% no-repeat;
    background-size: cover;
  }
  .minvh-10 { min-height: 10vh; }
  .maxvh-75 { max-height: 75vh; }
  .maxvh-75 { min-height: 75vh; }
</style>
<script>
// import employees from '~static/data.json'
//
// export default {
//   data ({ params }) {
//     return { employees }
//   }
// }
</script>
