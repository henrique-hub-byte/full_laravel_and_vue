<template>
    <div class="main">
        <div class="sidebar">
            <SideBarView />
        </div>

        <div class="content_right">

            <div class="navbar">
                <NavBarView />
            </div>

            <div class="pages">

            </div>

        </div>
    </div>
</template>

<script>
import SideBarView from './components/SideBarView.vue';
import NavBarView from './components/NavBarView.vue';

export default {
    name: 'DashboardView',
    components: {
        SideBarView,
        NavBarView
    }
}
</script>

<style lang="scss" src="./style.scss" scoped>

</style>