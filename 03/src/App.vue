<template lang="pug">
  #app
  
    #header
      h1 Contact Us
      h2 Contace The Net Ninja

    h2#content-header content

    #main-content
      p Hello there #[strong ninjas!] contract us below.
      p.test Aren't paragraph's cool?

    a(href="http://www.google.com") Google

    span Yo, I'm a span tag

    span.deck Yo, I'm a span tag too
    span.deck This is a deck of spans
    span.deck I like span decks

</template>

<script>
export default {
  name: 'app',
 
}
</script>

<style>
#main-content p{
  color: red; /* has 101 points */
}
p {
  color: black; /* only 1 point */
}
.test {
  color: green; /* class has 10 points */
}
strong {
  color: green; /* only inheriting #main-content p, override this */
}
</style>

