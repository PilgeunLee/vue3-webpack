<template>
    <h1>{{ massege }}</h1>
    <HelloWorld/>
</template>

<script>
import HelloWorld from '~/components/HelloWorld'

export default {
    components:{
        HelloWorld
    },

    data(){
        return {
            massege:'Hello vue!!!'
        }
    }
}
</script>