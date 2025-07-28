# 🧮 Calculadora Simples com React

Este projeto é uma calculadora simples desenvolvida com React e Styled-components. Ele oferece funcionalidades básicas de uma calculadora, com uma interface minimalista e responsiva.

## ✨ Funcionalidades

  * **Operações Aritméticas Básicas:** Suporta adição (+), subtração (-), multiplicação (\*) e divisão (/).
  * **Limpar Entrada:** Botão 'C' para limpar o número atual e 'CE' para limpar todas as entradas.
  * **Design Minimalista:** Interface clara e fácil de usar.
  * **Componentes Reutilizáveis:** Estrutura baseada em componentes React para botões e exibição de entrada.

## 🛠️ Tecnologias Utilizadas

O projeto foi construído com as seguintes tecnologias:

  * **React:** Biblioteca JavaScript para a construção da interface de usuário.
  * **Styled-components:** Para estilização dos componentes, permitindo CSS-in-JS.
  * **JavaScript (ES6+):** Lógica principal da calculadora.

## 📂 Estrutura do Projeto

A estrutura principal do projeto é a seguinte:

```
├── public/                     # Arquivos públicos (HTML, ícones, manifest) 🌐
│   ├── favicon.ico
│   ├── index.html              # Arquivo HTML principal da aplicação
│   ├── logo192.png             # Ícone do aplicativo
│   └── manifest.json           # Manifest da Progressive Web App (PWA)
├── src/                        # Código-fonte da aplicação 💻
│   ├── components/             # Componentes reutilizáveis (Button, Input) 🧩
│   │   ├── Button/
│   │   └── Input/
│   ├── global.js               # Estilos globais da aplicação 🎨
│   ├── styles.js               # Estilos dos componentes principais (Container, Content, Row) 🎨
│   └── App.js                  # Lógica principal da calculadora e renderização dos componentes
├── package.json                # Gerenciamento de dependências e scripts 📦
├── package-lock.json           # Bloqueio de versões de dependências 🔒
└── .gitignore                  # Arquivos e diretórios a serem ignorados pelo Git 🚫
```

## 🚀 Como Começar

Siga estas instruções para obter uma cópia do projeto em execução na sua máquina local para desenvolvimento e testes.

### 📋 Pré-requisitos

Certifique-se de ter o Node.js e o npm (ou Yarn) instalados em sua máquina.

### ⬇️ Instalação

1.  **Clone o repositório:**
    ```bash
    git clone <URL_DO_SEU_REPOSITORIO>
    cd calculadora-react-dio
    ```
2.  **Instale as dependências:**
    Usando npm:
    ```bash
    npm install
    ```
    Ou usando Yarn:
    ```bash
    yarn install
    ```

### ▶️ Executando a Aplicação

Para iniciar o servidor de desenvolvimento:

```bash
npm start
# ou
yarn start
```

Isso abrirá o aplicativo em seu navegador padrão em `http://localhost:3000`. A página será recarregada automaticamente quando você fizer alterações no código. Quaisquer erros de lint também serão visíveis no console.

## 📜 Scripts Disponíveis

No diretório do projeto, você pode executar:

  * **`npm start`**: 🚀 Inicia o aplicativo em modo de desenvolvimento.
  * **`npm test`**: 🧪 Inicia o executor de testes em modo de observação interativo.
  * **`npm run build`**: 🏗️ Compila o aplicativo para produção na pasta `build`.
  * **`npm run eject`**:  eject Esta é uma operação unidirecional. Ela removerá a dependência única de build do seu projeto e copiará todos os arquivos de configuração e dependências transitivas para o seu projeto, dando-lhe controle total sobre eles. Você não precisa usar `eject`.

## ⚖️ Licença

Este projeto é de código aberto e está disponível sob a licença ISC.
