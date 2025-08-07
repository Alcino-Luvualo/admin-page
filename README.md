# ��️ Admin Dashboard

Uma interface de administração moderna e responsiva construída com React e Vite, oferecendo uma experiência de usuário intuitiva para gerenciamento de projetos e conteúdo.

## ✨ Características

- 🎨 **Design Moderno**: Interface limpa e profissional
- 📱 **Totalmente Responsivo**: Adapta-se a qualquer dispositivo
- ⚡ **Performance Otimizada**: Construído com Vite para carregamento rápido
- 🎯 **UX Intuitiva**: Navegação clara e organizada
- 🔄 **Scroll Inteligente**: Scroll apenas vertical dentro dos painéis
- 🎪 **Componentes Reutilizáveis**: Estrutura modular e escalável

## 🛠️ Tecnologias Utilizadas

### Frontend
- **React 19.1.0** - Biblioteca JavaScript para interfaces de usuário
- **React DOM 19.1.0** - Renderização do React no navegador
- **JSX** - Sintaxe para componentes React

### Build Tools & Development
- **Vite 7.0.4** - Build tool e servidor de desenvolvimento
- **@vitejs/plugin-react 4.6.0** - Plugin React para Vite
- **ESLint 9.30.1** - Linting e qualidade de código
- **@eslint/js 9.30.1** - Configuração JavaScript para ESLint
- **eslint-plugin-react-hooks 5.2.0** - Regras ESLint para React Hooks
- **eslint-plugin-react-refresh 0.4.20** - Regras ESLint para React Refresh

### TypeScript Support
- **@types/react 19.1.8** - Tipos TypeScript para React
- **@types/react-dom 19.1.6** - Tipos TypeScript para React DOM

### Dependencies
- **globals 16.3.0** - Variáveis globais para ESLint

## 🚀 Instalação

1. **Clone o repositório**
   ```bash
   git clone https://github.com/alcino-luvualo/admin-page.git
   cd admin-page
   ```

2. **Instale as dependências**
   ```bash
   npm install
   ```

3. **Execute em modo desenvolvimento**
   ```bash
   npm run dev
   ```

4. **Acesse a aplicação**
   ```
   http://localhost:5173
   ```

## 📦 Scripts Disponíveis

- `npm run dev` - Inicia o servidor de desenvolvimento
- `npm run build` - Gera build de produção
- `npm run preview` - Visualiza o build de produção
- `npm run lint` - Executa o linter

## 🏗️ Estrutura do Projeto

admin-page/
├── src/
│ ├── assets/ # Imagens e recursos
│ │ └── perfil.PNG # Imagem de perfil
│ ├── App.jsx # Componente principal
│ ├── Painel.jsx # Painel de conteúdo principal
│ ├── Dashbord.jsx # Sidebar de navegação
│ ├── index.css # Estilos globais e responsivos
│ └── main.jsx # Ponto de entrada da aplicação
├── public/ # Arquivos públicos
├── index.html # HTML base
├── package.json # Dependências e scripts
├── vite.config.js # Configuração do Vite
└── eslint.config.js # Configuração do ESLint



## 🎨 Componentes Principais

### Dashboard (Sidebar)
- Navegação principal com ícones SVG
- Menu responsivo que colapsa em mobile
- Links para diferentes seções (Home, Profile, Messages, etc.)

### Painel (Conteúdo Principal)
- Header com barra de busca e perfil do usuário
- Grid de projetos responsivo com cards
- Seção de anúncios e trends
- Scroll vertical independente em cada seção

## 📱 Responsividade

O projeto é totalmente responsivo com breakpoints otimizados:

- **Desktop (>1200px)**: Layout completo com sidebar fixa
- **Tablet (768px-1200px)**: Ajustes adaptativos no grid
- **Mobile (<768px)**: Layout em coluna com sidebar colapsada

## �� Funcionalidades

- ✅ Interface de administração completa
- ✅ Sistema de busca integrado
- ✅ Perfil de usuário com avatar
- ✅ Grid de projetos dinâmico e responsivo
- ✅ Seção de anúncios
- ✅ Lista de trends com perfis
- ✅ Navegação intuitiva com ícones
- ✅ Design responsivo para todos os dispositivos
- ✅ Scroll inteligente (apenas vertical)
- ✅ Hover effects e transições suaves

## 🔧 Personalização

O projeto foi desenvolvido com foco na facilidade de personalização:

- **Cores**: Variáveis CSS facilmente modificáveis
- **Componentes**: Estrutura modular e reutilizável
- **CSS**: Bem estruturado com media queries
- **Estrutura**: Escalável para novos componentes

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👨‍�� Autor

**Alcino Luvualo** - Desenvolvedor Front-End

---

⭐ Se este projeto foi útil para você, considere dar uma estrela no repositório!