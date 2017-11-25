<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>~ ~</h2>
    <ul>
      <li>
        ico
      </li>
      <li>
        why
      </li>
      <li>
        when
      </li>
      <li>
        hardcap?
      </li>
    </ul>
    <h2>Why you want help us</h2>
    <ul>
      <li>
        ~
      </li>
      <li>
        ~
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'ico.progressbar.sk'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #35495E;
}
</style>
