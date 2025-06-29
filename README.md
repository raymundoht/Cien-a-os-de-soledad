#  Cien Años de Soledad - Análisis Narrativo con NLP

Este proyecto aplica técnicas de **procesamiento de lenguaje natural (NLP)** para analizar la novela *Cien años de soledad* de Gabriel García Márquez. A través de un backend en Node.js y una estructura de modelos literarios, permite explorar los personajes, lugares, eventos y objetos dentro de la historia.

##  Características

-  Procesamiento de preguntas con NLP (preguntas como "¿Dónde vivió Aureliano?" o "¿Qué objetos usó Amaranta?")
-  Modelado de datos narrativos: personajes, lugares, eventos, objetos, generaciones.
-  Análisis de capítulos y relaciones entre entidades narrativas.
-  Backend en Node.js con rutas API para acceder a la información.

##  Tecnologías Usadas

- Node.js
- Express.js
- MongoDB
- JavaScript
- NLP personalizado (`nlpProcessor.js`)
- Mongoose (ORM)

## 📁 Estructura del Proyecto

```
Cien_A-os-main/
├── server.js                 # Servidor principal
├── nlpProcessor.js          # Procesamiento de lenguaje natural
├── models/                  # Modelos Mongoose para cada entidad narrativa
│   ├── model_personajes.js
│   ├── model_lugares.js
│   ├── model_eventos.js
│   └── ...
├── package.json             # Configuración del proyecto Node
```

##  Cómo ejecutar el proyecto

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tuusuario/Cien_A-os-main.git
   cd Cien_A-os-main
   ```

2. Instala las dependencias:
   ```bash
   npm install
   ```

3. Ejecuta el servidor:
   ```bash
   node server.js
   ```

4. Accede a las rutas en tu navegador o con Postman:  
   Ejemplo: `http://localhost:3000/personajes`

##  Ejemplo de uso

Puedes hacer preguntas como:
- `"¿Dónde vivió José Arcadio Buendía?"`
- `"¿Qué eventos ocurrieron en Macondo?"`

El procesador NLP interpreta la pregunta y accede a la base de datos para dar una respuesta contextualizada.

