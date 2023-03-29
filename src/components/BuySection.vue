<script>
export default {
  
  name: 'AppBuy',

  data() {
    return {
      buyObjects: [
        {
          title: "Digital Comics",
          img: "buy-comics-digital-comics.png",
        },
        {
          title: "DC Merchandise",
          img: "buy-comics-merchandise.png",
        },
        {
          title: "Subscription",
          img: "buy-comics-subscriptions.png",
        },
        {
          title: "Comic Shop Locator",
          img: "buy-comics-shop-locator.png",
        },
        {
          title: "DC Power Visa",
          img: "buy-dc-power-visa.svg",
        },
      ],
    }
  },
}
</script>

<template>
  <div id="buy-elements-container">

    <a v-for="buyObject in buyObjects" href="#" class="buy-element">

      <img :src="'/img/' + buyObject.img" alt="" class="icon">
      <span class="title"> {{ buyObject.title }} </span>

    </a>

  </div>
</template>

<style lang="scss" scoped>
#buy-elements-container  {
  display: flex;
  flex-flow: row nowrap;
  justify-content: center;
  gap: 70px;
  padding: 50px;
  
  background-color: blue;
  .buy-element {
    display: flex;
    flex-direction: row;
    align-items: center;
    gap: 25px;
    .icon {
      height: 3.5em;
    }
   
    .title {
      color: white;
      text-transform: uppercase;
    }
  }

  .buy-element:hover{
    opacity: .8;
  }
}
</style>