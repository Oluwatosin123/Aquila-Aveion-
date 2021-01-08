<template>
  <div class="home">
    <div class="container parent-container">
      <div class="left-side"></div>
      <div class="right-side"></div>
    </div>
    <div class="img-area">
      <div class="image">
        <img src="../assets/lady1.png" alt="main-img" />
      </div>
    </div>
    <div>
      <ul class="list-area">
        <li>HOME</li>
        <li>ABOUT</li>
        <div class="img2">
          <img src="../assets/best-Copy.jpg" alt="circle-img" />
        </div>
        <li>GALERRY</li>
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

.parent-container {
  display: flex;
  width: 100%;
  height: 100vh;
  background-color: aqua;
  overflow: hidden;
  position: relative;
}

.left-side {
  width: 50%;
  height: 100vh;
  background-color: #bd0f4d;
}

.right-side {
  width: 50%;
  height: 100vh;
  background-color: #cb2964;
}

.img-area {
  width: 100px;
  height: 50px;
  background-color: #cf2b67;
  background-color: #082214;
  position: absolute;
  left: 10rem;
  top: 15rem;
}
.list-area {
  display: flex;
}

.img2 {
  border-radius: 50%;
  width: 50px;
  height: 50px;
  position: absolute;
}
</style>