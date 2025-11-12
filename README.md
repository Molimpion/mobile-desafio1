# mobile-desafio1

Este repositório contém o projeto `hello-rn`, um aplicativo simples desenvolvido como parte de um desafio mobile. O aplicativo utiliza React Native com Expo e TypeScript.

## 🚀 Sobre o Projeto

O aplicativo exibe uma lista dos três Pokémon iniciais (Bulbasauro, Charmander e Squirtle). Ao clicar no botão "Dados do pokémon" correspondente, o aplicativo faz uma chamada à [PokeAPI](https://pokeapi.co/) para buscar e exibir informações detalhadas daquele Pokémon, incluindo seu nome, peso e imagem oficial.

### Funcionalidades

  * Exibição de uma lista de Pokémon pré-definida.
  * Busca de dados em tempo real da PokeAPI (`https://pokeapi.co/api/v2/pokemon/`).
  * Exibição dinâmica do nome, peso e imagem do Pokémon selecionado.
  * Tratamento de erro básico caso a busca falhe.

## 🛠️ Tecnologias Utilizadas

O projeto foi construído utilizando as seguintes tecnologias:

  * **React Native**
  * **Expo**
  * **TypeScript**

## 🏁 Como Executar

Para rodar este projeto localmente, siga os passos abaixo:

1.  Clone este repositório:

    ```bash
    git clone [URL_DO_REPOSITORIO]
    ```

2.  Navegue até o diretório do aplicativo:

    ```bash
    cd molimpion/mobile-desafio1/mobile-desafio1-155e5b14d06a29b5ccf4f9c79d2ac8504b82423e/hello-rn
    ```

3.  Instale as dependências do projeto:

    ```bash
    npm install
    ```

4.  Inicie o servidor de desenvolvimento do Expo:

    ```bash
    npm start
    ```

    *(Este comando executa `expo start`)*

5.  Após iniciar o servidor, você pode optar por rodar o aplicativo:

      * No Android (via Expo Go ou simulador): `npm run android`
      * No iOS (via Expo Go ou simulador): `npm run ios`
      * Na Web: `npm run web`
