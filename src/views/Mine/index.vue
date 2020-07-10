<template>
    <div id="main">
        <Header title="我的喵喵"/>
            <div id="content">
                <Login />
            </div>
        <TarBar />
    </div>
</template>

<script>
import Header from '@/components/Header/index.vue'
import TarBar from '@/components/TarBar/index.vue'
import Login  from '@/components/Login/index.vue'

export default {
    name: 'Mine',
    components: {
        Header,
        TarBar,
        Login
    }
}
</script>

<style scoped>

</style>
