<template>
  <div>

<!-- Side Navbar ------------------------------->
    <div id="sideNav" uk-offcanvas="mode: push">
    <div class="uk-offcanvas-bar">
        <ul class="uk-nav uk-nav-default">
            <li :class="{'uk-active': $route.name == 'admin'}"><router-link to="/admin">Home</router-link></li>
            <li :class="{'uk-active': $route.name == 'products'}"><router-link to="/admin/products">Products</router-link></li>
            <li :class="{'uk-active': $route.name == 'categories'}"><router-link to="/admin/categories">Categories</router-link></li>
        </ul>
    </div>
</div>


  </div>
</template>

<script>
export default {
}
</script>

<style scoped>

</style>