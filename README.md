# PROJETO FACULDADE - nome ficticio:

**EFICAZES**

# Recriacao do projeto->

**GABINE HEADSET**

![Banner do Projeto](<(frontend/assets/images/Capa.png)> "Imagem de capa do figma utilizado para recriação")

## 📚 **Descrição**

> Uma landpage do projeto GABINI HEADSET para um projeto da faculdade em conjunto com a empresa EFICAZ.
> Sistema de Login e criação de usuários com conexão ao banco de dados via MySQL através de entradas API em C#

---

## 🛠️ **Funcionalidades**

- ✅ Criação de Usuário
- ✅ Sistema de Autenticação utilizando TOKEN JWT
- ✅ Sistema de Login
- ✅ Sistema de Edição de informações do Usuário
- 🚧 Sistema de Auth - route protect em página (em desenvolvimento)

---

## 🚀 **Tecnologias Utilizadas**

- [Vue.js](https://vuejs.org/)
- [Vue Router](https://router.vuejs.org/)
- [Axios](https://router.vuejs.org/)
- [CSS](https://www.w3schools.com/cssref/index.php)
- [Tailwind](https://tailwindcss.com/)

---

## 🖥️ Como Executar a parte do Front-end

### Clone este repositório:

```bash
git clone https://github.com/seu-usuario/seu-repo.git
```

### Acesse o diretório do projeto:

```bash
cd frontend
```

### Instale as dependências:

```bash
npm install
```

### Inicie a aplicação:

```bash
npm run dev
```

---

## 🖥️ Back-end

A estrutura do projeto é organizada em várias camadas, cada uma com responsabilidades bem definidas:

### Application:

Contém a lógica de negócios e serviços.

### Core:

Inclui as entidades de domínio, DTOs (Data Transfer Objects) e interfaces de repositórios.

### Infrastructure:

Gerencia a camada de dados, incluindo a configuração do Entity Framework Core, o contexto do banco de dados e as migrações.

### Presentation:

Contém a API Web, controladores e configurações da aplicação.

## Requisitos

Para executar o projeto, você precisará dos seguintes requisitos:

> .NET SDK 8.0
> MySQL
> Ferramenta de linha de comando dotnet format e dotnet ef

---

## 📂 **Estrutura do Projeto**

EFICAZES/
├── frontend/
│ ├── src/
│ │ ├── assets/
│ │ │ ├── Fonts/
│ │ │ ├── icons/
│ │ │ ├── images/
│ │ │ ├── fonts.css
│ │ │ └── tailwind.css
│ │ ├── components/
│ │ │ ├── AddressUser.vue
│ │ │ ├── BoxSwipe.vue
│ │ │ ├── Footer-Home.vue
│ │ │ ├── GiftSelection.vue
│ │ │ ├── Hero.vue
│ │ │ ├── Login.vue
│ │ │ ├── NavBar.vue
│ │ │ ├── NewProducts.vue
│ │ │ ├── Offer.vue
│ │ │ ├── ProductEmphasis.vue
│ │ │ ├── RegistrationUser.vue
│ │ │ └── UserProfile.vue
│ │ ├── router/
│ │ │ └── index.js
│ │ ├── services/
│ │ │ └── PostUserDataService.js
│ │ ├── stores/
│ │ │ └── auth.js
│ │ ├── views/
│ │ │ ├── AddressUserView.vue
│ │ │ ├── BoxSwipeView.vue
│ │ │ ├── FooterHomeView.vue
│ │ │ ├── GiftSelectionView.vue
│ │ │ ├── HeroView.vue
│ │ │ ├── HomePageView.vue
│ │ │ ├── LoginView.vue
│ │ │ ├── NavBarView.vue
│ │ │ ├── NewProductsView.vue
│ │ │ ├── OfferView.vue
│ │ │ ├── ProductEmphasisView.vue
│ │ │ ├── RegistrationUserView.vue
│ │ │ └── UserProfileView.vue
│ │ ├── App.vue
│ │ ├── http-common.js
│ │ └── main.js
│
├── backend/
│ ├── Application/
│ │ ├── Services/
│ │ │ ├── ClienteService.cs
│ │ │ └── EnderecoService.cs
│ ├── Core/
│ │ ├── DTO/
│ │ │ ├── ClienteDTO.cs
│ │ │ ├── EnderecoDTO.cs
│ │ │ └── SignInClienteDTO.cs
│ │ ├── Models/
│ │ │ ├── Cliente.cs
│ │ │ ├── Endereco.cs
│ │ │ └── Imagem.cs
│ │ ├── Repositories/
│ │ └── Services/
│ ├── Infrastructure/
│ │ ├── Repositories/
│ │ │ ├── AuthRepository.cs
│ │ │ ├── ClienteRepository.cs
│ │ │ ├── EnderecoRepository.cs
│ │ │ └── Data/
│ │ │ ├── EficazesDbContext.cs
│ │ │ └── Migrations/
│ │ └── Services/
│ │ └── ImagemService.cs
│ ├── Presentation/
│ │ ├── Controllers/
│ │ │ ├── AuthController.cs
│ │ │ ├── ClienteController.cs
│ │ │ └── EnderecoController.cs
│ │ └── Services/
│ │ ├── AuthService.cs
│ │ └── TokenService.cs

---

## Grupo Eficazes

### Integrantes

```bash
Higor Miguel Pavim Lopes | RA ->1971780
Lucas Garcia Ribeiro | RA ->1971977
Luiz Fernando Ferreira do Carmo | RA ->1965671
João Victor Marque Seixas | RA ->1974858
Josué Miguel Ramos de Souza | RA ->1976990
Julio Cesar Golfredo Carneiro | RA ->1963824
```
