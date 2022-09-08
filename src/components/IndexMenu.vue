  <template>
      <div class="indexMenu">
        <h1>{{ menuItem }}</h1>
      </div>
  </template>
  
  <script>
  export default {
    name: 'IndexMenu',
    props: {
      menuItem: String
    }
  }
  </script>