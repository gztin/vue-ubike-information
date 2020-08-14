<template>
  <div id="app">
    <h1>YouBike 臺北市公共自行車即時資訊</h1>
    <UbikeTable />
  </div>
</template>

<script>
import UbikeTable from "./components/UbikeTable.vue";
export default {
  name: "App",
  components: {
    UbikeTable
  }
};
</script>

<style>
@import url("https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta/css/bootstrap.min.css");
@import url("https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css");

#app {
  padding: 1rem;
}
</style>
