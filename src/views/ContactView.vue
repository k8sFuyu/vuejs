<template>
    <div>
        <h1>{{ contact.prenom }}</h1>
        <span>{{ contact.num }}</span>
        <button @click="call (contact.prenom, contact.numero)"></button>
    </div>
</template>
<script>
export default {
    name:'ContactView',

    components:{

    },
    computed:{
        contacts(){
            return this.$store.state.contacts;
        }
    },
    methods: {
        call(){
        return this.$store.commit("call")
        },
    },
    
}
</script>
<style>
    
</style>