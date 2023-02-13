<template>
    <div class="cont">
  <HeaderComponent></HeaderComponent>
  <PhonePostCard></PhonePostCard>
  </div>
</template>
<script>
import HeaderComponent from "../components/Header.vue";
import PhonePostCard from "../components/PhonePostCard.vue";
export default {
  name: "HomeScreen",
  components: {
    PhonePostCard,
    HeaderComponent,
  },
};
</script>

<style>
.cont{
    display: flex;
    justify-content: center;
    flex-direction: column;
gap: 1rem;
}
</style>
