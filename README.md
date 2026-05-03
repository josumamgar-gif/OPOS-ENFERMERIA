# OPE Enfermería 2026 — Osakidetza

App de estudio para las oposiciones de enfermería. 417 preguntas clasificadas en 23 temarios.

## Subir a Vercel (paso a paso)

### 1. Sube el proyecto a GitHub

En GitHub, crea un repositorio nuevo llamado `enfermeria-opos` (privado o público, da igual).

Luego desde tu ordenador, en la carpeta del proyecto:

```bash
git init
git add .
git commit -m "primera version"
git remote add origin https://github.com/TU_USUARIO/enfermeria-opos.git
git push -u origin main
```

### 2. Despliega en Vercel

1. Ve a [vercel.com](https://vercel.com) e inicia sesión con tu cuenta de GitHub
2. Pulsa **"Add New Project"**
3. Selecciona el repositorio `enfermeria-opos`
4. Deja toda la configuración por defecto (Vercel detecta Vite solo)
5. Pulsa **Deploy**

En 2 minutos tendrás una URL pública tipo `enfermeria-opos.vercel.app`.

### Desarrollo local

```bash
npm install
npm run dev
```
"# OPOS-ENFERMERIA" 
