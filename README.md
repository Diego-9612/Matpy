# 📛 Mapty: App de Entrenamientos Geolocalizados

Una aplicación construida con **JavaScript puro** que permite a los usuarios registrar sus entrenamientos de **running** y **ciclismo** en un mapa interactivo. Utiliza funcionalidades modernas del navegador como **Geolocalización** y **almacenamiento local**, ofreciendo una experiencia rica y persistente sin necesidad de backend.

---

## 📄 Descripción General

**Mapty** es una aplicación de seguimiento de actividades físicas como correr o andar en bicicleta, integrando un mapa dinámico que registra cada entrenamiento mediante formularios inteligentes. Permite:

* Obtener automáticamente tu ubicación usando la API de Geolocalización.
* Registrar diferentes tipos de entrenamiento con métricas personalizadas.
* Visualizar los entrenamientos en una lista y como pines interactivos en el mapa.
* Almacenar los datos de forma persistente usando LocalStorage.
* Navegar entre entrenamientos haciendo clic en los ítems de la lista.

Este proyecto fue desarrollado como parte de un curso avanzado de JavaScript, y representa una aplicación del mundo real enfocada en el aprendizaje de integración de APIs del navegador, manipulación del DOM, clases, eventos y almacenamiento.

---

## 🚀 Tecnologías Utilizadas

* JavaScript (ES6+)
* HTML5 y CSS3
* API de Geolocalización del Navegador
* Leaflet.js (librería de mapas interactivos)
* LocalStorage

---

## ⚙️ Instalación y Ejecución

1. Clona este repositorio:

```bash
git clone https://github.com/tuusuario/mapty-app.git
```

2. Abre el archivo `index.html` directamente en tu navegador:

```bash
cd mapty-app
open index.html
```

> ✅ No necesitas servidor backend ni instalación de dependencias. Solo necesitas un navegador moderno.

---

## 🧪 Instrucciones de Uso

1. Permite que el navegador acceda a tu ubicación.
2. Haz clic en el mapa para crear un nuevo entrenamiento.
3. Completa el formulario con los datos requeridos:

   * Tipo de entrenamiento: Correr o Bicicleta
   * Distancia, duración, cadencia o elevación según el tipo
4. Presiona Enter y verás el entrenamiento listado a la izquierda y marcado en el mapa.
5. Haz clic en un ítem del listado para centrar el mapa en ese punto.

---

## 📁 Estructura del Proyecto

```
mapty-app/
├── index.html
├── style.css
├── script.js
├── resources/
│   └── diagramas (opcional)
```

* `index.html`: Estructura HTML base
* `style.css`: Estilos personalizados
* `script.js`: Lógica de toda la aplicación

---

## ✅ Pruebas

No se incluyeron pruebas automatizadas, ya que el enfoque fue educativo y orientado a la integración de APIs del navegador y manejo del DOM. Puedes validar el comportamiento funcional directamente en el navegador.

---

## 👤 Contribuciones

¡Claro que sí! Las contribuciones son bienvenidas.

1. Haz un fork del repositorio
2. Crea tu rama: `git checkout -b feature/nueva-funcionalidad`
3. Haz commit de tus cambios: `git commit -m 'Añadir nueva funcionalidad'`
4. Push a la rama: `git push origin feature/nueva-funcionalidad`
5. Abre un Pull Request 🚀

---

## 🔐 Licencia

Distribuido bajo la Licencia MIT. Consulta `LICENSE` para más información.

---

## 📬 Contacto

Diego Guerrero, Codeweb Studio – [TuCorreo@ejemplo.com](diego.guerrero9612@gmail.com)

Proyecto del curso avanzado de JavaScript basado en la aplicación *Mapty*.

---

> 💡 Este proyecto es una excelente base para ampliar a una Progressive Web App, integrar almacenamiento en la nube o agregar autenticación para múltiples usuarios.

