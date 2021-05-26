<template>
  <div class="home">
    <main1 />
    <main2 />
  </div>
</template>

<script>
// @ is an alias to /src
import main1 from './site/main-1'
import main2 from './site/main-2'

export default {
  name: 'Home',
  components: {
    main1,
    main2
  }
}
</script>
