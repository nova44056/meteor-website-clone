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
            Hi
        </div>

    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
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
</style>