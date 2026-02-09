<div align="center">

# 🐾 PetsLove-Website

### Aplicación web para el cuidado y gestión de tus mascotas

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/es/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/es/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/es/docs/Web/JavaScript)
[![Mobile First](https://img.shields.io/badge/Mobile%20First-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

```
    🐶                    🐱
   /\_/\                /\_/\
  ( o.o )              ( ^.^ )
   > ^ <    PetsLove    > ♡ <
  /|   |\              /|   |\
 (_|   |_)            (_|   |_)
    
  ¡Tu compañero de cuidado animal! 🏥💉🍖
```

</div>

---

## 📑 Tabla de Contenidos

- [📖 Descripción](#-descripción)
- [✨ Características Principales](#-características-principales)
- [🗂️ Estructura del Proyecto](#️-estructura-del-proyecto)
- [🚀 Instalación y Uso](#-instalación-y-uso)
- [🎮 Guía de Uso](#-guía-de-uso)
- [🛠️ Tecnologías](#️-tecnologías)
- [🎨 Características de Diseño](#-características-de-diseño)
- [📱 Compatibilidad](#-compatibilidad)
- [📸 Screenshots](#-screenshots)
- [🔮 Roadmap](#-roadmap)
- [🤝 Contribuir](#-contribuir)
- [📄 Licencia](#-licencia)
- [👨‍💻 Autor](#-autor)

---

## 📖 Descripción

**PetsLove** es una aplicación web moderna y elegante diseñada con un enfoque **mobile-first** para ayudarte a gestionar de manera integral el cuidado de tus mascotas. Con una interfaz intuitiva y responsive, podrás mantener un registro completo de la salud, alimentación y cuidados de tus compañeros peludos.

### ¿Por qué PetsLove?

🎯 **Todo en un solo lugar**: Centraliza toda la información de tus mascotas  
💡 **Fácil de usar**: Interfaz intuitiva y moderna  
📱 **Siempre contigo**: Accede desde cualquier dispositivo  
💾 **Sin complicaciones**: Almacenamiento local sin necesidad de registro  

---

## ✨ Características Principales

<table>
<tr>
<td width="50%">

### 📅 Calendario de Vacunas
Control completo de vacunaciones, fechas de refuerzo y próximas citas veterinarias. Nunca olvides una vacuna importante.

### 🍖 Planes de Alimentación
Gestiona las dietas personalizadas de tus mascotas, horarios de comida y transiciones alimenticias para mantenerlos saludables.

</td>
<td width="50%">

### 🏥 Historial Médico
Mantén un registro detallado de la salud de tus mascotas: consultas, tratamientos, síntomas y medicamentos.

### 👨‍👩‍👧 Árbol Genealógico
Documenta la información de pedigree y linaje de tus mascotas para un registro completo.

</td>
</tr>
</table>

### Funcionalidades Adicionales

- 📱 **Diseño Responsive**: Perfecto en móviles, tablets y escritorio
- 🔔 **Sistema de Recordatorios**: Alertas para citas importantes y cuidados pendientes
- 🐕 **Multi-mascota**: Gestiona todas tus mascotas desde un solo lugar
- 💾 **Almacenamiento Local**: Tus datos seguros en tu navegador, sin necesidad de servidor
- 🎨 **Interfaz Moderna**: Diseño limpio inspirado en las mejores apps móviles
- ⚡ **Rápida y Ligera**: Sin dependencias externas, carga instantánea

---

## 🗂️ Estructura del Proyecto

```
PetsLove-Website/
├── 📄 petslove.html       # Aplicación principal (standalone)
│   ├── 🎨 CSS embebido   # Estilos modernos y responsive
│   ├── 💻 JavaScript     # Lógica de interacción
│   └── 📱 HTML5          # Estructura semántica
├── 📝 README.md           # Este archivo
└── 📋 .git/               # Control de versiones
```

> **Nota**: Esta es una aplicación standalone con todo el código en un único archivo HTML para facilitar su uso y distribución.

---

## 🚀 Instalación y Uso

### Opción 1: Uso Directo (Recomendado)

```bash
# 1. Clonar el repositorio
git clone https://github.com/albertogarciaquintana5-jpg/PetsLove-Website.git

# 2. Navegar al directorio
cd PetsLove-Website

# 3. Abrir en navegador
# Opción A: Doble clic en petslove.html
# Opción B: Arrastrar el archivo al navegador
# Opción C: Con VS Code Live Server (recomendado para desarrollo)
```

### Opción 2: Servidor Local

#### Con Python 3

```bash
# Iniciar servidor HTTP simple
python -m http.server 8000

# Acceder a: http://localhost:8000/petslove.html
```

#### Con Node.js (http-server)

```bash
# Instalar http-server (solo una vez)
npm install -g http-server

# Iniciar servidor
npx http-server

# Acceder a: http://localhost:8080/petslove.html
```

#### Con PHP

```bash
# Iniciar servidor PHP integrado
php -S localhost:8000

# Acceder a: http://localhost:8000/petslove.html
```

---

## 🎮 Guía de Uso

### Inicio Rápido

1. **Abre la aplicación** en tu navegador favorito
2. **Explora la interfaz**: Verás mascotas de ejemplo (Max y Luna)
3. **Navega por las secciones** usando las tarjetas de funciones
4. **Gestiona tus mascotas** con el selector inferior

### Funcionalidades Detalladas

#### 🐾 Gestión de Mascotas

- **Ver mascotas**: Desliza horizontalmente en el carrusel de mascotas
- **Seleccionar mascota**: Haz clic en una tarjeta de mascota para activarla
- **Añadir mascota**: Usa el botón **"+ Add Pet"** en la sección "My Pets"
- **Estado de salud**: Cada mascota muestra su estado actual con badges de colores

#### 📅 Funciones Principales

<table>
<tr>
<td align="center" width="25%">
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Calendar.png" alt="Calendar" width="50" height="50" />
<br><strong>Calendario</strong><br>
Vacunas y citas
</td>
<td align="center" width="25%">
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Food/Green%20Apple.png" alt="Diet" width="50" height="50" />
<br><strong>Alimentación</strong><br>
Planes de dieta
</td>
<td align="center" width="25%">
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Hospital.png" alt="Health" width="50" height="50" />
<br><strong>Historial</strong><br>
Registros médicos
</td>
<td align="center" width="25%">
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Deciduous%20Tree.png" alt="Family" width="50" height="50" />
<br><strong>Genealogía</strong><br>
Árbol familiar
</td>
</tr>
</table>

#### 🔔 Recordatorios

La sección **"Upcoming Reminders"** muestra:
- 💉 Próximas vacunas y refuerzos
- 🍖 Cambios en la alimentación
- 🛁 Citas de grooming y cuidado
- 🏥 Chequeos médicos programados

#### 🧭 Navegación

Barra inferior con 4 secciones:
- **🏠 Home**: Pantalla principal (activa por defecto)
- **📅 Calendar**: Vista de calendario completo
- **👨‍👩‍👧‍👦 Pets**: Gestión detallada de mascotas
- **⚙️ Settings**: Configuración de la aplicación

---

## 🛠️ Tecnologías

<div align="center">

| Tecnología | Versión | Uso |
|:----------:|:-------:|:---:|
| ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) | HTML5 | Estructura semántica de la aplicación |
| ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) | CSS3 | Estilos, animaciones y diseño responsive |
| ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | ES6+ | Lógica de negocio e interactividad |
| ![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white) | 2.x | Control de versiones |

</div>

### Detalles Técnicos

- **CSS Grid & Flexbox**: Layout moderno y flexible
- **CSS Variables**: Temas y colores personalizables
- **Local Storage API**: Persistencia de datos en el navegador
- **Responsive Design**: Media queries para todos los dispositivos
- **Vanilla JavaScript**: Sin dependencias, código puro y eficiente
- **SF Pro Display Font**: Tipografía moderna estilo iOS

---

## 🎨 Características de Diseño

<div align="center">

### Principios de Diseño

</div>

| Característica | Descripción |
|:---------------|:------------|
| ✅ **Mobile First** | Diseñado primero para dispositivos móviles, luego escalado a desktop |
| ✅ **Responsive** | Adaptación perfecta a cualquier tamaño de pantalla |
| ✅ **Interfaz Moderna** | Inspirada en las mejores apps móviles del mercado |
| ✅ **Colores Suaves** | Paleta de colores cálidos y agradables a la vista |
| ✅ **Iconos Intuitivos** | Emojis y símbolos universalmente reconocidos |
| ✅ **Animaciones Suaves** | Transiciones fluidas para mejor UX |
| ✅ **Sombras y Profundidad** | Diseño con sensación de profundidad (elevation) |
| ✅ **Espacios Generosos** | Padding y margins cómodos para touch |

### Paleta de Colores

```css
🎨 Gradiente Principal: #ff6b6b → #ffa726
⚪ Background: #ffffff
🔵 Texto Principal: #333333
⚫ Texto Secundario: #666666
🔴 Acento: #ff6b6b
🟠 Secundario: #ffa726
```

---

## 📱 Compatibilidad

<div align="center">

### Navegadores Soportados

| Navegador | Versión Mínima | Estado |
|:---------:|:--------------:|:------:|
| ![Chrome](https://img.shields.io/badge/Chrome-90+-4285F4?style=flat-square&logo=googlechrome&logoColor=white) | 90+ | ✅ Totalmente compatible |
| ![Firefox](https://img.shields.io/badge/Firefox-88+-FF7139?style=flat-square&logo=firefox&logoColor=white) | 88+ | ✅ Totalmente compatible |
| ![Safari](https://img.shields.io/badge/Safari-14+-000000?style=flat-square&logo=safari&logoColor=white) | 14+ | ✅ Totalmente compatible |
| ![Edge](https://img.shields.io/badge/Edge-90+-0078D7?style=flat-square&logo=microsoftedge&logoColor=white) | 90+ | ✅ Totalmente compatible |
| ![Opera](https://img.shields.io/badge/Opera-76+-FF1B2D?style=flat-square&logo=opera&logoColor=white) | 76+ | ✅ Totalmente compatible |

### Dispositivos

- ✅ **Smartphones** (iOS 14+, Android 9+)
- ✅ **Tablets** (iPad, Android tablets)
- ✅ **Laptops** (1024px+)
- ✅ **Desktops** (1440px+)
- ✅ **TV Browsers** (Navegadores de Smart TV)

</div>

---

## 📸 Screenshots

> 🚧 **Próximamente se añadirán capturas de pantalla**

### Vistas Planificadas

<table>
<tr>
<td align="center" width="25%">
<strong>🏠 Pantalla Principal</strong><br>
Vista general con todas las funciones
</td>
<td align="center" width="25%">
<strong>🐾 Selector de Mascotas</strong><br>
Carrusel interactivo de mascotas
</td>
<td align="center" width="25%">
<strong>📅 Calendario de Vacunas</strong><br>
Gestión de vacunaciones
</td>
<td align="center" width="25%">
<strong>🍖 Plan de Alimentación</strong><br>
Horarios y dietas personalizadas
</td>
</tr>
</table>

### Contribuye con Screenshots

Si usas PetsLove, ¡comparte tus capturas! Abre un issue con la etiqueta `screenshots` y adjunta tus imágenes.

---

## 🔮 Roadmap

### Versión 2.0 (Q2 2026)

- [ ] 🔐 **Sistema de autenticación** de usuarios
- [ ] ☁️ **Backend integrado** con base de datos
- [ ] 📊 **Dashboard de estadísticas** de salud
- [ ] 🔔 **Notificaciones push** para recordatorios

### Versión 2.5 (Q3 2026)

- [ ] 📄 **Exportar datos en PDF** (informes médicos)
- [ ] 🌙 **Modo oscuro** para mejor visualización nocturna
- [ ] 🌍 **Multi-idioma** (Español, Inglés, Francés, Alemán)
- [ ] 📷 **Galería de fotos** de mascotas

### Versión 3.0 (Q4 2026)

- [ ] 🤖 **IA para recomendaciones** de cuidado
- [ ] 🗺️ **Mapa de veterinarias** cercanas
- [ ] 👥 **Comunidad de usuarios** y foros
- [ ] 🔗 **API pública** para integraciones
- [ ] ⌚ **App nativa** para iOS y Android

### Mejoras Continuas

- [ ] Optimización de rendimiento
- [ ] Accesibilidad (WCAG 2.1)
- [ ] Tests automatizados
- [ ] Documentación extendida

---

## 🤝 Contribuir

¡Las contribuciones son **bienvenidas** y muy apreciadas! 🎉

### ¿Cómo contribuir?

1. **Fork** el proyecto
2. **Crea** una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. **Commit** tus cambios (`git commit -m 'Add: AmazingFeature'`)
4. **Push** a la rama (`git push origin feature/AmazingFeature`)
5. **Abre** un Pull Request

### Convenciones de Commits

Usa prefijos descriptivos en tus commits:

- `Add:` para nuevas características
- `Fix:` para corrección de bugs
- `Update:` para actualizaciones
- `Remove:` para eliminaciones
- `Docs:` para documentación
- `Style:` para cambios de formato

### Áreas de Contribución

- 🐛 **Reportar bugs**: Abre un issue con detalles del problema
- ✨ **Sugerir features**: Comparte tus ideas en las discusiones
- 📝 **Mejorar docs**: Ayuda a hacer la documentación más clara
- 🎨 **Diseño UI/UX**: Propón mejoras visuales
- 💻 **Código**: Implementa nuevas funcionalidades

### Código de Conducta

Por favor, sé respetuoso y profesional. Este es un proyecto para amantes de las mascotas 🐾

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - consulta el archivo [LICENSE](LICENSE) para más detalles.

```
MIT License

Copyright (c) 2026 Alberto García Quintana

Se concede permiso gratuito a cualquier persona que obtenga una copia
de este software y archivos de documentación asociados para usar, copiar,
modificar, fusionar, publicar, distribuir, sublicenciar y/o vender
copias del Software, sujeto a las siguientes condiciones:

El aviso de copyright anterior y este aviso de permiso se incluirán en
todas las copias o partes sustanciales del Software.
```

---

## 👨‍💻 Autor

<div align="center">

### Alberto García Quintana

**Full Stack Developer & Pet Lover** 🐕

[![Email](https://img.shields.io/badge/Email-albertogarciaquintana5@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:albertogarciaquintana5@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-albertogarciaquintana5--jpg-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/albertogarciaquintana5-jpg)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Alberto%20García%20Quintana-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/albertogarciaquintana)

</div>

---

<div align="center">

### ⭐ Si te gusta este proyecto, ¡dale una estrella!

**Hecho con 💙 y mucho ☕ para amantes de las mascotas 🐾**

---

### 🐕 🐈 🐇 🦜 🐹

*"Los animales son amigos tan agradables: no hacen preguntas ni critican."*  
— George Eliot

---

[![Volver arriba](https://img.shields.io/badge/⬆️_Volver_arriba-blue?style=for-the-badge)](#-petslove-website)

</div>
