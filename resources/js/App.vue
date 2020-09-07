<template>
    <Navbar />
</template>


<script>
import Navbar from './components/Navbar'
export default {
    name: "app",
    data() {
        return {
            activeItem: 0
        }
    },
    components: {
        Navbar
    }
}
</script>
