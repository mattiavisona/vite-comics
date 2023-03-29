<script>
export default {
  data(){
    return{
      
    }
  }
}

</script>

<template>

  <div class="container">

    <div id="navbar">
        <div id="logo">
          <img src="/img/dc-logo.png" height="80px"  alt="">
        </div>
      <div class="link-list">
          <ul id="list">
              <li>CHARACTERS</li>
              <li>COMICS</li>
              <li>MOVIES</li>
              <li>TV</li>
              <li>GAMES</li>
              <li>COLLECTBILES</li>
              <li>VIDEOS</li>
              <li>FANS</li>
              <li>NEWS</li>
              <li>SHOP</li>
          </ul>
      </div>
    </div>
    <div id="section"> 
      <p> ->Content goes here</p>
    </div>
      
  </div>
</template>

<style lang="scss" scoped>

#navbar{
            background-color: white;
            color: black;

            padding: 8px;
            

            display: flex;
            justify-content: space-around;
            align-items: center
        };

    #list{
            display: flex;
            gap: 40px;
            
            list-style-type: none;
            
            font-weight: bold;
            font-size: small
        };

    li:hover{
        color: blue;
        
        cursor: pointer;
      }
      
      #section{
        font-size: 30px;

        margin-left: 250px ;
        padding-top: 40px;
        padding-bottom: 40px;

        color: white;

      
      
    }
    

        

        

  
</style>