<template>
  <div class="q-pt-lg full-width" style="max-width: 800px">
    <NewsBlockvid />
    <NewsCovid />
  </div>
</template>

<script>
import NewsBlockvid from "./News/NewsBlockvid";
import NewsCovid from "./News/NewsCovid";

export default {
  components: {
    NewsBlockvid,
    NewsCovid
  }
};
</script>
