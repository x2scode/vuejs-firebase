<template>
  <div>
        <div>
          <a 
            class="uk-icon-button uk-margin-small-left uk-margin-small-top" 
            uk-toggle="target: #sideNav"
          >
          <span uk-icon="menu"></span>
          </a>
          <admin-sidebar></admin-sidebar>
       </div>
      <router-view/>
  </div>
</template>

<script>
import AdminSidebar from '@/components/Admin/AdminSidebar.vue'

export default {
  components: { 
    AdminSidebar,
    },
    data(){
      return{
      }
    },
}
</script>

<style>

</style>