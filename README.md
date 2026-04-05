# Proyecto Unity: Entorno Jurásico

**Autor:** Isaiah Ontaneda
**Institución:** UDLA
**Asignatura:** Desarrollo de videojuegos

## Descripción del Proyecto
Este repositorio contiene el código fuente y los assets de una escena interactiva desarrollada en Unity. El entorno simula un ecosistema de temática jurásica construido mediante la herramienta nativa Terrain.

## Características de la Escena
* **Diseño Topográfico:** La escena cuenta con elevaciones perimetrales (montañas) texturizadas con material rocoso.
* **Superficies:** El suelo del terreno implementa múltiples capas de texturas, diferenciando zonas de césped y zonas de nieve.
* **Fauna:** Se han integrado modelos 3D correspondientes a tres especies distintas de dinosaurios.
* **Elementos Estructurales:** Se han distribuido cubos geométricos a lo largo de la escena que representan infraestructuras.
* **Físicas:** El jugador y los elementos del entorno cuentan con componentes Rigidbody y Collider para la detección de colisiones e interacciones físicas continuas.

## Ejecución y Navegación
Para ejecutar la escena:
1. Clonar este repositorio localmente mediante `git clone`.
2. Abrir el proyecto a través de Unity Hub (versión compatible con el proyecto).
3. Cargar la escena principal desde el directorio de Assets.
4. Presionar el botón Play en el editor.

### Controles del Jugador
El jugador está representado por una entidad cúbica central sujeta a físicas.
* **Flecha Arriba / W:** Avanzar hacia adelante en el eje local.
* **Flecha Abajo / S:** Retroceder en el eje local.
* **Flecha Izquierda / A:** Rotar la cámara y el modelo sobre el eje vertical hacia la izquierda.
* **Flecha Derecha / D:** Rotar la cámara y el modelo sobre el eje vertical hacia la derecha.
