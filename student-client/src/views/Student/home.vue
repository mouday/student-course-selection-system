<template>
  <div>
    <el-container>
      <el-main>
        <h1>student home</h1>
        <info-card></info-card>
        <logout></logout>
      </el-main>
    </el-container>
  </div>
</template>

<script>
import Logout from "@/components/logout";
import InfoCard from "@/components/infoCard";
export default {
  name: "home",
  components: { InfoCard, Logout },
};
</script>

<style scoped></style>
