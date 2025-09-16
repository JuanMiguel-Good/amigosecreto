# 🎁 Amigo Secreto

Una aplicación web interactiva para sortear nombres de amigos de forma aleatoria, perfecta para intercambios de regalos o juegos de amigo secreto.

![Amigo Secreto App](https://images.pexels.com/photos/1303081/pexels-photo-1303081.jpeg?auto=compress&cs=tinysrgb&w=800)

## 🌟 Características

- ✅ **Agregar amigos**: Interfaz intuitiva para añadir nombres
- 🎲 **Sorteo aleatorio**: Selección aleatoria con animación
- 🗑️ **Gestión de lista**: Eliminar amigos individualmente
- 📱 **Responsive**: Optimizado para móviles y escritorio
- 🎨 **Animaciones**: Transiciones suaves y efectos visuales
- ⌨️ **Accesibilidad**: Soporte completo de teclado

## 🚀 Demo en Vivo

[Ver Demo](https://tu-usuario.github.io/amigo-secreto)

## 🛠️ Tecnologías Utilizadas

- **React 18** - Framework principal
- **TypeScript** - Tipado estático
- **Tailwind CSS** - Estilos utilitarios
- **Lucide React** - Iconos
- **Vite** - Build tool y desarrollo

## 📦 Instalación

1. **Clonar el repositorio**
```bash
git clone https://github.com/tu-usuario/amigo-secreto.git
cd amigo-secreto
```

2. **Instalar dependencias**
```bash
npm install
```

3. **Ejecutar en desarrollo**
```bash
npm run dev
```

4. **Construir para producción**
```bash
npm run build
```

## 🎮 Uso

1. **Agregar amigos**: Escribe un nombre y presiona "Añadir" o Enter
2. **Ver la lista**: Los nombres aparecen en la lista con opción de eliminar
3. **Realizar sorteo**: Necesitas mínimo 2 amigos, luego presiona "Sortear Amigo"
4. **Ver resultado**: El amigo secreto se mostrará con una animación especial

## 🎯 Funcionalidades

### Validaciones
- ❌ No permite nombres vacíos
- ❌ No permite nombres duplicados  
- ❌ Mínimo 2 amigos para sortear
- ✅ Mensajes de error claros

### Experiencia de Usuario
- 🎨 Animaciones fluidas
- 📊 Contador de amigos
- 🎊 Efectos de celebración
- 📱 Diseño adaptable
- ⚡ Respuesta instantánea

## 📁 Estructura del Proyecto

```
amigo-secreto/
├── src/
│   ├── App.tsx              # Componente principal
│   ├── AmigoSecreto.css     # Estilos específicos
│   ├── main.tsx             # Punto de entrada
│   └── index.css            # Estilos globales
├── public/                  # Archivos estáticos
├── package.json             # Dependencias
└── README.md               # Documentación
```

## 🎨 Personalización

### Colores Principales
```css
:root {
    --color-primary: #4B69FD;    /* Azul principal */
    --color-secondary: #FFF9EB;  /* Crema */
    --color-button: #fe652b;     /* Naranja */
    --color-white: #FFFFFF;      /* Blanco */
}
```

### Fuentes
- **Merriweather**: Títulos principales
- **Inter**: Texto del cuerpo y botones

## 🤝 Contribución

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📝 Roadmap

- [ ] Historial de sorteos
- [ ] Exportar resultados
- [ ] Temas personalizables
- [ ] Múltiples listas
- [ ] Compartir en redes sociales

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 👨‍💻 Autor

**Tu Nombre**
- GitHub: [@tu-usuario](https://github.com/tu-usuario)
- Email: tu-email@ejemplo.com

## 🙏 Agradecimientos

- Diseño inspirado en el desafío de Oracle ONE
- Iconos de [Lucide](https://lucide.dev)
- Fuentes de [Google Fonts](https://fonts.google.com)

---

⭐ Si te gusta este proyecto, ¡dale una estrella en GitHub!