<template>
  <main>
    <DashboardView>
      <div slot="slot-pages" class="content-pages">
        <p>Home</p>
      </div>

    </DashboardView>
  </main>
</template>

<script>
import DashboardView from '../Dashboard/DashboardView.vue';
export default {
  components: {
    DashboardView,
  }
}
</script>

<style lang="scss" src="./style.scss" scoped>

</style>