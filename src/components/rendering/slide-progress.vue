<template >
    <div class="slide-progress">
        <div class="slide-progress-value" :style="`transform: ${slides-1 == idx?`scaleX(${tick})`: slides-1 > idx? 'scaleX(1)' : 'scaleX(0)'}`"></div>
    </div>
</template>
<script>
export default {
    name: "slide-progress",
    props: ["slides", "idx", "tick"]
}
</script>
<style lang="sass">
    
</style>