<template></template>

<script>
export default {
  head() {
    return {
      script: [
        { src: '/js/prefixfree.min.js' },
        { src: '/vendor/jquery/jquery.min.js' },
        { src: '/vendor/bootstrap/js/bootstrap.min.js' },
        { src: '/js/custom.js' },
        { src: '/js/plugins.js' },
        { src: '/vendor/layerslider/js/greensock.js' },
        { src: '/vendor/layerslider/js/layerslider.transitions.js' },
        { src: '/vendor/layerslider/js/layerslider.kreaturamedia.jquery.js' },
        { src: '/vendor/layerslider/js/layerslider.load.js' },
      ],
      link: [
        {
          rel: 'stylesheet',
          href: 'https://fonts.googleapis.com/css?family=Satisfy:400,400i,700,700i%7CNunito:300,400,700',
        },
        {
          rel: 'stylesheet',
          href: '/fonts/flaticon/flaticon.css',
          type: 'text/css',
        },
        {
          rel: 'stylesheet',
          href: '/fonts/fontawesome/fontawesome-all.min.css',
          type: 'text/css',
        },
        {
          rel: 'apple-touch-icon',
          sizes: '72x72',
          href: '/favicons/apple-icon-72x72.png',
        },
        {
          rel: 'apple-touch-icon',
          sizes: '114x114',
          href: '/favicons/apple-icon-114x114.png',
        },
        {
          rel: 'shortcut icon',
          href: '/favicons/favicon.ico',
          type: 'image/x-icon',
        },
        {
          rel: 'stylesheet',
          href: '/vendor/bootstrap/css/bootstrap.min.css',
        },
        {
          rel: 'stylesheet',
          href: '/css/style.css',
        },
        {
          rel: 'stylesheet',
          href: '/css/plugins.css',
        },
        {
          rel: 'stylesheet',
          href: '/css/maincolors.css',
        },
        {
          rel: 'stylesheet',
          href: 'vendor/layerslider/css/layerslider.css',
        },
      ],
    }
  },
}
</script>
