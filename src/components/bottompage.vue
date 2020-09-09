<template>
	<div class="finalpart">
		<div class="section-4">
			<div class="buildmeteor">
				<div class="meteror-detail">
                    <div>
                        <h2>Build with</h2>
                        <h2>Meteor</h2>
                    </div>
					<img src="@/assets/Rectangle.svg" alt="" />
                    <p>PATHABLE</p>
                    <p>MAESTRO</p>
                    <p>LEMLIST</p>
                    <p>CHATRA</p>
                    <p>CODESIGNAL</p>
                    <i class="fa fa-arrow-circle-o-right" aria-hidden="true"></i>
                    <H4>VIEW MORE</H4>
				</div>
                <div class="pathable-wrapper">
                    <img src="@/assets/pathable-logo.svg" alt="pathable-logo" class="pathable-logo">

                    <div class="pathable-wrapper-bottom">
                        <div class="pathable-wrapper-content">
                            <h3>
                                Mobile Events App & Conference Microsites
                            </h3>
                            <p> Pathable </p>
                            <p>
                                Pathable's platform produces white label mobile apps and websites for conferences, tradeshows and meetings for all types
                            </p>
                        </div>
                        <img src="@/assets/Pathable-bg.jpg" alt="Pathable-bg" class="pathable-bg">
                    </div>
                </div>
			</div>
		</div>
		<div class="section-5">
			<div class="center">
                <h2>Commercial Services</h2>
                </div>
			<div class="comser">
				<div class="col img1">
                    <img src="@/assets/official5.svg" alt="">
                    <h2>Enterprise Support</h2>
                    <p>Confidently host your application on Galaxy</p>
                    <p>Hosting with premium support, including</p>
                    <p>guaranteed support response times and</p>
                    <p>critical SLA commitments.</p>
                    <br>
                    <button>GET PAID SUPPORT</button>
                    </div>
				<div class="col bg img2">
                    <img src="@/assets/effortless_2.svg" alt="">
                    <h2>Effortless Meteor Hosting</h2>
                    <p>Stop wasting time on devops. Deploy your</p>
                    <p>app using Galaxy, the easiest way to scale</p>
                    <p>and manage your Meteor applications.</p>
                    <br>
                    <button>GET METEOR HOSTING</button>
                </div>
				<div class="col img3">
                    <img src="@/assets/global2.svg" alt="">
                    <h2>Global Partner Network</h2>
                    <p>Choose from hundreds of Official Meteor</p>
                    <p>Partners to help you with application </p>
                    <p>development and training</p>
                    <br>
                    <button>FIND A PARTNER</button>
                </div>
			</div>
		</div>
        <br>
        <br>
        
        <div class="section-6">
            <div class="flex">
                <div class="row1">
                    <h3>Community</h3>
                    <div class="move">
                    <h1>Build great applications</h1>
                    <h1>faster than ever using</h1>
                    <h1>Meteor.</h1>
                    </div>
                    <p>Join the community of developers from all</p>
                    <p>over the world that rely on Meteor.</p>
                    <br>
                    <button>GET STARTED NOW</button>
                </div>
                <div class="row2">
                    <p>14,223</p>
                    <h5>PACKAGES</h5>
                    <p>163</p>
                    <h5>PARTNERS</h5>
                    <p>28,681</p>
                    <h5>STACK OVERFLOW QUESTIONS</h5>
                    <p>508,000+</p>
                    <h5>UNIQUE INSTALLS</h5>
                </div>
            </div>
        </div>
	</div>
</template>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500&family=Roboto:wght@500&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Inter:wght@200;300&display=swap");
.pathable-wrapper-bottom{
    display: flex;
    flex-direction: row;
    align-items: center;
}

.pathable-bg{
    width: 600px;
    height: 400px;
}
.pathable-wrapper-content{
    color:white;
    margin: 2rem;
}

.pathable-logo{
    height: 100px;
    width: 100px;
    margin: 3rem;
}

.pathable-wrapper{
    background-color: #252B58;
    border-radius: 2rem;
}

.fa{
    font-size: x-large;
}

.section-4 {
	display: flex;
    justify-content: center;
	/* padding: 30px 0px;
	padding-left: 100px; */
}
.meteror-detail{
    width: 30rem;
}

