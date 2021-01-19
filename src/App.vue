<template>
  <Header />
  <div class="w-full flex">
    <Calendar />
  </div>
</template>

<script>
import Calendar from "./components/Calendar.vue";
import Header from "./components/Header.vue";
export default {
  components: { Calendar, Header },
};
</script>
