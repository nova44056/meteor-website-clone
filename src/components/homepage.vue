<template>
    <div class="homepage-wrapper">
        <!-- Javascript section -->
        <div class="section-wrapper">
            <div class="section">
                <div class="sky-container">
                    <div class="star"></div>
                    <div class="star"></div>
                    <div class="star"></div>
                    <div class="star"></div>
                    <div class="star"></div>
                </div>
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

.sky-container {
  /* width: 500px;
  height: 500px;
  background: linear-gradient(125deg, #00103a 0%, #3e5f77 100%);
  clip-path: circle(50% at 50% 50%);
  border-radius: 50%; */
  transform: rotateZ(45deg);
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
    overflow: hidden;
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


.star {
  position: absolute;
  top: 50%;
  left: 50%;
  height: 2px;
  background: linear-gradient(-45deg, #c15744, rgba(0, 0, 255, 0));
  filter: drop-shadow(0 0 6px #c15744);
  animation: tail 3000ms ease-in-out infinite, shooting 3000ms ease-in-out infinite;
}

.star::before, .star::after {
  position: absolute;
  content: '';
  top: calc(50% - 1px);
  right: 0;
  height: 2px;
  background: linear-gradient(-45deg, rgba(0, 0, 255, 0), #c15744, rgba(0, 0, 255, 0));
  border-radius: 100%;
  animation: shining 3000ms ease-in-out infinite;
}


.star:nth-child(1) {
  top: calc(50% - 200px);
  left: calc(50% - 300px);
  animation-delay: 650ms;
}
.star:nth-child(1)::before, .star:nth-child(1)::after {
  animation-delay: 650ms;
}

.star:nth-child(2) {
  top: calc(50% - -50px);
  left: calc(50% - 190px);
  animation-delay: 150ms;
}
.star:nth-child(2)::before, .star:nth-child(2)::after {
  animation-delay: 150ms;
}

.star:nth-child(3) {
  top: calc(50% - -90px);
  left: calc(50% - 200px);
  animation-delay: 1600ms;
}
.star:nth-child(3)::before, .star:nth-child(3)::after {
  animation-delay: 1600ms;
}

.star:nth-child(4) {
  top: calc(50% - 50px);
  left: calc(50% - 250px);
  animation-delay: 4700ms;
}
.star:nth-child(4)::before, .star:nth-child(4)::after {
  animation-delay: 4700ms;
}

.star:nth-child(5) {
  top: calc(50% - -190px);
  left: calc(50% - 200px);
  animation-delay: 2100ms;
}
.star:nth-child(5)::before, .star:nth-child(5)::after {
  animation-delay: 2100ms;
}




/* Animations */
@keyframes tail {
  0% {
    width: 0;
  }
  
  30% {
    width: 100px;
  }
  
  100% {
    width: 0;
  }
}

@keyframes shining {
  0% {
    width: 0;
  }
  50% {
    width: 30px;
  }
  100% {
    width: 0;
  }
}

@keyframes shooting {
  0% {
    transform: translateX(0);
  }
  100% {
    transform: translateX(320px);
  }
}
</style>