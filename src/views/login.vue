<template>

     <div class="container">
         <div>
           <!-- <img src="../assets/WhatsApp Image 2024-04-25 at 20.17.20.jpeg" alt="Imagen del evento" style="object-fit:scale-down; -->
           <!--  width:200px;
            height:300px;"> -->
         </div>
         <div class="login-container">
             <h2>Iniciar Sesión</h2>
             <form action="/login" method="post">
                 <div class="input-group">
                     <label for="usuario">Usuario:</label>
                     <input type="text" id="usuario" name="usuario" required>
                 </div>
                 <div class="input-group">
                     <label for="contraseña">Contraseña:</label>
                     <input type="password" id="contraseña" name="contraseña" required>
                 </div>
                 <button type="submit">Iniciar Sesión</button>
             </form>
         </div>
     </div>
 </template>

<style>
@media (min-width: 1024px) {



  .container {
    min-height: 100vh;
    display: flex;
    align-items: right;
    max-width: 100%;
  }
  .login-container {
    min-height: 100vh;
    display:table-cell;
    align-items: right;
    max-width: 100%;
  }
  .navbar {
    padding: 0px;
}

img {
  max-width: 100%;
  height: auto;
}

}
</style>
