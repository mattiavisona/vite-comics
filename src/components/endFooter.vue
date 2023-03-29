<script>



</script>

<template>
  
    <footer id="end-footer">
        <div class="footer-container">
        
            <div id="sign-up">
                Sign up Now
            </div>
            
            <div id="social-list">
                
                <ul class="list">
                    <li><span id="follow">follow us</span></li>
                    <li><img src="/img/footer-facebook.png" alt="facebook"></li>
                    <li><img src="/img/footer-twitter.png" alt="twitter"></li>
                    <li><img src="/img/footer-youtube.png" alt="youtube"></li>
                    <li><img src="/img/footer-pinterest.png" alt="pinterest"></li>
                    <li><img src="/img/footer-periscope.png" alt="periscope"></li>
                </ul>
            </div>
        </div>
    </footer>
  
</template>

<style lang="scss" scoped>

    #end-footer{
        background-color: #303030;

        height: 100px;

        

    }
    #sign-up{
        color: white;

        font-weight: bold;

        border: 1px solid blue;
        width: fit-content;
        padding: 10px;
    }
  
    #follow{
        text-transform: uppercase;
        font-weight:bold;
        
        color: blue;

        position: absolute;
        right: 650px;
        bottom: 100px;
    }

    .footer-container{
        display: flex;
        justify-content: space-around;

        align-items: center;

        padding-top: 20px;
        
    }

    .list{
        list-style-type: none;
        display: flex;
        gap: 15px;
    }

    
</style>