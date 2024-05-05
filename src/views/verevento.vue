<template>
      <nav class="navbar">
              <div class="logo">
                  <!-- <img src="../assets/logo.jpeg" alt="Logo" id="logo"> -->
              </div>
          </nav>
          <header>
              <h1>URBAN UNITY</h1>
          </header>
          <div class="event-details">
              <table>
                      <h1>Evento: Taller de cocina italiana para principiantes</h1>
                  
                  <tr>
                      <th>Detalle del evento</th>
                      <td>En este taller aprenderás las técnicas básicas de la cocina italiana y prepararás algunos platos tradicionales como pasta fresca, risotto y tiramisú.</td>
                      <td colspan="2" class="image-cell">
                          <img src="../assets/WhatsApp Image 2024-04-25 at 20.17.20.jpeg" alt="Imagen del evento" width="200">
                      </td>
                  </tr>
                  <tr>
                      <th>Ubicación</th>
                      <td>Escuela de cocina "El Sabor", Calle Mayor 123, Ciudad</td>
                  </tr>
                  <tr>
                      <th>Fecha y hora</th>
                      <td>Sábado 25 de marzo de 2024, de 10:00 a 14:00</td>
                  </tr>
                  <tr>
                      <th>Categorías</th>
                      <td>Gastronomía, Taller</td>
                  </tr>
                      
              </table>
          </div>
          <div>
              <a href="#" class="join-button">Unirse</a>
          </div>
</template>

<style scoped>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}

.join-button {
    background-color: #4caf50;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    width: 100%;
}

button:hover {
    background-color: #45a049;
}
</style>
