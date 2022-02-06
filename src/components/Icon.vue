<template>
    <i class="iconfont" :class="fontClass"></i>
</template>
<script>
const classMap = {
    home: "icon-home-page",
    arrowUp: "icon-jiantoushang",
    arrowDown: "icon-jiantouxia",
    blog: "icon-blog",
    message: "icon-xinxi",
    chat: "icon-liuyan"     
}
export default {
    props: {
        type: {
            type: String,
            required: true
        }
    },
    computed: {
        fontClass() {
            return classMap[this.type];
        }
    }
    
}
</script>
<style scoped>
@import "//at.alicdn.com/t/font_3169937_kzaw9ll5zkd.css"
</style>


