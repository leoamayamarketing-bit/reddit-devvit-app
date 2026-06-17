# reddit-devvit-app

App interactiva para Reddit construida con Devvit — posts personalizados, menús para moderadores y automatizaciones.

## Requisitos

- Node.js >= 22.6.0
- Cuenta de Reddit (para desarrolladores)

## Instalación

```bash
npm install
npx devvit login
```

## Uso

```bash
# Menú interactivo
./dev.sh

# Playtest en subreddit de prueba
./dev.sh dev

# Build
./dev.sh build

# Deploy a Reddit
./dev.sh deploy

# Publicar
./dev.sh launch
```

## Scripts

| Comando | Descripción |
|---------|-------------|
| `npm run dev` | Playtest en vivo |
| `npm run build` | Compilar cliente y servidor |
| `npm run deploy` | Subir nueva versión |
| `npm run launch` | Publicar para revisión |
| `npm run login` | Iniciar sesión en Reddit |
| `npm run type-check` | Verificar tipos TypeScript |

## Estructura

```
src/
├── client/     # Código del lado del cliente (post interactivo)
├── server/     # Lógica del servidor (triggers, menús)
└── shared/     # Tipos compartidos
```
