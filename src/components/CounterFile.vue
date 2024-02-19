<template>
    <h2>COUNTER</h2>
    <h1>{{ counter }}</h1>
    <button class="btn btn-outline-primary m-3 " @click="incremento"><b>+</b></button>
    <button class="btn btn-outline-danger m-3 " @click="reset"><b>reset</b></button>
</template>

<script>
import { ref } from 'vue';
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'


export default{
    setup(){
        const counter = ref(0);
        return {counter};
    },

    methods: {
        incremento(){
            this.counter++;
        },
        reset(){
            this.counter = 0;
        }
    }
}
</script>