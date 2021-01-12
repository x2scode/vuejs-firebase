<template>
<div class="uk-margin-small-top">
<!-- Navbar section ----------------------------->
    <nav class="uk-navbar uk-navbar-container uk-margin">
        <div class="uk-navbar-left uk-dark uk-background-muted ">
            <div class="uk-navbar-item">
                <!-- Slot Title of navbar -->
                <slot name="title">
                </slot>
            </div>
        </div>
        <div class="uk-navbar-right">
            <div class="uk-navbar-item">
                <!-- Slot Button -->
                <slot name="action">
                </slot>
            </div>
        </div>
    </nav>
</div>
</template>

<script>
export default {

}
</script>

<style>

</style>