# Camarauth SDK Documentation

Documentación oficial del SDK de Camarauth para autenticación por WhatsApp.

## Estructura del proyecto

```
camarauth-sdk-docs/
├── index.mdx                    # Página principal
├── quickstart.mdx               # Guía de inicio rápido
├── docs.mdx                     # Índice global por perfiles
├── mint.json                    # Configuración de navegación/branding
├── package.json
├── concepts/                    # Arquitectura, flujo y seguridad
├── guides/                      # Testing, errores, deploy, migración
├── api-reference/               # Endpoints, WebSocket y errores
├── backend/                     # Documentación del backend
│   ├── overview.mdx
│   ├── installation.mdx
│   ├── quickstart.mdx
│   ├── database-adapter.mdx
│   ├── adapters/
│   │   ├── postgresql.mdx
│   │   ├── mongodb.mdx
│   │   ├── redis.mdx
│   │   └── custom.mdx
│   ├── classes/
│   │   ├── camarauth-backend.mdx
│   │   └── camarauth-client.mdx
│   └── interfaces/
│       ├── backend-config.mdx
│       ├── pin-data.mdx
│       ├── auth-response.mdx
│       └── user.mdx
├── react/                       # Documentación de React
│   ├── overview.mdx
│   ├── installation.mdx
│   ├── quickstart.mdx
│   ├── hooks/
│   │   ├── use-pin-auth.mdx
│   │   ├── use-pin-generator.mdx
│   │   ├── use-countdown.mdx
│   │   ├── use-auto-regeneration.mdx
│   │   ├── use-whatsapp-link.mdx
│   │   └── use-auth-context.mdx
│   └── interfaces/
│       ├── pin-auth-options.mdx
│       ├── pin-auth-state.mdx
│       ├── pin-generator-options.mdx
│       ├── countdown-options.mdx
│       ├── auto-regeneration-options.mdx
│       └── user.mdx
├── sdks/                        # Overview de SDKs
│   ├── overview.mdx
│   ├── nodejs.mdx
│   ├── react.mdx
│   ├── python.mdx
│   ├── go.mdx
│   ├── rust.mdx
│   ├── java.mdx
│   ├── dotnet.mdx
│   └── php.mdx
└── core/                        # Documentación core
    ├── overview.mdx
    ├── pin-generator.mdx
    ├── emoji-encoder.mdx
    ├── errors.mdx
    ├── storage.mdx
    └── jwt-utils.mdx
```

## Desarrollo local

```bash
# Instalar dependencias
npm install

# Iniciar servidor de desarrollo
npm run dev
```

## Construcción

```bash
npm run validate
npm run check:links
```

## SDKs documentados

- ✅ **Node.js Backend** - Servidor completo con Express y Socket.IO
- ✅ **React Frontend** - Hooks para integración en React
- 🚧 **Python** - En desarrollo (FastAPI/Flask)
- 🚧 **Go** - En desarrollo
- 🚧 **Rust** - En desarrollo
- 🚧 **Java** - En desarrollo
- 🚧 **.NET** - En desarrollo
- 🚧 **PHP** - En desarrollo

## Características de la documentación

- 📚 **Clases documentadas** - Todas las clases principales con ejemplos
- 🔧 **Interfaces** - Documentación completa de TypeScript interfaces
- 💻 **Ejemplos de código** - Ejemplos prácticos de integración
- 🎨 **Diseño moderno** - Interfaz inspirada en Auth0 Docs
- 📱 **Responsive** - Funciona en todos los dispositivos
- 🔍 **Buscador** - Búsqueda en tiempo real
- 🌙 **Modo oscuro** - Soporte para dark mode

## Contribuir

Para contribuir a la documentación:

1. Haz un fork del repositorio
2. Crea una rama para tu feature
3. Edita los archivos `.mdx`
4. Haz commit y push
5. Crea un Pull Request

## Tecnologías

- [Mintlify](https://mintlify.com/) - Plataforma de documentación
- MDX - Markdown con JSX
- TypeScript - Tipos para ejemplos de código

## Licencia

MIT © [Camarauth](https://camarauth.com)
