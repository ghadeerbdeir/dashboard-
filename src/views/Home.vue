<template>
  <div class="">
    <SideBarLeft class="col-2" />
    <div class="ps-2">
      <div class="d-flex">
        <div>
          <ContentCon class="" />
          <div class="row">
            <div class="col-md-6"><BarChart class="" /></div>
            <div class="col-md-6"><SectionSe class="" /></div>
          </div>
        </div>

        <SideBarright class="col-2" />
      </div>
    </div>

    <CustomChart />
  </div>
</template>
<script>
import SideBarLeft from "@/components/SideBarLeft.vue";
import SideBarright from "@/components/SideBarright.vue";
import ContentCon from "@/components/ContentCon.vue";
import BarChart from "@/components/BarChart.vue";
import SectionSe from "../components/SectionSe.vue";
import CustomChart from "../components/CustomChart.vue";
export default {
  name: "Home-m",
  components: {
    SideBarLeft,
    SideBarright,
    ContentCon,
    SectionSe,
    BarChart,
    CustomChart,
  },
};
</script>
<style>
/* For mobile phones: */
* {
  font-family: "Karma", sans-serif;
}
</style>
