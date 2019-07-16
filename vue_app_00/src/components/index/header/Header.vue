<template>
    <div>
        <ceiling></ceiling>
        <nput></nput>
        <navbar></navbar> 
        <navv></navv>
        <middle></middle>
        <ooter></ooter>
    </div>
</template>
<script>
import Input from './comm/Input'
import Nav from './Nav'
import Navbar from './comm/Navbar'
import Ceiling from './comm/Ceiling'
import Middle from './Middle'
import Footer from './Footer'
export default {
    data() {
        return {
            
        }
    },
    components:{
     "nput":Input,
     "navv":Nav,
     "navbar":Navbar,
     "ceiling":Ceiling,
     "middle":Middle,
     "ooter":Footer,
   }
    
    
}
</script>
<style>
    
</style>