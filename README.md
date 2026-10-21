# 👕 Bewear - E-commerce de Roupas

Bewear é uma plataforma de e-commerce moderna e responsiva para venda de vestuário, desenvolvida com foco em performance, experiência do usuário e código limpo.

**🌐 [Acesse o site ao vivo](https://bewear-lyart.vercel.app/)**
**🔌 [API do Projeto](https://bewear-api.onrender.com/)**

## 🚀 Tecnologias Utilizadas

O projeto foi construído utilizando o ecossistema mais moderno de desenvolvimento frontend:

- **[React 19](https://react.dev/)** - Biblioteca principal para construção da interface.
- **[TypeScript](https://www.typescriptlang.org/)** - Tipagem estática para maior segurança e manutenibilidade.
- **[Vite](https://vitejs.dev/)** - Tooling de build ultra rápido.
- **[Styled Components](https://styled-components.com/)** - Estilização baseada em componentes (CSS-in-JS).
- **[React Router Dom](https://reactrouter.com/)** - Gestão de navegação e rotas.
- **[Lucide React](https://lucide.dev/)** - Conjunto de ícones leves e consistentes.
- **Backend:** API REST hospedada no [Render](https://bewear-api.onrender.com/).

## 🛠️ Funcionalidades

- **Catálogo Dinâmico:** Busca de produtos, marcas e banners via API.
- **Sistema de Carrinho:** 
  - Adição, remoção e atualização de quantidades.
  - Persistência de itens utilizando `localStorage`.
  - Cálculo de subtotal em tempo real.
- **Navegação Fluida:** Rotas configuradas para Home e Detalhes do Produto.
- **Interface Responsiva:** Design adaptável para diferentes tamanhos de tela (Mobile First).
- **Gestão de Estado:** Uso de Context API para controle global do carrinho.

## 📦 Como executar o projeto

### Pré-requisitos
Certifique-se de ter o [Node.js](https://nodejs.org/) instalado em sua máquina.

### Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/bewear.git
   cd bewear
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

### Execução

Para rodar o projeto localmente:

1. **Inicie o frontend:**
   ```bash
   npm run dev
   ```

O projeto estará disponível em `http://localhost:5173`. O frontend já está conectado automaticamente à API de produção.

## 📁 Estrutura de Pastas

```text
src/
├── components/    # Componentes reutilizáveis (Botões, Cards, NavBar, etc)
├── contexts/      # Contextos de estado global (ex: CartContext)
├── hooks/         # Hooks personalizados (ex: useStoreData)
├── pages/         # Páginas da aplicação (Home, Product)
├── routes/        # Configuração de rotas do sistema
├── services/       # Integrações com API/Backend
├── types/         # Definições de tipos TypeScript
└── utils/         # Funções utilitárias e formatadores
```

## 📄 Licença

Este projeto está sob a licença MIT.