.meteror-detail > h2 {
	font-size: 40px;
	font-weight: bold;
	line-height: 0px;
	font-family: "Playfair Display", serif;
	font-family: "Roboto", sans-serif;
	letter-spacing: 2px;
}
.meteror-detail > p {
    font-size: 16px;
    font-family: "inter", sans-serif;
    color: #8D91A3;
}
.meteror-detail > h4 {
    font-size: 16px;
    color: #1B2448;
    font-family: "inter", sans-serif;
    margin-left: 25px;
    margin-top: -19px;
}
.buildmeteor {
	width: 60%;
	display: flex;
}
.center {
    display: flex;
    justify-content: center;
    align-items: center;
}
.comser {
    display: flex;
    justify-content: center;
    margin-right: 10px;
    border: 1px solid white;
    border-radius: 10px;
    flex-direction: row;
}
.col {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    margin-right: 40px;
    box-shadow: 7px 7px 20px -10px rgba(13,17,33,.25), 0 1px 3px 0 rgba(27,36,72,.16);
    transition: box-shadow .2s ease;
    padding-right: 10px;
    padding-left: 10px;
    border-radius: 20px;
    height: 480px;
    width: 388px;
    font-family: "inter", sans-serif;
}
.bg {
    background-color: #1B2448;
    color: #FFFFFF;
}
.section-5 {
    display: flex;
    padding: 30px 0px;
    flex-direction: column;
}
.img1 > img {
    margin-top: -50px;
}
.img1 > h2 {
    margin-top: 35px;
    font-size: 24px;
    margin-bottom: 40px;
}
.img1 > p {
    margin-top: -9px;
    color: #8D91A3;
    font-size: 16px;
}
.img2 > img {
    margin-top: -60px;
}
.img2 > h2 {
    margin-bottom: 40px;
}
.img2 > p {
    margin-top: -9px;
    font-size: 16px;
}
.img3 > img {
    margin-top: -5px;
}
.img3 > h2 {
    margin-top: 35px;
    font-size: 24px;
    margin-bottom: 40px;
}
.img3 > p {
    margin-top: -9px;
    color: #8D91A3;
    font-size: 16px;
}
.center > h2 {
    font-size: 40px;
    color: #1B2448;
    font-family: "inter", sans-serif;
    margin-bottom: 60px;
}
.img1 > button {
    height: 52px;
    width: 201px;
    border: 2px solid #595DFF;
    border-radius: 8px;
    background-color: #FFFFFF;
    color: #595DFF;
    font-size: 16px;
    padding: 14px 18px;
    font-weight: bold;
    margin-top: 20px;
}
.img1 > button:hover {
    cursor: pointer;
    background-color: #595DFF;
    color: #FFFFFF;
}
.img2 > button {
    height: 52px;
    width: 230px;
    border: 2px solid #595DFF;
    border-radius: 8px;
    background-color: #1B2448;
    color: #FFFFFF;
    font-size: 16px;
    padding: 14px 18px;
    font-weight: bold;
    margin-top: 20px;
}
.img2 > button:hover {
    cursor: pointer;
    background-color: #595DFF;
}
.img3 > button {
    height: 52px;
    width: 178px;
    border: 2px solid #595DFF;
    border-radius: 8px;
    background-color: #FFFFFF;
    color: #595DFF;
    font-size: 16px;
    padding: 14px 18px;
    font-weight: bold;
    margin-top: 20px;
}
.img3 > button:hover {
    cursor: pointer;
    background-color: #595DFF;
    color: #FFFFFF;
}
.section-6 {
    background-image: url(../assets/bottom-bg.webp);
    background-repeat: repeat;
    background-position: 50% 80%, 0px 0px, 100% 100%;
    background-color: #1B2448;
    height: 584px;
    width: max;
    font-family: "inter", sans-serif;
}
.flex {
    display: flex;
    flex-direction: row;
    padding: 100px 40px;
    justify-content: space-between;
    margin-top: 15px;
}
.row1 {
    display: flex;
    justify-content: center;
    flex-direction: column;
    margin-top: -30px;
    margin-left: 300px;
}
.row1 > h3 {
    color: #FF6A3E;
    font-size: 24px;
    margin: 0px 0px 8px;
}
.row1 > h1 {
    margin-top: -10px;
    color: #FFFFFF;
    font-size: 32px;
    font-weight: bold;
    margin-bottom: -10px;
}
.move {
    margin-top: -10px;
    color: #FFFFFF;
    font-weight: bolder;
    margin-bottom: 10px;
}
.row1 > p {
    color: #FFFFFF;
    margin-top: -10px;
    margin-bottom: 20px;
}
.row1 > button {
    height: 52px;
    width: 202px;
    border: 2px solid #595DFF;
    border-radius: 8px;
    background-color: #595DFF;
    color: #FFFFFF;
    font-size: 16px;
    padding: 14px 18px;
    font-weight: bold;
}
.row1 > button:hover {
    cursor: pointer;
    background-color: #595DFF;
    opacity: 0.9;
}
.row2 {
    display: flex;
    justify-content: center;
    flex-direction: column;
    margin-right: 300px;
}
.row2 > p {
    color: #FFFFFF;
    font-size: 28px;
    margin-top: 0px;
}
.row2 > h5 {
    color: #FF6A3E;
    font-size: 16px;
    margin-top: -20px;

}
</style>
