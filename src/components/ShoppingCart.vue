<template>
    <v-navigation-drawer v-model="drawer" location="right">

      Blaa
    </v-navigation-drawer>
</template>
<script>
  export default {
    props: ['drawerProp'],
    computed: {
      drawer() {
        return this.drawerProp;
      }
    }
  }
</script>
<style scoped></style>
