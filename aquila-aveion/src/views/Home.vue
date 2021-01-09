<template>
  <div class="home">
    <div class="container parent-container">
      <div class="left-side"></div>
      <div class="right-side"></div>
    </div>
    <div class="img-area">
      <img class="image" src="../assets/lady1.png" alt="main-img" />
    </div>
    <div class="mother-list">
      <ul class="list-area">
        <li>HOME</li>
        <li>ABOUT</li>
        <div class="set">
          <img class="img2" src="../assets/best.jpg" alt="circle-img" />
        </div>
        <li>GALLERY</li>
        <li>CONTACT</li>
      </ul>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    // HelloWorld,
  },
};
</script>

<style scoped>
*,
*::before,
*::after {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  margin: 0;
  padding: 0;
}

.parent-container {
  display: flex;
  width: 100%;
  height: 110vh;
  /* background-color: aqua; */
  overflow: hidden;
  position: relative;
}

.left-side {
  width: 50%;
  height: 110vh;
  background-color: #bd0f4d;
}

.right-side {
  width: 50%;
  height: 110vh;
  background-color: #cb2964;
}

.img-area {
  width: 30%;
  height: 80%;
  background-color: #cf2b67;
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
  box-shadow: 0rem 2rem 3rem rgba(0, 0, 0, 0.616);
}

.image {
  height: 100%;
  width: 120%;
  object-fit: contain;
  position: absolute;
  top: 59.8%;
  left: 50%;
  transform: translate(-50%, -50%);
  margin-left: 0.5rem;
}
.list-area {
  display: flex;
  position: absolute;
  flex-direction: row;
  justify-content: space-between;
  width: 40%;
  list-style: none;
}

.img2 {
  border-radius: 50%;
  width: 100px;
  height: 100px;
  position: absolute;
}

.mother-list {
  margin-top: -6rem;
  margin-bottom: 1rem;
  color: #fff;
  display: flex;
  justify-content: center;
  justify-content: space-around;
}

.set {
  padding: 0 auto;
  margin-top: -2rem;
  margin-left: -2rem;
}
</style>