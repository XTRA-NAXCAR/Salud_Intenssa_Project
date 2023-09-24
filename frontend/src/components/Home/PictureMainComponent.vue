<template>
  <div class="container-fluid px-0">
    <div class="image-wrapper">
      <img
        alt="..."
        src="@/assets/images/home/pictureMain.jpeg"
        class="image-element"
      >
      <div class="custom-box">
        <div class="text-align-start">
          <h2 class="title-font">SALUD INTENSSA MEDICINA ANTIENVEJECIMIENTO</h2>
          <p class="description-font d-none d-md-inline">Procedimientos personalizados, mínimamente invasivos.</p>
        </div>

      </div>
    </div>
  </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@500&display=swap');
.title-font{
  font-family: 'Roboto', sans-serif;
  font-weight: 600;
  font-size: 29px;
  margin-top: 30px;
  color: #fff;
}
.description-font{
  font-family: 'Roboto', sans-serif;
  font-weight: 300;
  font-size: 20px;
  margin-top: 15px;
  color: #fff;
}
.image-wrapper {
  position: relative;
  width: 100%;
  padding-bottom: 56.25%;
  overflow: hidden;
}

.image-element {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.custom-box {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 700px; 
  height: 175px; 
  background-color: #d1b684;
  box-sizing: border-box;
  padding-left: 30px;
  border-top-right-radius: 25px;
}

@media (max-width: 576px) {
  .image-wrapper{
    height: 400px;
  }
  .custom-box{
    width: 250px;
    height: 120px;
    padding-left: 10px;
  }
  .title-font{
    font-size: 20px;
  }
}

@media (min-width: 577px) and (max-width: 991px) {
  .image-wrapper{
    height: 600px;
  }
  .custom-box{
    width: 600px;
  }
}
</style>

