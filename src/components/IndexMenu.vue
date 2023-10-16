  <template>
      <div class="indexMenu">
        <h4>{{ menuItem }}</h4>
      </div>
      <swiper-container slides-per-view="3" speed="500" loop="true" css-mode="true">
        <swiper-slide><img src="../assets/wmw_buenos_aires_1.jpg"></swiper-slide>
        <swiper-slide><img src="../assets/wmw_buenos_aires_2.jpg"></swiper-slide>
        <swiper-slide><img src="../assets/wmw_rio_1.jpg"></swiper-slide>
      </swiper-container>
</template>
  
  <script>
  export default {
    name: 'IndexMenu',
    props: {
      menuItem: String
    }
  }
  </script>