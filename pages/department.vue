<template>
  <div class="container">
    <Header :showTopBar="false" :showBreadcrumbs="true" :nowSelected="1"/>
    <div class="warpper">
      <Department/>
    </div>
    <FooterSmall/>
  </div>
</template>

<script>
import Header from '~/components/utils/Header.vue'
import FooterSmall from '~/components/utils/FooterSmall.vue'
import Department from '~/components/department/Department.vue'

export default {
  components: {
    Header,
    Department,
    FooterSmall,
  }
}
</script>

<style lang="scss">
  @import "assets/css/main.scss";

</style>
