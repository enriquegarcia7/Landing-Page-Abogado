<template>
  <a
    href="https://wa.me/56931766391?text=Hola%20quiero%20mas%20información"
    target="_blank"
    rel="noopener noreferrer"
    class="whatsapp-link"
  >
    <img
      src="/whatsapp-icon.png"
      alt="WhatsApp"
      class="whatsapp-icon"
    >
  </a>
</template>

<script setup lang="ts">
// Aquí puedes agregar cualquier lógica que necesites para el componente, si es necesario
</script>

<style scoped>
.whatsapp-link {
  position: fixed;
  bottom: 100px;
  right: 20px;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #25d366; /* Color de fondo de WhatsApp */
  color: white;
  padding: 15px; /* Aumenta el padding para hacer el botón más grande */
  border-radius: 50%;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
  text-decoration: none;
  z-index: 1000; /* Asegura que el enlace esté encima de otros elementos */
}

.whatsapp-icon {
  width: 50px; /* Aumenta el tamaño del ícono */
  height: 50px; /* Aumenta el tamaño del ícono */
}
</style>
