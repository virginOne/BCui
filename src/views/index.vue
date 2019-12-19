<template>
    
</template>
<script>
import web3 from 'web3'

export default {
    data() {
        return {
            Web3:null,
        }
    },
    created() {
        
        this.Web3 = web3
        console.log(web3)
    },
}
</script>