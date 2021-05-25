<template>
  <siteHeader />
  <router-view/>
  <siteFooter />
</template>

<script>
import siteHeader from '@/views/site/header'
import siteFooter from '@/views/site/footer'

export default {
  components: {
    siteHeader,
    siteFooter
  },
  name: 'App'
}
</script>

<style>
  @import url(//spoqa.github.io/spoqa-han-sans/css/SpoqaHanSansNeo.css);
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100;200;300;400;500;600;700;800;900&display=swap');
  * { font-family: 'Spoqa Han Sans Neo', 'sans-serif'; }
</style>
