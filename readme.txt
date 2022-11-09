/* Iniciar o projeto */
 npm install next react react-dom

 /* retirar ^ no package.json, para definir a versão atual, se ter que atualizar  */

 /* Inserir nos scripts */

   "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start",
    "lint": "next lint"
  },

 /* parar CTRL + C iniciar o projeto npm run dev */

 /* Instalar Styled Components CSS */
   npm install styled-components

/* Criar o arquivo Next.config.js */
/** @type {import('next').NextConfig} */

const nextConfig = {
  reactStrictMode: true,
  compiler: {
    styledComponents: true,
  },
};

module.exports = nextConfig;