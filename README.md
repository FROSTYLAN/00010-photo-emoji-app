# 📸 Photo Emoji App

Una aplicación móvil React Native que permite seleccionar fotos de la galería y agregar stickers de emojis interactivos. Los usuarios pueden personalizar sus imágenes con emojis animados que responden a gestos táctiles con efectos de escala y animaciones fluidas.

## 🌟 Características

- **Selector de imágenes** desde la galería del dispositivo
- **Stickers de emojis interactivos** con animaciones
- **Gestos táctiles** para escalar y manipular emojis
- **Interfaz moderna** con diseño dark theme
- **Animaciones fluidas** con React Native Reanimated
- **Modal picker** para selección de emojis
- **Compatibilidad multiplataforma** (iOS y Android)
- **Navegación intuitiva** entre pantallas

## 🛠️ Tecnologías Utilizadas

- **React Native** - Framework móvil multiplataforma
- **Expo** - Plataforma de desarrollo y deployment
- **React Navigation** - Navegación entre pantallas
- **Expo Image Picker** - Selección de imágenes
- **React Native Gesture Handler** - Manejo de gestos
- **React Native Reanimated** - Animaciones de alto rendimiento
- **Expo Vector Icons** - Iconografía

## 📁 Estructura del Proyecto

```
00010-photo-emoji-app/
├── components/
│   ├── Button.js              # Botón principal
│   ├── CircleButton.js        # Botón circular
│   ├── EmojiList.js          # Lista de emojis disponibles
│   ├── EmojiPicker.js        # Modal selector de emojis
│   ├── EmojiSticker.js       # Componente de sticker animado
│   ├── IconButton.js         # Botón con icono
│   └── ImageViewer.js        # Visor de imágenes
├── pages/
│   ├── FriendsScreen.js      # Pantalla de amigos
│   └── HomeScreen.js         # Pantalla principal
├── assets/
│   ├── images/               # Emojis e imágenes
│   └── *.png                 # Iconos de la app
├── App.js                    # Componente principal
├── app.json                  # Configuración de Expo
└── package.json              # Dependencias del proyecto
```

## 🎨 Características de Diseño

### Pantalla Principal
- Visor de imágenes centrado con bordes redondeados
- Botones de acción con efectos hover
- Selector de imágenes desde galería
- Interfaz dark theme moderna

### Editor de Stickers
- Modal deslizante para selección de emojis
- Stickers interactivos con gestos de doble tap
- Animaciones de escala suaves
- Posicionamiento libre de stickers

### Navegación
- Pantalla de inicio (Home)
- Pantalla de amigos (Friends)
- Transiciones fluidas entre pantallas

## 🚀 Instalación y Uso

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/FROSTYLAN/photo-emoji-app.git
   ```

2. **Navega al directorio:**
   ```bash
   cd photo-emoji-app
   ```

3. **Instala las dependencias:**
   ```bash
   npm install
   ```

4. **Inicia el proyecto:**
   ```bash
   npm start
   ```

5. **Ejecuta en dispositivo:**
   - **iOS:** `npm run ios`
   - **Android:** `npm run android`
   - **Web:** `npm run web`

## 📱 Compatibilidad

La aplicación está optimizada para:
- 📱 **iOS** - iPhone y iPad
- 🤖 **Android** - Smartphones y tablets
- 🌐 **Web** - Navegadores modernos
- 📟 **Expo Go** - Testing en dispositivos reales

## 🎯 Funcionalidades Principales

### Selección de Imágenes
- Acceso a galería del dispositivo
- Preview de imagen seleccionada
- Soporte para edición y recorte

### Editor de Stickers
- 6 emojis predefinidos disponibles
- Gestos de doble tap para escalar
- Posicionamiento libre en la imagen
- Animaciones suaves con spring physics

### Gestión de Estado
- Estado local con React Hooks
- Manejo de modales y navegación
- Persistencia de cambios en sesión

## 🔧 Posibles Mejoras

- [ ] Guardar imágenes editadas en galería
- [ ] Más opciones de stickers y emojis
- [ ] Filtros y efectos para imágenes
- [ ] Compartir en redes sociales
- [ ] Historial de ediciones
- [ ] Stickers personalizados
- [ ] Modo colaborativo en tiempo real
- [ ] Exportar en diferentes formatos

## 🧪 Testing

Para probar la aplicación:

1. **Expo Go (Recomendado):**
   - Instala Expo Go en tu dispositivo
   - Escanea el QR code generado

2. **Simulador iOS:**
   ```bash
   npm run ios
   ```

3. **Emulador Android:**
   ```bash
   npm run android
   ```

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 👨‍💻 Autor

**Charles Castillo (FROSTYLAN)**
- GitHub: [@FROSTYLAN](https://github.com/FROSTYLAN)
- LinkedIn: [Charles Castillo](https://linkedin.com/in/charles-castillo-772968234)

---

⭐ ¡No olvides dar una estrella al proyecto si te gustó!

🎨 **Desarrollado con ❤️ usando React Native y Expo**