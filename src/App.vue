<template>
    <div>
        <login></login>
    </div>
</template>
<script>
    import Login from './auth/Login'
    export default {
        name :"app",
        components: {Login}
    }
</script>