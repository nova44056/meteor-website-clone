<template>
    <div class="footer content-wrapper">
        <div class="row1">
            <div class="top">
                <h2>Join our newsletter</h2>
                <p>Sign up to receive a monthly email on the latest Meteor</p>
                <p>updates, features, and news!</p>
                <div class="subscribe-now">
                    <h4>SUBSCRIBE NOW </h4>
                    <h4> ></h4>
                </div>
                <br>
                <hr>
                <br>
            </div>
            <div class="grey">
                <img src="https://d14jjfgstdxsoz.cloudfront.net/assets/meteor-logo.svg" alt="">
                <br>
                <p>© 2020 Meteor Software</p>
                <p>Open source downloads supported by <b class="bold">KeyCDN</b> and <b class="bold">StackPath</b></p>
                <div class="sm">
                    <div class="twitter">
                        <i class="fa fa-twitter" aria-hidden="true"></i>
                        <p>Twitter</p>
                    </div>
                    <div class="git">
                        <i class="fa fa-github" aria-hidden="true"></i>
                        <p>Github</p>
                    </div>
                    <div class="youtube">
                        <i class="fa fa-youtube-play" aria-hidden="true"></i>
                        <p>Youtube</p>
                    </div>
                    <div class="facebook">
                        <i class="fa fa-facebook" aria-hidden="true"></i>
                        <p>Facebook</p>
                    </div>
                    <div class="medium">
                        <i class="fa fa-medium" aria-hidden="true"></i>
                        <p>Medium</p>
                    </div>
                </div>
            </div>
        </div>
        <div class="row2">
            <div class="col">
                <h3>DEVELOPERS</h3>
                <p>Install</p>
                <p>Tutorials</p>
                <p>Guide</p>
                <p>Docs</p>
                <p>Galaxy Docs</p>
                <p>Packages</p>
                <p>FAQ</p>
                <p>Forums</p>
                <p>Meetups</p>
                <p>Showcase</p>
                <p>Status</p>
            </div>
            <div class="col">
                <h3>SOLUTIONS</h3>
                <p>Hosting</p>
                <p>Official Partners</p>
            </div>
            <div class="col">
                <h3>COMPANY</h3>
                <p>Careers</p>
                <p>Culture</p>
                <p>Blog</p>
                <p>Contact</p>
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
    .bold{
        color: #1b2448;
        width: max-content;
    }

    .bold:hover{
        border-bottom: 2px solid #F85C4C;
        cursor: pointer;
    }

    .footer{
        margin-top: 100px;
        display: flex;
        justify-content: space-around;
        flex-direction: row;
        font-family: 'Inter', sans-serif;
        margin-top: 200px;
    }
    .row1 {
        display: flex;
        flex-direction: column;
        justify-content: center;
        width: 50%;
    }
    .sm {
        display: flex;
        flex-direction: row;
        align-items: center;
        margin-top: 20px;
    }
    .twitter > p {
        margin-left: 22px;
        margin-top: -19px;
        margin-right: 10px;
    }
    .git > p {
        margin-left: 22px;
        margin-top: -19px;
        margin-right: 10px;
    }
    .youtube > p {
        margin-left: 22px;
        margin-top: -20px;
        margin-right: 10px;
    }
    .facebook > p {
        margin-left: 18px;
        margin-top: -19px;
        margin-right: 10px;
    }
    .medium > p {
        margin-left: 25px;
        margin-top: -19px;
    }

    .grey {
        color: #8D91A3;
        font-size: 16px;
        margin-top: 12px;
    }
    .grey > b {
        color: black;
    }
    .grey > b:hover {
        cursor: pointer;
    }
    .grey > img {
        height: 24px;
        width: 99px;
        margin-bottom: 5px;
    }
    .row2 {
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        margin-left: 30px;
    }
    .col {
        display: flex;
        flex-direction: column;
        margin-right: 60px;
    }
    .col > h3 {
        color: #8D91A3;
        font-size: 16px;
        margin-top: -100px;
    }
    .col > p {
        color: #1B2448;
        font-size: 16px;
        margin-top: -1px;
        width: max-content;
    }
    .col > p:hover{
        border-bottom: 2px solid #F85C4C;
        cursor: pointer;
    }
    .top {
        margin-top: -160px;
    }
    .top > h2 {
        font-size: 29px;
        font-weight: bolder;
        color: #1B2448;
    }
    .subscribe-now {
        display: flex;
        font-size: 16px;
        color: #FF6A3E;
    }
    .subscribe-now h4{
        margin-right: 5px;
    }

    .subscribe-now h4:hover{
        cursor: pointer;
        margin-right: 10px;
        transition: ease .5s;
    }

    .top > p {
        font-size: 18px;
        color: #1B2448;
    }
    .top > hr {
        color: #8D91A3;
        opacity: 0.2;
    }
    .content-wrapper {
        height: 100%;
        position: relative;
    }
    .content-wrapper,
    .wrapper {
        margin-right: auto;
        margin-left: auto;
        padding-right: 30px;
        padding-left: 30px;
        padding-bottom: 30px;
    }
</style>