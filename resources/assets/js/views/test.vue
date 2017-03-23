/**
 * 
 * 测试组件
 * @description 访问不存在的路由都会定向到这个组件页面
 * @author 苏锐佳
 * @date 2017/02/22
 * 
 */
<template>
    <!-- <div> -->
    	<indexL></indexL>
        test
    <!-- </div> -->
</template>
<style lang="sass" scoped>

    @import "../../sass/function";

</style>
<script>
	import indexL from './index.vue';
    export default{
        name: 'test',
        components: {
	        indexL
	    }
    }
</script>
