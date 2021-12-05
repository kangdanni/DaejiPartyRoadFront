<template>
  <div class="main">
    <DaejiPartyRoad msg="여기는 돼지파티의 성지입니다." />
    <MainStoreList></MainStoreList>
  </div>
</template>

<script>
// @ is an alias to /src
import DaejiPartyRoad from "@/components/DaejiPartyRoad.vue";
import MainStoreList from "@/components/MainStoreList.vue";

export default {
  name: "Main",
  components: {
    DaejiPartyRoad,
    MainStoreList,
  },
};
</script>
