# 🛒 BEWEAR – Ecommerce Mobile

O **BEWEAR** é um ecommerce online focado na **experiência mobile**, oferecendo um design moderno e minimalista, pensado para facilitar a jornada de compra do usuário.  
Este projeto foi desenvolvido com **React**, **Next.js**, **Drizzle ORM**, **PostgreSQL**, **Shadcn UI** e **autenticação via Google**.

![Preview do BEWEAR]("")

---

## 🚀 Tecnologias Utilizadas

- **[React](https://react.dev/)** – Biblioteca para construção da interface.
- **[Next.js](https://nextjs.org/)** – Framework React para SSR, SSG e otimização de performance.
- **[Drizzle ORM](https://orm.drizzle.team/)** – ORM moderno para integração com o banco de dados.
- **[PostgreSQL](https://www.postgresql.org/)** – Banco de dados relacional.
- **[Shadcn UI](https://ui.shadcn.com/)** – Componentes estilizados prontos para React.
- **Autenticação com Google** – Login rápido e seguro.
- **Responsividade** – Layout totalmente adaptado para dispositivos móveis.

---

## 📌 Funcionalidades

- 📱 Interface responsiva e otimizada para mobile.
- 🔐 Login com conta Google.
- 🛍️ Listagem de produtos com imagens e descrições.
- ⭐ Seção de “Mais Vendidos”.
- 🛒 Carrinho de compras funcional.
- ⚡ Renderização otimizada com Next.js.

---

## 🛠️ Como Rodar Localmente

### 1️⃣ Clone o repositório

git clone https://github.com/WagnerK4uan/ecommerce-react-next.git
cd ecommerce-react-next

### 2️⃣ Instale as dependências

npm install

### 3️⃣ Configure as variáveis de ambiente

Crie um arquivo .env.local na raiz do projeto e adicione:

DATABASE_URL="postgresql://usuario:senha@localhost:5432/nome_do_banco"
BETTER_AUTH_SECRET="sua_chave_secreta"

GOOGLE_CLIENT_ID="sua_google_client_id"
GOOGLE_CLIENT_SECRET="seu_google_client_secret"

### 4️⃣ Execute as migrações com Drizzle

npx drizzle-kit push

### 5️⃣ Popule o banco com o seed

node seed.js

### 6️⃣ Inicie o servidor de desenvolvimento

npm run dev

---

## 📸 Preview

### 🏠 Tela Inicial
![Preview Home](docs/preview-home.png)

---

### 🛍️ Lista de Produtos
![Preview Produtos](docs/preview-products.png)

---

### 🛒 Carrinho de Compras
![Preview Carrinho](docs/preview-cart.png)
