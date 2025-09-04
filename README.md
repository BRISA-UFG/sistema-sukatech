# SUKATECH - Programando o Futuro

Sistema de gestão acadêmica para cursos de tecnologia e programação desenvolvido com React, TypeScript e Vite.

## 🚀 Tecnologias Utilizadas

### Frontend
- **React 18** - Biblioteca JavaScript para construção de interfaces
- **TypeScript** - Superset do JavaScript com tipagem estática
- **Vite** - Build tool e dev server rápido
- **React Router DOM** - Roteamento para aplicações React
- **Tailwind CSS** - Framework CSS utilitário
- **Shadcn/ui** - Componentes UI reutilizáveis

### Bibliotecas Principais
- **Radix UI** - Componentes primitivos acessíveis
- **React Hook Form** - Gerenciamento de formulários
- **Zod** - Validação de esquemas
- **Lucide React** - Ícones
- **Recharts** - Gráficos e visualizações
- **Date-fns** - Manipulação de datas
- **React Query** - Gerenciamento de estado do servidor

## 📋 Pré-requisitos

- **Node.js** (versão 18 ou superior)
- **npm** ou **yarn** ou **bun**

## 🛠️ Instalação

1. **Clone o repositório**
```bash
git clone <url-do-repositorio>
cd sukatech-futurescape
```

2. **Instale as dependências**
```bash
npm install
# ou
yarn install
# ou
bun install
```

## 🚀 Executando o Projeto

### Desenvolvimento
```bash
npm run dev
# ou
yarn dev
# ou
bun dev
```

O servidor de desenvolvimento será iniciado em `http://localhost:8080`

### Build para Produção
```bash
npm run build
# ou
yarn build
# ou
bun run build
```

### Preview da Build
```bash
npm run preview
# ou
yarn preview
# ou
bun run preview
```

### Linting
```bash
npm run lint
# ou
yarn lint
# ou
bun run lint
```

## 📁 Estrutura do Projeto

```
src/
├── components/          # Componentes reutilizáveis
│   ├── dashboard/      # Componentes do dashboard
│   ├── layout/         # Componentes de layout
│   ├── modals/         # Modais e formulários
│   └── ui/             # Componentes UI base
├── contexts/           # Contextos React
├── hooks/              # Custom hooks
├── lib/                # Utilitários e configurações
├── pages/              # Páginas da aplicação
└── main.tsx           # Ponto de entrada
```

## 🎨 Funcionalidades

- **Dashboard** - Visão geral do sistema
- **Gestão de Cursos** - CRUD de cursos
- **Gestão de Instrutores** - CRUD de instrutores
- **Gestão de Estudantes** - CRUD de estudantes
- **Gestão de Turmas** - CRUD de turmas
- **Calendário** - Visualização de eventos
- **Relatórios** - Relatórios e análises
- **Perfil** - Gerenciamento de perfil do usuário
- **Notificações** - Sistema de notificações

## 🔧 Configuração

O projeto utiliza:
- **Vite** como bundler e dev server
- **Tailwind CSS** para estilização
- **ESLint** para linting
- **TypeScript** para tipagem

## 📦 Scripts Disponíveis

- `dev` - Inicia o servidor de desenvolvimento
- `build` - Gera build de produção
- `build:dev` - Gera build de desenvolvimento
- `preview` - Preview da build de produção
- `lint` - Executa o linter

## 🌐 Acesso

Após executar `npm run dev`, acesse:
- **URL Local**: http://localhost:8080
- **URL Rede**: http://[seu-ip]:8080

## 📝 Licença

Este projeto é privado e pertence à SUKATECH.
