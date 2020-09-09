<template>
    <div class="homepage-wrapper">
        <!-- Javascript section -->
        <div class="section-wrapper">
            <div class="section">
                <img src="../assets/meteor_animation.svg" alt="meteor-animation" class="meteor-animation">
                <div class="text">
                    <h1>
                        Javascript
                    </h1>
                    <h2>
                        Meteor is an open source platform for web, mobile, and desktop used by over half a million developers around the globe to make shipping javascript applications simple, efficient, and scalable.
                    </h2>
                    <button>Get Started</button>
                </div>
            </div>
        </div>
        <!-- fading logo section  -->
        <div class="section-2">
            <h1>Companies using meteor</h1>
                <div class="logos-container logos-container__row-1 logos-container__row--animated">
                    <img src="../assets/QUALCOMM.svg" alt="Qualcomm logo">
                    <img src="../assets/MAZDA.svg" alt="Qualcomm logo">
                    <img src="../assets/IKEA.svg" alt="Qualcomm logo">
                    <img src="../assets/HONEYWELL.svg" alt="Qualcomm logo">
                </div>

                <div class="logos-container logos-container__row-2 logos-container__row--animated">
                    <img src="../assets/DISPATCH.svg" alt="Dispatch logo">
                    <img src="../assets/ROCKET-CHAT.svg" alt="Qualcomm logo">
                    <img src="../assets/MIXMAX.svg" alt="Qualcomm logo">
                    <img src="../assets/CODESIGNAL.svg" alt="Qualcomm logo">
                </div>
        </div>

        <div class="section-3">

            <div class="whyMeteor">

            
            <div class="meteror-detail">
                <h2>Why Meteor?</h2>
                <img src="@/assets/Rectangle.svg" alt="">
                <h3>Integrate Technologies you already use</h3>
                <p>Use popular frameworks and tools, right out-of-the-box. Focus on building features instead of wiring disparate components together yourself.</p>


                <h3>Build apps for any device</h3>
                <p>Use the same code whether you’re developing for web, iOS, Android, or desktop. Hot push new code without app store approval or forcing users to download a new native app.</p>
                
                <h3>Ship more with less code</h3>
                <p>Accomplish in 10 lines what would otherwise take 1,000, thanks to an integrated Javascript stack that extends from the database to the end user's screen.

</p>
            </div>

            
            </div>

            <div class="meteror-img">
                <img src="@/assets/why-meteor.svg" alt="">
            </div>

            
            
           

        </div>


         <div class="integrate">
                <h3>Meteor integrates with</h3>
                <div class="integrate-partner">
                    <img src="@/assets/React.svg" alt="">
                    <img src="@/assets/Vue.svg" alt="">
                    <img src="@/assets/Svelte.svg" alt="">
                    <img src="@/assets/Angular.svg" alt="">
                    <img src="@/assets/graph-ql.svg" alt="">
                    <img src="@/assets/MongoDB.svg" alt="">
                    <img src="@/assets/Cordova.svg" alt="">
                    <img src="@/assets/npm.svg" alt="">

                </div>
            </div>


        


    </div>
</template>

<script>
export default {
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@200;300&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@500&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500&family=Roboto:wght@500&display=swap');
*{
    font-family: 'Inter' ;
}
.section-3{
    background-image: radial-gradient(circle farthest-corner at 50% 0,rgba(239,240,249,.4),rgba(241,242,250,.4) 23%,rgba(245,245,251,.4) 41.25%,rgba(249,250,253,.4) 58.75%,rgba(253,253,254,.4) 77.5%,hsla(0,0%,100%,.4));
    margin-top: 100px;
}


.logos-container{
    margin-top: 150px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
}

.logos-container img{
    margin: 20px;
}

.section-2{
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    /* position: relative; */
}
.text{
    position: absolute;
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
}
.text h1{
    font-size: 55px;
}
.text h2{
    width: 470px;
}
.section-wrapper{
    display: flex;
    justify-content: center;
}
.section{
    display: flex;
    position: relative;
    border-radius: 2rem;
    background-color: #262B59;
    width: 90%;
    height: 35rem;
    justify-content: center;
    align-items: center;
    color: white;
    flex-direction: column;
}
.meteor-animation{
    width: 100%;
    height: inherit;
}

.integrate-partner{
    display: flex;
    justify-content: space-between
}
@keyframes fadeIn {
 0% {
  opacity:0
 }
 6% {
  opacity:1
 }
 27% {
  opacity:1
 }
 33% {
  opacity:0
 }
}

.logos-container__row--animated {
 animation-name:fadeIn;
 animation-duration:8s;
 animation-iteration-count:infinite;
 animation-timing-function:ease-in-out;
 opacity:0
}

.logos-container__row-1{
    position: absolute;
}

.logos-container__row-2{
    position: absolute;
    animation-delay: 4s;
}

.section-3 {
    display: flex;
    padding: 30px 0px;
    padding-left: 100px;
}

.whyMeteor{
    width: 60%;
    display: flex;
}

.meteror-detail {
    max-width: 600px;
    
}

.meteror-detail > h2{
    font-size: 40px;
    font-weight: bold;
    line-height: 0px;
    font-family: 'Playfair Display', serif;
    font-family: 'Roboto', sans-serif;
    letter-spacing: 2px;
}

.meteror-detail > img {
    display: block;
    margin-bottom: 40px;
}
.meteror-img > img{
    height: 100%;
    width: 100%;
    margin-right: -100px;   
}

h3 {
    font-size: 30px;
    font-weight: bold;
    opacity: 0.8;
}

.meteror-detail > p{
    max-width: 430px;
    opacity: 0.4;
    font-size: 18px;
    line-height: 32px;
}

.integrate{
    padding-left: 100px;
    padding-right: 20px;
    margin-bottom: 30px;
}

.integrate > h3 {
    text-align: center;
    font-size: 40px;
    font-weight: 900;
    letter-spacing: -0.3px;
    font-family: 'Roboto';
}
</style>