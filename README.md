# BuscArt3

BuscArt es una plataforma que conecta artistas con compradores de arte, facilitando la exposición y comercialización de obras artísticas.

## Características

- Búsqueda y filtrado de artistas por categorías
- Panel de descubrimiento con sistema de swipe
- Blog de tendencias artísticas
- Sistema de chat integrado
- Notificaciones en tiempo real
- Perfiles personalizables para artistas y compradores

## Tecnologías

- Frontend: React + Vite
- Backend: Node.js
- Base de datos: Firebase
- UI: Material-UI + Radix UI
- Autenticación: Firebase Auth

## Instalación

1. Clonar el repositorio:
```bash
git clone https://github.com/yourusername/BuscArt3.git
```

2. Instalar dependencias del cliente:
```bash
cd client
npm install
```

3. Instalar dependencias del servidor:
```bash
cd ../server
npm install
```

4. Configurar variables de entorno:
Crear archivo `.env` en la raíz del proyecto con las siguientes variables:
```
VITE_FIREBASE_API_KEY=your_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_storage_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
VITE_FIREBASE_APP_ID=your_app_id
```

5. Iniciar el servidor de desarrollo:
```bash
# En la carpeta server
npm run dev

# En la carpeta client
npm run dev
```

## Estructura del Proyecto

```
BuscArt3/
├── client/                # Frontend React
│   ├── src/
│   │   ├── components/    # Componentes React
│   │   ├── hooks/        # Custom hooks
│   │   ├── utils/        # Utilidades
│   │   └── App.jsx       # Componente principal
│   └── package.json
├── server/                # Backend Node.js
│   ├── src/
│   │   ├── routes/       # Rutas API
│   │   ├── controllers/  # Controladores
│   │   └── models/       # Modelos de datos
│   └── package.json
└── README.md
```

## Contribuir

1. Fork el proyecto
2. Crear una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abrir un Pull Request

## Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.
