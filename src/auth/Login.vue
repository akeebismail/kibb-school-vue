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
                    <b-form-group id="userEmail" label="Enter Your username" label-for="email" class="m-b-15">
                      <b-form-input id="email" type="email" size="lg" placeholder="Enter your email">

                      </b-form-input>
                    </b-form-group>
                    <b-form-group class="m-b-15" id="userPassword" label="Enter your password" label-for="password">
                      <b-form-input id="password" type="password" size="lg" placeholder="Enter your password">

                      </b-form-input>
                    </b-form-group>
                    <div class="login-buttons">
                      <b-button :size="lg" variant="success" type="submit" block>Login</b-button>
                    </div>
                    <div class="m-t-20 m-b-40 p-b-40 text-inverse">
                      not a member yet? Click <a href="#" class="text-success">Here</a> to register.
                    </div>
                    <hr/>
                    <p class="text-center">
                      &copy;Kibb Admin ALl Right Reserved 2018
                    </p>
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
