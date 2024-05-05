<template>
        <div class="contenedor-chat">
        <header class="cabecera-chat">
            <h1>Chat</h1>
            <div class="configuracion-chat">
                <i class="fas fa-cog"></i>
                <ul class="menu-configuracion">
                    <li><a href="#">Ajustes</a></li>
                    <li><a href="#">Cerrar sesión</a></li>
                </ul>
            </div>
        </header>

        <div class="area-mensajes">
            <ul class="mensajes">
                </ul>
        </div>

        <form class="formulario-chat">
            <div class="grupo-entrada">
                <input type="text" id="mensaje-chat" name="mensaje-chat" placeholder="Escribe tu mensaje...">
                <i class="fas fa-paperclip"></i> </div>
            <button type="submit">Enviar</button>
        </form>
    </div>
</template>

<style>
.contenedor-chat {
    width: 300px;
    height:auto;
    margin: 20px auto;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.cabecera-chat {
    display: flex;
    align-items: center;
    padding: 20px;
    background-color: #f0f0f0;
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
}

.cabecera-chat h1 {
    flex: 1;
    text-align: center;
}

.configuracion-chat {
    margin-left: auto;
    cursor: pointer;
}

.configuracion-chat i {
    font-size: 20px;
    color: #333;
}
</style>
