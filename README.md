# 04-Crear-una-red-virtual
En este tutorial vamos a crear una red virtual, a implementar dos máquinas virtuales en esa red virtual y despues de confugrarlas correctamente, permitir que una de las máquinas virtuales haga ping a la otra dentro de esa red.

## Tarea 1: Crear una red virtual (20 minutos)
Primero, crearemos una red virtual.

  1. Inicie sesión en Azure Portal en https://portal.azure.com

  2. Desde la hoja *Todos los servicios*, busque y seleccione *Redes virtuales* y, luego, haga clic en *Agregar*.

  3. En la hoja de *Crear red virtual* complete con lo siguiente (deje los valores predeterminados para todo lo demás):

| Configuración | Valores |
    |  -- | -- |
    | Nombre | **vnet1** |
    | Espacio de direcciones | 10.1.0.0/16 |
    | Suscripción | Seleccione su suscripción |
    | Grupo de recursos | **myRGVNet** (crear nuevo) |
    | Ubicación | **Este de EE. UU.** |
    | Subred-Nombre | Predeterminado |
    | Rango de dirección de subred | **10.1.0.0/24** |
    | | |
   
   
   
   
     | Configuración | Valores |
    |  -- | -- |
    | Nombre | **vnet1**|
    | Espacio de direcciones | 10.1.0.0/16 |
    | Suscripción | Seleccione su suscripción |
    | Grupo de recursos | **myRGVNet** (crear nuevo)|
    | Ubicación | **Este de EE. UU.**|
    | Subred-Nombre | Predeterminado|
    | Rango de dirección de subred | Predeterminado |
    | | |
   
    img1
    
    
    img2
    
  4. Haga clic en el botón Revisar y crear. Asegúrese de que la validación sea exitosa.

  5. Haga clic en el botón Crear para implementar la red virtual.

Nota: En su organización, ¿cómo sabrá qué redes virtuales y direccionamiento IP necesitará?

## Tarea 2: Crear dos máquinas virtuales
En esta tarea crearemos dos máquinas virtuales en la red virtual.

  1. Desde la hoja Todos los servicios, busque Maquinas virtuales y luego haga clic en Agregar.

  2. En la pestaña Datos básicos, complete la siguiente información (deje los valores predeterminados para todo lo demás):
