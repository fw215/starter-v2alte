<template>
  <div id="app">
    <div class="wrapper">
      <Header></Header>
      <Aside></Aside>
      <div class="content-wrapper">
        <router-view/>
      </div>
    </div>
  </div>
</template>

<script>
import Header from '@/components/Header'
import Aside from '@/components/Aside'

export default {
  name: 'App',
  components: {
    Header,
    Aside
  }
}
</script>
