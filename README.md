# 🌳 Demo AR - Información de Árboles

Un demo interactivo de Realidad Aumentada para visualizar información de árboles usando AR.js y A-Frame. Proyecto desarrollado como prueba de concepto para mostrar datos de árboles a través de códigos QR.

## 🚀 Demo en Vivo

**[👉 Probar Demo Aquí](https://tu-usuario.github.io/demo-ar-arboles/)**

> **📱 Nota:** Accede desde tu móvil para la mejor experiencia AR

## 🎯 ¿Qué hace este demo?

- **Escanea** códigos QR/marcadores con la cámara
- **Muestra información** del árbol en Realidad Aumentada
- **Visualiza** modelos 3D interactivos del árbol
- **Presenta datos** como especie, edad, altura y estado de salud

## 📋 Características

- ✅ **Sin instalación** - Funciona directo en el navegador
- ✅ **Multiplataforma** - Compatible con iOS y Android
- ✅ **Responsive** - Se adapta a diferentes pantallas
- ✅ **Offline-ready** - Funciona sin internet una vez cargado
- ✅ **Open Source** - Código libre y modificable

## 🛠️ Tecnologías Utilizadas

- **[AR.js](https://ar-js-org.github.io/AR.js-Docs/)** - Biblioteca de Realidad Aumentada
- **[A-Frame](https://aframe.io/)** - Framework web para experiencias VR/AR
- **HTML5/CSS3/JavaScript** - Tecnologías web estándar
- **WebRTC** - Acceso a cámara del dispositivo

## 📱 Instrucciones de Uso

### 1. Obtener el Marcador
- Abre el demo en tu dispositivo
- Haz clic en **"📱 Descargar QR/Marcador"**
- Imprime la imagen descargada

### 2. Activar AR
- Permite acceso a la cámara cuando se solicite
- Apunta la cámara al marcador impreso
- Mantén distancia de 20-50 cm para mejor detección

### 3. Interactuar
- El árbol 3D aparecerá sobre el marcador
- Mueve el dispositivo para ver desde diferentes ángulos
- La información se muestra en tiempo real

## 🔧 Desarrollo Local

### Prerrequisitos
- Servidor web local (PHP, Node.js, Python, etc.)
- **IMPORTANTE:** Requiere HTTPS para acceso a cámara

### Configuración
```bash
# Clonar repositorio
git clone https://github.com/tu-usuario/demo-ar-arboles.git
cd demo-ar-arboles

# Servidor con PHP
php -S localhost:8000

# O con Node.js
npx http-server -p 8000 --ssl

# O con Python
python -m http.server 8000
```

### Acceso
- Local: `https://localhost:8000`
- Red local: `https://tu-ip:8000`

## 📂 Estructura del Proyecto

```
demo-ar-arboles/
├── index.html          # Archivo principal del demo
├── README.md           # Este archivo
└── marcadores/         # Carpeta para marcadores personalizados (opcional)
```

## 🎨 Personalización

### Modificar Información del Árbol
Edita las variables en el JavaScript:
```javascript
// Cambiar datos del árbol
const treeData = {
    name: "Ceiba Pentandra",
    age: "200 años",
    height: "40 metros",
    status: "Protegido"
};
```

### Añadir Nuevos Marcadores
1. Crea nuevos patrones con [AR.js Marker Training](https://ar-js-org.github.io/AR.js-Docs/marker-based/)
2. Añade nuevos elementos `<a-marker>` en el HTML
3. Personaliza el contenido 3D para cada marcador

### Cambiar Modelos 3D
- Reemplaza los elementos `<a-cylinder>` y `<a-sphere>` 
- Usa modelos .glb/.gltf para mayor realismo
- Ajusta posiciones y escalas según necesites

## 🐛 Solución de Problemas

### La cámara no funciona
- ✅ Verifica que estás usando **HTTPS**
- ✅ Permite acceso a la cámara en el navegador
- ✅ Prueba en modo incógnito
- ✅ Revisa que la cámara funcione en otras apps

### El marcador no se detecta
- ✅ Asegura **buena iluminación**
- ✅ Mantén el marcador **plano** y **estable**
- ✅ **Distancia óptima:** 20-50 centímetros
- ✅ Evita **reflejos** en el papel

### Performance lento
- ✅ Cierra otras **pestañas del navegador**
- ✅ Usa un dispositivo con **cámara de buena calidad**
- ✅ Asegura **conexión estable** a internet

## 🔄 Roadmap / Próximas Funciones

- [ ] **Base de datos** de múltiples árboles
- [ ] **Geolocalización** para árboles cercanos
- [ ] **Audio** con sonidos de la naturaleza
- [ ] **Compartir** información en redes sociales
- [ ] **Modo offline** completo
- [ ] **Realidad Aumentada sin marcadores**
- [ ] **Integración** con APIs de biodiversidad

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Si quieres mejorar este demo:

1. **Fork** el repositorio
2. **Crea** una rama para tu función (`git checkout -b nueva-funcion`)
3. **Commit** tus cambios (`git commit -am 'Añadir nueva función'`)
4. **Push** a la rama (`git push origin nueva-funcion`)
5. **Abre** un Pull Request

## 📝 Casos de Uso

Este demo puede adaptarse para:

- 🌲 **Jardines botánicos** - Tours autoguiados
- 🏫 **Educación** - Clases de biología interactivas
- 🏛️ **Museos** - Exhibiciones de naturaleza
- 🌍 **Conservación** - Concientización ambiental
- 🚶‍♂️ **Turismo** - Rutas ecológicas
- 🏢 **Empresas** - Espacios verdes corporativos

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para detalles.

## 👨‍💻 Autor

**[Tu Nombre]** - Desarrollador Web
- 🌐 Portfolio: [tu-portfolio.com](https://tu-portfolio.com)
- 💼 LinkedIn: [linkedin.com/in/tu-perfil](https://linkedin.com/in/tu-perfil)
- 📧 Email: tu-email@ejemplo.com

## 🙏 Agradecimientos

- **AR.js** por la increíble biblioteca de AR web
- **A-Frame** por el framework VR/AR accesible
- **GitHub Pages** por el hosting gratuito
- **Comunidad Open Source** por las herramientas increíbles

---

⭐ **¡Si te gustó este proyecto, danos una estrella!** ⭐

**¿Tienes ideas o encontraste un bug?** 
[Abre un issue](https://github.com/tu-usuario/demo-ar-arboles/issues) o [contribuye](https://github.com/tu-usuario/demo-ar-arboles/pulls) al proyecto.

---

*Desarrollado con 💚 para la naturaleza y la tecnología*
