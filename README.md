# 🎵 Animación de Logos - EDM Linares

Una animación visual de logos sincronizada a 128 BPM para presentaciones de música electrónica.

## 📋 Descripción

Este proyecto crea una animación visual que cambia entre diferentes logos de EDM Linares al ritmo de 128 BPM, acompañada de textos promocionales que alternan entre enlaces de Telegram y Linktree con colores distintivos.

## ✨ Características

- **Sincronización musical**: Animación sincronizada a 128 BPM
- **Cambio de logos**: Rotación automática entre 4 logos diferentes
- **Textos promocionales**:
  - Telegram (color azul #0088cc)
  - Linktree (color rosa #ff69b4)
- **Transiciones suaves**: Efectos de transición de 2 segundos
- **Diseño responsivo**: Se adapta a diferentes tamaños de pantalla
- **Centrado automático**: Elementos perfectamente centrados

## 🎨 Elementos Visuales

### Logos

- `logo1.png` - Logo principal
- `logo2.png` - Logo secundario
- `logo3.png` - Logo terciario
- `logo4.png` - Logo cuaternario

### Textos Promocionales

1. "Sígueme en Telegram" (azul)
2. "t.me/edmlinares" (azul)
3. "https://linktr.ee/carlosnewmusic" (rosa)

## 🚀 Uso

1. Abre el archivo `index.html` en tu navegador web
2. La animación comenzará automáticamente
3. Los logos cambiarán cada beat (aproximadamente cada 0.47 segundos)
4. Los textos promocionales cambiarán en secuencia con transiciones suaves

## 📁 Estructura del Proyecto

```
animacion logo/
├── index.html          # Archivo principal
├── README.md           # Documentación
└── img/               # Carpeta de imágenes
    ├── logo1.png
    ├── logo2.png
    ├── logo3.png
    └── logo4.png
```

## 🎛️ Personalización

### Cambiar BPM

Modifica la variable `bpm` en el archivo `index.html`:

```javascript
const bpm = 128; // Cambia este valor
```

### Agregar/Modificar Textos Promocionales

Edita el array `promoTexts`:

```javascript
const promoTexts = [
  { text: "Tu texto aquí", type: "telegram" },
  { text: "Otro texto", type: "linktree" },
];
```

### Cambiar Colores

Modifica los valores de color en la función `promotext()`:

```javascript
// Para Telegram
promoText.style.color = "#0088cc";

// Para Linktree
promoText.style.color = "#ff69b4";
```

## 🎯 Tecnologías Utilizadas

- HTML5
- CSS3 (Flexbox, Transiciones, Gradientes)
- JavaScript (Vanilla)

## 📱 Compatibilidad

- ✅ Chrome
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Dispositivos móviles

## 🎵 Uso Recomendado

Esta animación es ideal para:

- Presentaciones en vivo de DJ
- Videos de música electrónica
- Streams en redes sociales
- Eventos de EDM

## 📞 Contacto

- **Telegram**: t.me/edmlinares
- **Linktree**: https://linktr.ee/carlosnewmusic

---

_Desarrollado para EDM Linares - Música Electrónica_ 🎧
