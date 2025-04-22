# GuitarLA V2

Es Una (SPA) **Single Page Application** simple de e‑commerce para una colección de guitarras, construida con **Vite** y **React**, que permite navegar por los productos, añadirlos al carrito, modificar cantidades y vaciar el carrito. Desplegada en Netlify.

---

## Demo en Vivo

[Ver la aplicación en Netlify](https://jovial-starship-d36c41.netlify.app/)

---

## Características

- **Listado de Guitarras**  
  Muestra una galería responsiva de 12 guitarras con nombre, descripción, imagen y precio (datos cargados desde un arreglo estático)
- **Carrito de Compras**
  - Añade productos al carrito con cantidad inicial.
  - Incrementa/decrementa cantidad (entre 1 y 5 unidades).
  - Elimina productos individualmente o vacía todo el carrito.
  - Persistencia en `localStorage` para mantener el carrito entre recargas.
- **Encabezado y Pie de Página**
  - Cabecera con logo y carrusel del carrito interactivo.
  - Footer sencillo con derechos reservados.

---

## Tecnologías

- **Vite** ^6.2.0 (bundler y servidor de desarrollo)
- **React** ^19.0.0 y **ReactDOM** ^19.0.0 (biblioteca de UI)
- **ESLint** con plugins para React y Hooks (calidad de código)
- **JavaScript** con módulos ES
- **CSS** clases utilizadas de Tailwind
- **Netlify** (hosting del frontend)

---

## Instalación y Uso

1. **Clonar el repositorio**

```bash
 git clone https://github.com/Cachi1997/guitar-la-V2.git

 cd guitar-la-V2

 npm install

 npm run dev
```
