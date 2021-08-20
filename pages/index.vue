<template></template>

<script>
export default {
  head() {
    return {
      script: [
        { src: '/vendor/jquery/jquery.min.js' },
        { src: '/vendor/bootstrap/js/bootstrap.min.js' },
        { src: '/js/custom.js' },
        { src: '/js/plugins.js' },
        { src: '/vendor/layerslider/js/greensock.js' },
        { src: '/vendor/layerslider/js/layerslider.transitions.js' },
        { src: '/vendor/layerslider/js/layerslider.kreaturamedia.jquery.js' },
        { src: '/vendor/layerslider/js/layerslider.load.js' },
      ],
      link: [{}],
    }
  },
}
</script>
