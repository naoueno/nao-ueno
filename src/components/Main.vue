<template>
  <div id="mainSection">
    <div id="userName">
      N.Ueno
    </div>
    <div id="companyName">
      SeattleConsulting
    </div>
    <img
      id="profilePicture"
      src="../assets/css/profile.png"
    >
  </div>
</template>

<script>
export default {
  name: 'Main',
    msg: String
}
</script>

<style scoped>
@import url(https://www.google.com/get/noto/);
#mainSection {
  background: linear-gradient(180deg, #99FFCC, #06C1E6);
  padding-bottom: 30px;
  text-align: center;
}
#userName {
  color: #FFFFFF;
  font-family: 'Noto Suns';
  font-weight: bold;
  font-size: 18pt;
  text-shadow: 0px 0.5px 2px black;
  padding: 20px 0;
  display: inline-block;
  border-bottom: 1px solid#FFFFFF;
  margin-left: auto;
  margin-right: auto;
}
#companyName {
  padding-top: 20px;
  padding-bottom: 20px;
  color: #FFFFFF;
  font-family: 'Noto Suns';
  font-weight: bold;
  font-size: 18pt;
  text-shadow: 0px 0.5px 2px black;
}
#profilePicture {
  border-radius: 50%;
  width: 100px;
  height: 100px;
}
</style>
