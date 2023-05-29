<template>
    <TheHeader />
    <div class="containter-fuild"></div>
        <div class="row">
            <div class="col-sm-3">
                SIDER BAR
            </div>

            <div class="col-sm-9">
                <router-view></router-view>
            </div>

        </div>

    
</template>

<script>
import TheHeader from "../components/TheHeader.vue";

export default {
    components: {
        TheHeader
    }
}
</script>