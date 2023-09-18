<template>
    <div class="whatsapp-chat">
      <a href="https://wa.link/9qcqr7" target="_blank" class="whatsapp-icon">
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
    background-color: #25d366; /* Puedes personalizar el color de fondo */
    border-radius: 50%;
    text-align: center;
    line-height: 60px;
    font-size: 40px;
    color: white; /* Puedes personalizar el color del ícono */
    text-decoration: none;
    transition: background-color 0.3s ease;
  }
  
  .whatsapp-icon:hover {
    background-color: #128C7E; /* Cambia el color de fondo en el hover */
  }
  </style>
  