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
        more about ico
      </li>
    </ul>
    <h2>Why we need your help</h2>
    <ul>
      <li>
        visualisations of new space
      </li>
      <li>
        bill of costs & materials
      </li>
      <li>
        cowork model
      </li>
      <li>
        space for bigger meetups
      </li>
      <li>
        meeting room
      </li>
      <li>
        hackerspace
      </li>
    </ul>
    <h3>What we have now</h3>
    <li>
      <a href="https://progressbar.sk">main hackerspace page</a>
    </li>
    <li>
      <a href="https://progressbar.sk/calendar">lot of meetups in our space</a>
    </li>
    <li>
      <a href="https://cowork.progressbar.sk">working cowork in Bratislava</a>
    </li>
    <li>
      <a href="httsp://donate.progressbar.sk">donation page</a>
    </li>
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
