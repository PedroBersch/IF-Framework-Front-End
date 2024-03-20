<template>
  <div v-if="show">
    <!-- Loop through the images array and render img tags dynamically -->
    <img v-for="img in images" :src="img.url" width="250px" />
  </div>
  <div v-else>
    <p>Erro em postar imagems</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      images: [
        {
          url: "https://th.bing.com/th/id/OIP.eUrLjP_6-w6sEA3CFbiejgHaD3?rs=1&pid=ImgDetMain",
        },
        {
          url: "https://th.bing.com/th/id/OIP.BxV_yIUCcu68ZNFpPdYxSwAAAA?rs=1&pid=ImgDetMain",
        },
        {
          url: "https://th.bing.com/th/id/R.8885ce9860f3aed4c999dc1b9fb70633?rik=ujP9lvfbsVflUw&pid=ImgRaw&r=0",
        },
        {
          url: "https://logos-download.com/wp-content/uploads/2019/01/JavaScript_Logo.png",
        },
        {
          url: "https://th.bing.com/th/id/R.6fc1c04b114f92b2ea6747c9a0b57f61?rik=xXmXG%2bKcP3wJWw&pid=ImgRaw&r=0",
        },
      ],
      show: false,
    };
  },
};
</script>
