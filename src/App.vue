<template>
  <div id="app">
    <router-view />
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #00ffff;
  font-family: Helvetica;
  
}


@media only screen and (max-width: 560px) {

  .proposal{
 text-align: center;

}
.el-message-box {
  width: 268px !important;
}

}

.el-icon-success {
  display: none !important;
}

.el-icon-close {
  display: none !important;
}



.main {
  background-image:  url('assets/holograph.jpg');
  background-blend-mode: multiply;
  background-color: rgba(0, 0, 0, 0.589);
  background-size: cover;



}

.box0 {

padding-top: 20px;
margin-top: 10px;
padding-bottom: 20px;
border-style: solid;
border-width: 1px;
border-color: azure;
border-radius: 10px;
background: #000;
display: flex;
width: 95vw;
max-width: 720px;
margin: 0px auto 0px auto;
position: relative;
text-align: left;
box-sizing: 1px;
border: none;
border: 1px solid #00ffff;

box-shadow: 0 0 40px #00bfff6e;
}

.box1 {

  padding-top: 20px;
  margin-top: 10px;
  padding-bottom: 20px;
  border-style: solid;
  border-width: 1px;
  border-color: azure;
  border-radius: 10px;
  background: #000;
  display: flex;
  width: 95vw;
  max-width: 720px;
  margin: 0px auto 0px auto;
  position: relative;
  text-align: left;
  box-sizing: 1px;
  border: none;
  border: 1px solid #00ffff;
  box-shadow: 0 0 40px #00bfff6e;
}


.box2 {

  padding: 24px;
  max-width: 1440px;
  max-height: auto;
  margin: 10px;
  border-style: solid;
  border-width: 1px;
  border-color: azure;
  border-radius: 10px;
  background: #191c20;
  margin: 0px auto 0px auto;
  position: relative;
  text-align: left;
  box-sizing: 1px;
  border: none;
  border: 1px solid #00ffff;
  box-shadow: 0 0 40px #00bfff6e;
}


.box3 {
padding: 10px;
width: 28vw;
height: 24vh;
margin: 5rem;
border-style: solid;
border-width: 1px;
border-color: azure;
border-radius: 10px;
background: #191c20;
margin: 2rem auto 0px auto;
position: relative;
text-align: left;
box-sizing: 1px;
border: none;
border: 1px solid #00ffff;
box-shadow: 0 0 40px #00bfff6e;
}



.aw {
  color: rgba(102, 102, 102, 1);
  font-size: 34px;
}
.el-radio__input.is-checked + .el-radio__label {
  color: #00ffff !important;
}
.el-radio__input.is-checked .el-radio__inner {
  border-color: #00ffff !important;
  background: #00ffff !important;
}
.el-radio__inner:hover {
  border: 1px solid #00ffff !important;
}
.sk {
  color: rgba(102, 102, 102, 1);
  font-size: 16px;
  font-weight: bold;
  margin-top: 30px;
}
.skbtn {
  width: 416px;
  height: 50px;
  border-radius: 4px;
  border: 1px solid #ddd;
  line-height: 50px;
  cursor: pointer;
  color: #ddd;
  text-align: center;
  font-size: 14px;
}



.bg-box {
  overflow: hidden;
  height: 188px;
  width: 100%;
}
.el-input__inner {
  background-color: #000 !important;
}

.el-select .el-input.is-focus .el-input__inner {
  border-color: #00ffff !important;
}
.el-select .el-input__inner:focus {
  border-color: #00ffff !important;
}
.el-select-dropdown__item.selected {
  color: #00ffff !important;
}
.el-input.is-active .el-input__inner, .el-input__inner:focus {
  border-color: #00ffff !important;
}
</style>
