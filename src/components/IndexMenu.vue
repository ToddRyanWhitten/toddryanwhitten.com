  <template>
      <div class="indexMenu">
        <h5>{{ menuItem }}</h5>
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