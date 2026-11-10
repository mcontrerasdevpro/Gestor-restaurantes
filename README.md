# Gestor de restaurantes

Web para un restaurante con carta digital, menú del día y reserva de mesa online. Pensada como plantilla que se adapta a cualquier restaurante cambiando textos, platos e imágenes.

> **Estado:** frontend funcional. El backend (Flask) está pendiente: las reservas todavía no se guardan en ninguna base de datos.

## Qué hace

- **Inicio:** portada con la imagen y el estilo del local
- **Carta:** platos por categorías, con foto y precio
- **Menú del día:** selección con carrito flotante que suma el total, para reservar el menú por adelantado
- **Reservas:** formulario por pasos con fecha, hora, número de personas y datos de contacto
- **Contacto:** dirección y formas de contacto

## Stack

React 19 · Vite · Tailwind CSS 4 · Framer Motion · react-datepicker · Lucide

## Estructura

```
frontend/
  src/components/   Navbar, Hero, Carta, DailyMenu, FloatingCart, Reservas, Contacto, Footer
  src/assets/       Fotos de platos y del local
backend/            Reservado para la API (pendiente)
```

## Puesta en marcha

```bash
cd frontend
npm install
npm run dev     # http://localhost:5173
```

## Próximos pasos

- API en Flask para guardar reservas y pedidos de menú
- Panel para que el restaurante vea y gestione las reservas
- Confirmación de reserva por email

## Autor

Miguel Contreras · [mcontreras.dev](https://www.mcontreras.dev) · [NexuraIA](https://www.nexuraia.com)
