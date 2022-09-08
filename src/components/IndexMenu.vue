  <template>
      <div class="indexMenu">
        <h4>{{ menuItem }}</h4>
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