
---

## 🛠️ Instalación y Uso

### Opción 1: Abrir directamente en el navegador

1. Clona o descarga este repositorio
2. Localiza el archivo `index.html`
3. Haz doble clic en el archivo
4. Se abrirá en tu navegador predeterminado
5. ¡Listo! El menú aparecerá automáticamente

### Opción 2: Usar un servidor local (recomendado)

Si tienes VS Code:
1. Instala la extensión "Live Server"
2. Haz clic derecho en `index.html`
3. Selecciona "Open with Live Server"

## 💡 Características Destacadas

### 🎨 Diseño Visual
- Interfaz estilo terminal con tema oscuro
- Colores verde neón sobre fondo negro
- ASCII art personalizado
- Bordes decorativos con caracteres especiales

### 🧩 Arquitectura del Código
- **Modularidad:** Cada práctica es una función independiente
- **Reutilización:** Funciones auxiliares para mostrar mensajes y limpiar pantalla
- **Mantenibilidad:** Código comentado y organizado por secciones
- **Escalabilidad:** Fácil agregar nuevas prácticas al menú

### ✨ Experiencia de Usuario
- Navegación intuitiva con menú principal
- Botón "Volver al Menú" después de cada práctica
- Mensajes claros y descriptivos
- Validación de opciones inválidas

---

## 🔍 Detalles Técnicos Implementados

### Funciones Principales

```javascript
menuPrincipal()        // Gestiona el menú de navegación
ejecutarPractica1()    // Ejecuta la práctica de calificación salarial
ejecutarPractica2()    // Ejecuta la práctica de login
mostrarMensaje()       // Función auxiliar para mostrar texto en pantalla
limpiarPantalla()      // Función auxiliar para limpiar el contenido
