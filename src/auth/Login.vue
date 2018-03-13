<template>
    <auth>
        <div class="login login-with-news-feed">
            <div class="news-feed">
                <div class="news-image">
                    <img src="../assets/img/login-bg/bg-7.jpg" data-id="login-cover-image"/>
                </div>
                <div class="news-caption">
                    <h4 class="caption-title">
                        <i class="fa fa-diamond text-success"></i>
                        Announcing the Kibb School MS
                    </h4>
                    <p>
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    </p>
                </div>
            </div>
            <div class="right-content">
                <div class="login-header">
                    <div class="brand">
                        <span class="logo"></span>
                        Kibb Admin
                        <small>Kibb School Management system</small>
                    </div>
                    <div class="icon">
                        <i class="fa fa-sign-in"></i>
                    </div>
                </div>
                <div class="login-content">
                    <b-form>
                        Login Form Here
                    </b-form>
                </div>
            </div>
        </div>
    </auth>
</template>

<script>
    import Auth from '../auth/Login'
    export default {
        name: "login",
        components: {Auth},
        data() {

        },
    }
</script>

<style scoped>

</style>