<template>
  <span v-if="false"></span>
</template>

<script>
// Test on: https://cards-dev.twitter.com/validator
export default {
  data: () => ({
    href: 'https://twitter.com/intent/tweet?url=' + encodeURIComponent('https://head-elements.now.sh/about')
  }),
  head: {
    meta: [
      { name: 'twitter:card', content: 'summary' },
      { name: 'twitter:site', content: '@yangwao' },
      { name: 'twitter:title', content: 'Crypto2020 project' },
      { name: 'twitter:description', content: 'Crypto2020 aims to part all banking products, soon' },
      { name: 'twitter:image', content: 'https://s.gravatar.com/avatar/d31afb47d607e443bbf5f781922407cf?s=80&r=x' },
      { name: 'twitter:image:alt', content: 'yangwao avatar' }
    ]
  }
}
</script>
