# Moovies 🐮
![moovies logo](/src/assets/moovies.svg)


Moovies is a project developed in group by:
- [Gabriel Herdina](https://linkedin.com/in/gabrielherdina)
- [Giovane Saes](https://linkedin.com/in/giovanesaesdev)
- [Isabel Terenzi](https://linkedin.com/in/isabel-terenzi)
- [Rafael Almeida](https://linkedin.com/in/rafael-almeida-0a40361a7)
- [Rafael Kaique](https://linkedin.com/in/rafaelrksilva)


# Ferramentas ⚙️
As ferramentas utilizadas nesse projeto foram:
- [Vite](https://vitejs.dev/), para inicialização do projeto;
- [React](https://pt-br.reactjs.org/), para criação da interface;
- [Styled Component](https://styled-components.com/), para estilização;
- [Router Dom V.6](https://v6.reactrouter.com/), para roteamento;
- [Axios](https://axios-http.com/docs/intro), para requisições HTTP;
- [Eslint](https://eslint.org/), para padronização.

# Style Guide 🎨
Para o style guide desse projeto, foram utilizadas as mesmas cores do site oficial da Hybrid Development, afim de manter a aplicação característica conforme a identidade da empresa. A única mudança, foi utilizar a fonte Sora em toda a aplicação.

# Detalhes técnicos 🧠

### Fotos dos albuns com scroll horizontal
Foi optado a utilização dessa forma de navegação por conta da API retornar muitas fotos em cada album, assim o usuário pode apenas deslizar o scroll e passar várias fotos em sequência, sem prender a atenção em uma única imagem do thumbnail, e, caso o usuário esteja na última foto, e queira retornar para a primeira, ou vice-versa, basta um scroll no desktop ou um drag no mobile.

### Modal de deleção dos posts
O modal de deleção foi adotado devido à possibilidade de acontecer um clique ou touch do usuário sem querer no botão de deletar post, assim, o modal é essencial para que não aconteça nenhuma deleção indesejada na aplicação, provendo uma melhor experiência para o usuário.

### Formulário de edição na mesma página dos posts
O formulário de edição foi implementada na mesma página dos posts afim de evitar levar o usuário para outra página e manter o foco na página de posts, visto que a alteração seria somente no título e no conteúdo do post.

### Estilização com Styled Components
O CSS-in-JS foi utilizado nesse projeto para facilitar o uso de temas globais e variáveis CSS globais com o Theme Provider, além de permitir o uso de lógica e utilização das props na estilização dos componentes, provendo melhor dinamismo pras páginas.

# Inicializando o projeto na máquina local

### Clonando o repositório
Escolha uma pasta e clone este repositório na sua máquina via chave SSH ou link HTTP: \
```git clone git@github.com:giovanedann/moovies.git``` \
```git clone https://github.com/giovanedann/moovies.git```

### Selecionando a pasta do arquivo

#### Opção 1 - Via terminal
Primeiro certifique-se de que está na mesma pasta em que deu o clone no projeto, e execute o seguinte comando: \
```cd moovies.git```

#### Opção 2 - Navegando até a pasta do projeto navegando pelo sistema operacional


### Abrindo o projeto no VSCode
#### Opção 1 - Via terminal
Primeiro certifique-se de que está na pasta do projeto e execute o seguinte comando: \
```code .```

#### Opção 2 - Pelo VSCode
Clique na opção Abrir Arquivo / Open Folder do VSCode e selecione a pasta em que o clone foi feito (por padrão, test-hiring-git)

### Instalando as dependências do projeto

Atenção, esse passo é importante para que o projeto funcione corretamente, caso as dependências não sejam instaladas, provavelmente o projeto não vai funcionar na máquina local.

#### com npm
Dentro da pasta do arquivo, rode o seguinte comando:
```npm install``` ou ```npm i```

#### com yarn
Dentro da pasta do arquivo, rode o seguinte comando:
```yarn``` ou ```yarn install```

### Executando o projeto
Após instaladas as dependências, execute o seguinte comando: \
```npm run dev``` ou ```yarn dev```

Acesse o projeto pelo link que aparecer no terminal (http://localhost:xxxx).
Caso queira ver a aplicação em outro dispositivo conectado à mesma rede de internet da sua máquina (um celular, por exemplo), acesse o link Network que aparecerá no terminal!

