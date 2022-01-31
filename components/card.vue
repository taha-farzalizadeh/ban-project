<template>
    <div>
        <nuxt-link :to="link">
            <img :src="require(`../assets/images/${link}.png`)" :alt="link">
        </nuxt-link>
    </div>
</template>
<script>
export default {
    props:{
        link:{
            type:String,
            required:true
        }
    }
}
</script>