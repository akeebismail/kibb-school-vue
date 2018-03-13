<template>
    <div class="pace-top">
        <div id="page-loader" class="fade in">
            <span class="spinner"></span>
        </div>
        <div class="login-cover">
            <div class="login-cover-image"><img src="" data-id="login-cover-image" alt="" /></div>
            <div class="login-cover-bg"></div>
        </div>
        <!-- begin #page-container -->
        <div id="page-container" class="fade">
            <!-- begin login -->
            <div class="login login-v2" data-pageload-addclass="animated fadeIn">
                <!-- begin brand -->
                <div class="login-header">
                    <div class="brand">
                        <span class="logo"></span> Color Admin
                        <small>responsive bootstrap 3 admin template</small>
                    </div>
                    <div class="icon">
                        <i class="fa fa-sign-in"></i>
                    </div>
                </div>
                <!-- end brand -->
                <div class="login-content">
                    <b-form class="margin-30">
                    </b-form>
                </div>
    </div>
</template>

<script>
    export default {
        name: "auth"
    }
</script>

<style scoped>

</style>