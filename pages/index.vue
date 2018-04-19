<template lang="pug">
  article
    section
      .cols
        .grid.bg-white.grid-rows.grid-cols.grid-cols(style="--grid-rows: 3fr 1fr; --grid-columns: 3fr 2fr;")
          .writeup.overflow-scroll.maxvh-75.p-4.grid-row-span-2
            h1 Catherine "Cat" Most
            h3 Nature Explorer. Hugger. Invertebrate Enthusiast.
            h1.blue —
            p
              span.bold Prior to Gigster…
              span lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras ac lorem at felis vulputate semper. Curabitur consecteur, mi vitae vehicula malesuada,
            p
              span.bold Outside of the office, you can find me…
              span lorem ipsum dolor sit amet, consectetur adipiscing elit.
            p
              span Curabitur consectetur, mi vitae vehicula
              span.bold …always make(s) me happy.
            p
              span.bold My favorite place in the world…
              span lorem ipsum dolor sit amet, consectetur adipiscing elit.
            p
              span.bold My goal is to…
              span vivamus vehicula auctor tortor, nec luctus tellus volutpat quis. Fusce quis laoreet lorem. Duis fermentum velit in ligula congue cursus. Sed scelerisque neque quis suscipit vulputate.
            p
              span.bold My goal is to…
              span vivamus vehicula auctor tortor, nec luctus tellus volutpat quis. Fusce quis laoreet lorem. Duis fermentum velit in ligula congue cursus. Sed scelerisque neque quis suscipit vulputate.
            p
              span.bold My goal is to…
              span vivamus vehicula auctor tortor, nec luctus tellus volutpat quis. Fusce quis laoreet lorem. Duis fermentum velit in ligula congue cursus. Sed scelerisque neque quis suscipit vulputate.
          .brief-img
            .img-background.h-100
          .brief-info
            .bg-orange.p-2.h-100
              .h3.bold Executive Assistant
              p.mb-0 Started Aug 2017
              a.dark.h3(href="#")
                i.fab.fa-linkedin
              a.dark.h3.ml-1(href="#")
                i.fab.fa-slack

</template>
<style>
  .img-background {
    background: url('~/static/headshotA.jpg') center 25% no-repeat;
    background-size: cover;
  }
  .minvh-10 { min-height: 10vh; }
  .maxvh-75 { max-height: 75vh; }
  .maxvh-75 { min-height: 75vh; }
</style>
<script>
