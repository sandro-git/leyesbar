<template>
<div>

  <WaitingPage />
</div>
</template>

<script>
import WaitingPage from '../components/WaitingPage.vue'
export default {
  name: 'IndexPage',
  components: WaitingPage,
  head: {
    bodyAttrs: {
      class: 'h-screen'
    },
    htmlAttrs:{
      class:'h-screen'
    }
  }

}

</script>
