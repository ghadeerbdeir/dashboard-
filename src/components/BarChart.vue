<template>
  <div class="container">
    <Bar
      class="bg-light col-xl-12 col-sm-12 col-md-3"
      style="
        width: 500px;
        height: 300px;
        margin-top: 3rem;
        margin-left: 10rem;
        background-color: aqua;
        border-radius: 2%;
        border: 1px solid rgb(255, 244, 244);
        box-shadow: 10px 5px 25px rgb(223, 215, 215);
      "
      :chart-options="chartOptions"
      :chart-data="chartData"
      :chart-id="chartId"
      :dataset-id-key="datasetIdKey"
      :plugins="plugins"
      :css-classes="cssClasses"
      :styles="styles"
      :width="width"
      :height="height"
    />
  </div>
</template>
  
  <script>
import { Bar } from "vue-chartjs";
import {
  Chart as ChartJS,
  Title,
  Tooltip,
  Legend,
  BarElement,
  CategoryScale,
  LinearScale,
} from "chart.js";

ChartJS.register(
  Title,
  Tooltip,
  Legend,
  BarElement,
  CategoryScale,
  LinearScale
);

export default {
  name: "BarChart",
  components: { Bar },
  props: {
    chartId: {
      type: String,
      default: "bar-chart",
    },
    datasetIdKey: {
      type: String,
      default: "label",
    },
    width: {
      type: Number,
      default: 300,
    },
    height: {
      type: Number,
      default: 150,
    },
    cssClasses: {
      default: "",
      type: String,
    },
    styles: {
      type: Object,
      default: () => {},
    },
    plugins: {
      type: Object,
      default: () => {},
    },
  },
  data() {
    return {
      chartData: {
        labels: [
          "January",
          "February",
          "Mars",
          "April",
          "May",
          "November",
          "Oktober",
        ],
        datasets: [
          {
            label: "Data One",
            backgroundColor: "#716cf9",
            data: [4, 20, 12, 3, 10, 40, 17],
          },
        ],
      },
      chartOptions: {
        responsive: true,
      },
    };
  },
};
</script>
<style scoped>
.bar {
  width: 50rem;
  border-radius: 2%;
  border: 1px solid rgb(255, 244, 244);
  box-shadow: 10px 5px 25px rgb(223, 215, 215);
}
</style>