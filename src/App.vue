<script>

import UpHeader from "./components/UpHeader.vue"
import BuySection from "./components/BuySection.vue"
import LinkSection from "./components/LinkSection.vue"
import endFooter from "./components/endFooter.vue"
export default {
  data(){
    return{

    }
  },
  components: {
    UpHeader,
    BuySection,
    LinkSection,
    endFooter
  }
}

</script>

<template>
  
    <UpHeader></UpHeader>

    <BuySection></BuySection>

    <LinkSection></LinkSection>

    <endFooter></endFooter>
  
</template>

<style lang="scss" scoped>
  
</style>