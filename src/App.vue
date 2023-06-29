<template>
  <HeaderTemplate />
  <main>
    <div class="inside">
      <BooklistTemplate />
    </div>
  </main>
</template>

<script>
import HeaderTemplate from "@/components/HeaderTemplate.vue";
import BooklistTemplate from "@/components/BooklistTemplate.vue";
export default {
  name: "App",
  components: {
    HeaderTemplate,
    BooklistTemplate,
  },
};
</script>
