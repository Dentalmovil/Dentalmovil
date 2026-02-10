i### Hi there 👋

<!--
**Dentalmovil/Dentalmovil** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 Actualmente estoy trabajando en...
- 🌱 Actualmente estoy aprendiendo... ir
- 👯 Busco colaborar en...
- 🤔 Busco ayuda con...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
inversiones_comerciales
sobre_bitcoin
Que_necesitasita_saber
yo_te_puedo-ayudar
tengo_experienciaza
comienza_contactarme
en_mi_redes_sociales
echo '<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dentalmovilr4</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f8ff;
            color: #2c3e50;
        }
        h1 {
            border: 2px solid #3498db;
            padding: 20px;
            border-radius: 10px;
        }
    </style>
</head>
<body>
    <h1>Bienvenido a Dentalmovilr4</h1>
</body>
</html>' > index.html
git add index.html
"Mejora de diseño y soporte móvil"
git push -u origin main
git push -u origin main
# Si quieres un proyecto nuevo con Vite (recomendado en 2026)
npm create vite@latest mi-app -- --template react

# Entra a la carpeta
cd mi-app

# Instala las dependencias
npm install

# Inicia el servidor de desarrollo
npm run dev
{
  "name": "React con Vite y Herramientas Pro",
  "image": "mcr.microsoft.com/devcontainers/javascript-node:20",
  "customizations": {
    "vscode": {
      "extensions": [
        "dsznajder.es7-react-js-snippets", // Snippets de React
        "dbaeumer.vscode-eslint",         // Corrector de errores de código
        "esbenp.prettier-vscode",         // Formateador de código
        "christian-kohler.npm-intellisense", // Autocompletado de paquetes npm
        "bradlc.vscode-tailwindcss"       // Si usas Tailwind CSS
      ],
      "settings": {
        "editor.defaultFormatter": "esbenp.prettier-vscode",
        "editor.formatOnSave": true
      }
    }
  },
  "forwardPorts": [5173], // El puerto por defecto de Vite
  "postCreateCommand": "npm install" 
}
FROM mcr.microsoft.com/devcontainers/javascript-node:20

# Instalar herramientas adicionales de sistema si las necesitas
RUN apt-get update && apt-get install -y \
    curl \
    git \
    && rm -rf /var/lib/apt/lists/*

# (Opcional) Instalar globalmente herramientas como vercel o netlify CLI
RUN npm install -g vercel netlify-cli

