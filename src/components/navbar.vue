<template>
  <div class="header">
    <img
      src="https://d14jjfgstdxsoz.cloudfront.net/assets/meteor-logo.svg"
      alt=""
    />
    <div class="header-nav">
      <div class="nav-developer">
        <span>Developers</span>
        <div class="nav-content" id="developer">
          <p>Install</p>
          <p>Why Meteor</p>
          <p>Tutorial</p>
          <p>Docs</p>
          <p>Package</p>
          <p>FAQ</p>
          <p>Forum</p>
          <p>Showcase</p>
        </div>
      </div>
      <div class="nav-hosting">
        <span>Hosting</span>
        <div class="nav-content" id="developer">
          <p>Pricing</p>
          <p>Why Galaxy</p>
          <p>Galaxy Docs</p>
        </div>
      </div>
      <div class="nav-company ">
        <span>Company</span>
        <div class="nav-content" id="developer">
          <p>Culture</p>
          <p>Career</p>
          <p>Partner</p>
          <p>Blogs</p>
        </div>
      </div>
      <button class="sign-up">SIGN UP</button>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Inter:wght@200;300&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Inter:wght@200;300;400&family=Kumbh+Sans&display=swap");

.header {
  display: flex;
  justify-content: space-between;
  padding: 20px 40px;
}
.header > img {
  width: 5%;
  margin-top: -3px;
}
.header-nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 500px;
  font-family: "Inter";
}
.header-nav > div {
  display: inline-block;
}

.nav-developer:hover #developer {
  display: block;
}
.nav-hosting:hover #developer {
  display: block;
}
.nav-company:hover #developer {
  display: block;
}
button {
  padding: 15px 30px;
  background-color: #595dff;
  color: white;
  border: none;
  font-weight: 900;
  border-radius: 10px;
  box-sizing: border-box;
  font-size: 15px;
}

button:hover {
  cursor: pointer;
  background-color: #4f53df;
}

.nav-content {
  display: none;
  position: absolute;
  padding: 5px 15px;
  box-sizing: border-box;
  line-height: 15px;
  border-radius: 5px;
  min-width: 120px;
  font-weight: 700;
  font-family: "Inter", sans-serif;
  font-family: "Kumbh Sans", sans-serif;
  color: #8d91a3;
  box-shadow: 4px 4px 12px 0 rgba(27, 36, 72, 0.08),
    1px 1px 3px 0 rgba(27, 36, 72, 0.16);
  z-index: 1;
  background-color: white;
}

.header-nav > div:hover {
  cursor: pointer;
}
.nav-content > p:hover {
  color: #1B2448;
  cursor: pointer;
}
</style>
