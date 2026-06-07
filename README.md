# KILLAMI - POS Restaurant 🍽️

Sistema de Punto de Venta (POS) profesional para restaurantes de comida rápida, inspirado en OlaClick.

## Características principales

- ✅ **Menú Digital** - Catálogo de productos con imágenes y descripciones
- ✅ **QR Code** - Acceso rápido al menú desde celular
- ✅ **PDV (Punto de Venta)** - Gestión de pedidos en tiempo real
- ✅ **Gestión de Mesas** - Control de mesas y ocupación
- ✅ **Caja y Arqueo** - Cierre de caja y reportes
- ✅ **Impresión de Comandas** - Impresoras térmicas
- ✅ **Inventario** - Control de stock y alertas
- ✅ **Reportes** - Estadísticas de ventas
- ✅ **Usuarios Multirol** - Permisos por rol (Admin, Mesero, Chef, Caja)

## Stack Tecnológico

### Frontend
- React 18+ con TypeScript
- Vite como bundler
- Tailwind CSS para estilos
- Redux Toolkit para estado global
- React Router para navegación

### Backend
- Node.js con Express
- TypeScript
- PostgreSQL
- Prisma ORM
- JWT para autenticación
- Socket.io para tiempo real

### Mobile
- React Native
- Expo

## Estructura del Proyecto

```
KILLAMI/
├── frontend/              # Aplicación React
│   ├── src/
│   ├── public/
│   └── package.json
├── backend/               # Servidor Node.js + Express
│   ├── src/
│   ├── prisma/
│   └── package.json
├── mobile/                # App React Native
│   └── package.json
├── docs/                  # Documentación
└── README.md
```

## Requisitos

- Node.js >= 16
- npm o yarn
- PostgreSQL >= 12
- Git

## Instalación Rápida

### Backend
```bash
cd backend
npm install
cp .env.example .env
npx prisma migrate dev
npm run dev
```

### Frontend
```bash
cd frontend
npm install
npm run dev
```

El sistema estará disponible en `http://localhost:5173`

## Licencia

MIT

---

**Autor:** ja2935138-art
