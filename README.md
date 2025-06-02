# Projeto MemeVerse - README

## 📱 Visão Geral

O MemeVerse é uma plataforma de compartilhamento e interação com memes, criada para reunir os melhores e mais divertidos conteúdos da internet. O projeto foi desenvolvido utilizando Next.js e React, com foco em componentização e uso de props para criar uma interface dinâmica e reutilizável.

## ✨ Características

- 🖼️ Feed personalizado de memes
- 👤 Perfis de criadores em destaque
- 🏷️ Categorização por temas
- 🔥 Seção de memes em tendência
- 📅 Eventos da comunidade
- 💌 Newsletter para receber os melhores memes
- 💎 Plano premium com recursos exclusivos

## 🛠️ Tecnologias Utilizadas

- [Next.js](https://nextjs.org/) - Framework React com renderização híbrida
- [React](https://reactjs.org/) - Biblioteca JavaScript para construção de interfaces
- [CSS Modules](https://github.com/css-modules/css-modules) - Estilização com escopo local

## 🚀 Iniciando o Projeto

### Pré-requisitos

- Node.js (versão 14 ou superior)
- npm ou yarn

### Instalação

1. Clone o repositório:
```bash
git clone https://github.com/vinipereir/meme-verse.git
cd meme-verse
```

2. Instale as dependências:
```bash
npm install
# ou
yarn install
```

3. Execute o servidor de desenvolvimento:
```bash
npm run dev
# ou
yarn dev
```

4. Abra [http://localhost:3000](http://localhost:3000) no seu navegador para ver o resultado.

## 📂 Estrutura do Projeto

```
/src
  /app             # Rotas e layouts da aplicação
  /components      # Componentes reutilizáveis
    /CategoriesSection
    /CreatorCard
    /CreatorsSection
    /EventCard
    /FeaturedMemeCard
    /FeaturedMemesSection
    /Feed
    /Footer
    /Header
    /HeroSection
    /InteractionBar
    /MemeCard
    /NewsletterSection
    /PremiumCard
    /Sidebar
    /TagCloud
```

## 🧩 Componentes Principais

### Header
Barra de navegação principal com logo e links.

### HeroSection
Destaque para o "Meme do Dia" com estatísticas e informações do autor.

### Feed
Lista de memes com filtros por categorias e tendências.

### MemeCard
Card individual de meme com título, descrição, autor e interações.

### InteractionBar
Barra de interação com botões para curtir, comentar, compartilhar e salvar.

### Sidebar
Painel lateral com eventos próximos, oferta premium e tags populares.

## 🎨 Estilo e Design

O projeto utiliza uma paleta de cores baseada em tons de azul (#4e5de4 e #8a94f8) com alto contraste para destacar elementos importantes. A interface é clean, moderna e responsiva, adaptando-se a diferentes tamanhos de tela.

## 📦 Scripts Disponíveis

- `npm run dev` - Executa o servidor de desenvolvimento com turbopack
- `npm run build` - Compila o projeto para produção
- `npm run start` - Inicia o servidor de produção
- `npm run lint` - Executa verificação de código com ESLint

## 🔜 Próximos Passos

- Implementação de autenticação de usuários
- Sistema de comentários em tempo real
- Editor de memes integrado
- Modo escuro
- Notificações personalizadas

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

---

Desenvolvido com 💙 e muito humor.