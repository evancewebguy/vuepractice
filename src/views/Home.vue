<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <CompanyList class="text-info" msg="List of Companies" />
  </div>
</template>

<script>
// @ is an alias to /src
import CompanyList from "@/components/CompanyList.vue";

export default {
  name: "Home",
  components: {
    CompanyList,
  },
};
</script>
