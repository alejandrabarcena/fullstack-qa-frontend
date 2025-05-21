## 🛠️ Herramientas de calidad de código

Este proyecto implementa una configuración sólida para mantener un código limpio, consistente y profesional:

- 🎯 **ESLint** — Detección de errores de sintaxis y problemas comunes en JS/React
- 💅 **Prettier** — Formateador de código automático
- 🐶 **Husky** — Hooks que bloquean commits si el código no cumple con los estándares

---

### 🔒 Hook de pre-commit configurado

Antes de cada commit, se ejecutan automáticamente:

```bash
npx eslint .
npx prettier --check .
```

---

## 🧪 Comandos útiles para desarrollo

| Comando                   | Descripción                                      |
| ------------------------- | ------------------------------------------------ |
| `npm install`             | Instala todas las dependencias del proyecto      |
| `npm run dev`             | Levanta el servidor de desarrollo con Vite       |
| `npx eslint .`            | Ejecuta ESLint sobre todo el código              |
| `npx prettier --write .`  | Aplica formateo automático con Prettier          |
| `git add . && git commit` | Guarda cambios y ejecuta verificación automática |

---

🚀 Proyecto en evolución mantenido por **Alejandra Bárcena**  
_Full Stack QA Dev con sparkle, visión crítica y su fiel pug a un lado 🐾✨_

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
npx prettier --check .

````

```bash
npx eslint .
npx prettier --check .
````
