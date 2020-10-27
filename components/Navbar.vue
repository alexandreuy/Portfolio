<template>
    <b-navbar toggleable="lg" type="dark" variant="info">
        <b-navbar-nav class="ml-auto">
            <SideBar />
        </b-navbar-nav>
    </b-navbar>
</template>

<script>
import SideBar from '@/components/SideBar'

export default {
    components: { SideBar }

}
</script>
        