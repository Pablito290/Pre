# Proyecto VR Mejorado - Interacción Humano-Computador

## Descripción

Este proyecto es una mejora de un proyecto de realidad virtual (VR) proporcionado por la empresa CERV, desarrollado por un grupo de tres estudiantes: **Pablo Carazas**, **Camila Luque**, y **Mauricio Apaza**. Nuestro objetivo fue añadir nuevas funcionalidades y mejorar la interacción con los vehículos en el entorno virtual.

Debido al tamaño del proyecto, solo se han subido **dos packages** que contienen los cambios principales que implementamos. El proyecto completo no pudo ser subido por limitaciones de espacio.


## Mejoras Implementadas

### 1. Modo Focus
- Se agregó un nuevo modo llamado **Modo Focus**, el cual permite a los usuarios seleccionar un vehículo y desarmarlo virtualmente. Esto permite visualizar las piezas de manera detallada.
- En el Modo Focus, los usuarios pueden alternar entre dos vistas:
  - **Vista normal del vehículo**.
  - **Vista de piezas coloreadas según su estado**:
    - **Verde**: Buen estado.
    - **Amarillo**: Estado regular.
    - **Rojo**: Mal estado.
- Un **canvas** muestra el estado de las piezas del vehículo en porcentaje, indicando de manera clara cuán dañadas o en buen estado están las diferentes partes.
- Además, el **desarme del vehículo** permite al usuario inspeccionar cada una de las piezas individualmente y ver su condición.
- Se agregó un **minimapa** que muestra la posición del vehículo seleccionado, permitiendo una mejor navegación y orientación dentro del **Modo Focus**.

### 2. Zoom Mejorado
- Mejoramos la función de zoom, permitiendo a los usuarios acercarse y alejarse de los vehículos de manera más precisa y fluida.

### 3. Selección de Vehículos
- Implementamos la funcionalidad de seleccionar vehículos en el entorno VR. El usuario puede elegir el vehículo con el que desea interactuar, y esto activa el **Modo Focus**.

## Controles en Modo Focus
- **Botón 1**: Alternar entre la vista normal del vehículo y la vista de piezas coloreadas por estado.
- **Botón 2**: Regresar al modo de vista normal del vehículo.

## Video Demostrativo

Mira un video demostrativo de nuestro proyecto aquí: [Enlace al video](https://www.tu-enlace-video.com)

## Créditos

Este proyecto fue desarrollado por:
- **Pablo Carazas**
- **Camila Luque**
- **Mauricio Apaza**
