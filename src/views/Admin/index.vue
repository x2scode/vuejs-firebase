<template>
  <div>
        <div>
          <admin-sidebar>
            <template #title>Admin</template>
            <template #sidebar>
              <a 
                class="uk-icon-button uk-margin-small-leftp" 
                uk-toggle="target: #sideNav"
                >
                <span uk-icon="menu"></span>
              </a>
            </template>
            <template #action>
                <router-link class="uk-link-heading" to="/" uk-icon="sign-out">Sign out</router-link>
            </template>
          </admin-sidebar>
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