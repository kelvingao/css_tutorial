<template lang="pug">
  #app
  
    #header
      h1 Contact Us
      h2 Contace The Net Ninja

    h2#content-header content

    p Hello there ninjas! contract us below.
    p Aren't paragraph's cool?

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
h2 {
  font-size: 24px;
}
#content-header {
  font-size: 18px;
  color: red;
}

span {
  display: block;
  color: blue;
}

.deck {
  color: red;
}
</style>

