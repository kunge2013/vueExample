<template>
     <mt-button type="primary" @click="showText">default</mt-button>
</template>
<script>
import Vue from 'vue';
import { Button } from 'mint-ui';
Vue.component(Button.name, Button);
import'mint-ui/lib/style.css';
export default {
    methods:{
        showText(){
            console.log("你单击了我");
        }
    }
}
</script>

<style scoped>

</style>
