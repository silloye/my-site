<template>
    <img 
        class="img-avatar"
        :src="url" 
        :style="{width: size + 'px', height: size + 'px'}" alt="" />
</template>
<script>
export default {
    //验证格式和范围
    props: {
        url: {
            type: String,
            required: true
        },
        size: {
            type: Number,
            required: true
        }
    }
}
</script>

<style scoped>
.img-avatar {
    border-radius: 50%;
    object-fit: cover
}
</style>


