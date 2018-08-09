<template>
  <div>
    <article>
      <header class="content-header container-fluid">
        <div class="row">
          <div class="col-lg-12">
            <h2>Hello World</h2>
          </div>
        </div>
      </header>

      <div class="content container-fluid">
        <div class="row">
          <div class="col-lg-12">
            <p>{{msg}}</p>
          </div>
        </div>
      </div>
    </article>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>
