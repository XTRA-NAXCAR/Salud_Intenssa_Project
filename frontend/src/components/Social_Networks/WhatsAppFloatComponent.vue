<template>
  <div class="whatsapp-chat">
    <a href="https://wa.link/iid2xh" target="_blank" class="whatsapp-icon">
      <i class="bi bi-whatsapp"></i>
    </a>
  </div>
</template>

<style scoped>
.whatsapp-chat {
  position: fixed;
  bottom: 20px;
  right: 20px;
  z-index: 999;
}

.whatsapp-icon {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 80px;
  height: 80px;
  border-radius: 50%;
  text-align: center;
  line-height: 60px;
  font-size: 40px;
  color: white;
  text-decoration: none;
  animation: changeBackgroundColor 0.5s linear infinite alternate;
}

@keyframes changeBackgroundColor {
  0% {
    background-color: #25d366;
  }
  100% {
    background-color: transparent;
  }
}
</style>
