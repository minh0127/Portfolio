<template>
  <!-- homeview -->
  <div>
    <div class="section">
      <PortfolioInfo></PortfolioInfo>
    </div>

    <div class="section">
      <portfolio-profile></portfolio-profile>
    </div>

    <div class="section">
      <portfolio-project-list></portfolio-project-list>
    </div>
  </div>
</template>
<script>
import PortfolioInfo from "@/components/PortfolioInfo.vue";
import PortfolioProfile from "@/components/PortfolioProfile.vue";
import PortfolioProjectList from "@/components/PortfolioProjectList.vue";
export default {
  components: { PortfolioInfo, PortfolioProfile, PortfolioProjectList },
};
</script>
<style scoped>
.section {
  padding-block: 100px;
}
</style>
