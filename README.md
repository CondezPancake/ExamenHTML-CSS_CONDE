# 🛍️ Ecommerce Clothing — HTML & CSS

Interfaz móvil estática de una tienda de ropa desarrollada con HTML5 y CSS3 puro. El proyecto replica el flujo completo de compra de una aplicación móvil: exploración de productos, detalle del artículo y proceso de pago.

---

## 👥 Integrantes

| Nombre | Rol |
|---|---|
| Juan Pablo Conde Zapata | Desarrollador Frontend |
| Daniel Eduardo Jaimes Gamboa | Desarrollador Frontend |

---

## 📱 Vistas del Proyecto

El proyecto cuenta con tres pantallas principales interconectadas:

### 1. `index.html` — Página Principal (Home)
- Barra de estado estilo iOS (hora, señal, wifi, batería)
- Barra de búsqueda con filtro por categorías (All Items, Dress, T-Shirt, Pants)
- Grilla de productos con imagen, nombre, categoría, precio y calificación
- Botón de favoritos por producto
- Navegación inferior con iconos (Home, Bolso, Favoritos, Cuenta)

### 2. `views/detail.html` — Detalle del Producto
- Imagen principal del producto con botón de favorito
- Nombre, calificación y número de reseñas
- Descripción del artículo
- Selector de talla (S, M, L, XL) mediante radio buttons
- Selector de color con botones visuales
- Control de cantidad (+/−)
- Botón de acción *"Add to Cart"* con precio actual y precio anterior tachado

### 3. `views/checkout.html` — Carrito y Pago
- Header con botón de retroceso y menú hamburguesa desplegable
- Lista de productos agregados con imagen, nombre, precio y cantidad
- Panel de información de envío con tarjeta VISA
- Resumen de compra: subtotal, envío, descuento y total final
- Botón de pago *"Pay"*

---

## 🗂️ Estructura del Proyecto

```
Gamboa-Conde-HTML-CSS/
│
├── index.html                  # Pantalla principal
│
├── views/
│   ├── detail.html             # Detalle del producto
│   └── checkout.html           # Carrito y pago
│
├── css/
│   ├── variables.css           # Variables globales (colores, fuentes, espaciado)
│   ├── style.css               # Estilos del Home
│   ├── detail.css              # Estilos del Detalle
│   └── checkout.css            # Estilos del Checkout
│
└── storage/
    ├── img/                    # Íconos y productos
    └── font/
        └── encode_sans/        # Fuente Encode Sans (Regular y Bold)
```

---

## 🎨 Tecnologías Utilizadas

- **HTML5** — Estructura semántica de las vistas
- **CSS3** — Estilos, layout y diseño visual
  - Variables CSS (`--color`, `--space`, `--text`, `--radius`)
  - Tipografía personalizada con `@font-face` (Encode Sans)
  - Diseño responsivo tipo móvil
- **Git** — Control de versiones

---

## 🖌️ Sistema de Diseño

El proyecto utiliza un sistema de diseño consistente definido en `css/variables.css`:

**Paleta de colores**
- `#292526` — Texto principal (casi negro)
- `#787676` — Texto secundario
- `#A3A1A2` — Texto terciario / disabled
- `#F2F2F2` — Fondos claros
- `#121111` — Color de contraste

**Tipografía**
- Familia: `Encode Sans` (local) + `Inter` (Google Fonts en checkout)
- Tamaños: `12px` a `36px` mediante variables semánticas

**Espaciado**
- Sistema de 8 niveles: de `4px` a `32px`

**Bordes redondeados**
- Desde `10px` hasta `pill (999px)`

---

## 🚀 Cómo Ejecutar el Proyecto

1. Clona o descarga el repositorio
2. Abre el archivo `index.html` directamente en tu navegador
3. Navega entre las vistas usando los enlaces del proyecto

> No requiere instalación de dependencias ni servidor backend.

---

## 📋 Historial de Versiones

| Commit | Descripción |
|---|---|
| `0161a0e` | Index, Detail y Checkout finalizados |
| `6dbb5b4` | Index y Detail funcionando |
| `29f641a` | Index terminado |
| `e032bd8` | Corrección del dashboard |
| `1a1f1aa` | Estructura inicial del proyecto |
