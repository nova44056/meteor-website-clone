<template>
    <div class="footer">
        <div class="row1">
            <div>
                <h2>Newsletter</h2>
                <p>Sign up to receive a monthly email on the latest Meteor</p>
                <p>updates, features, and news!</p>
                <br>
                <h4>SUBSCRIBE NOW ></h4>
            </div>
            <hr />
            <div class="grey">
                <img src="https://d14jjfgstdxsoz.cloudfront.net/assets/meteor-logo.svg" alt="">
                <br>
                <p>© 2020 Meteor Software</p>
                <p>Open source downloads supported by <b>KeyCDN</b> and <b>StackPath</b></p>
                <div class="sm">
                    <div class="twitter">
                        <p>Twitter</p>
                    </div>
                    <div class="git">
                        <p>Github</p>
                    </div>
                    <div class="youtube">
                        <p>Youtube</p>
                    </div>
                    <div class="facebook">
                        <p>facebook</p>
                    </div>
                    <div class="medium">
                        <p>Medium</p>
                    </div>
                </div>
            </div>
        </div>
        <div class="row2">
            <div class="col">
                <h3>DEVELOPERS</h3>
                <br>
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
                <br>
                <p>Hosting</p>
                <p>Official Partners</p>
            </div>
            <div class="col">
                <h3>COMPANY</h3>
                <br>
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
    .footer{
        display: flex;
        justify-content: space-between;
        flex-direction: row;
    }
    .row1 {
        display: flex;
        flex-direction: column;
        justify-content: center;
    }
    .sm {
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
    }
    .grey {
        color: silver;
    }
    .grey > b {
        color: black;
    }
    .grey > b:hover {
        cursor: pointer;
    }
    .row2 {
        display: flex;
        flex-direction: row;
        justify-content: space-between;
    }
    .col {
        display: flex;
        flex-direction: column;
    }
    .col > h3 {
        color: silver;
    }
</style>