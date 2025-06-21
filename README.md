# Ignite Teams

Este é um projeto de aplicativo para criação e gerenciamento de times e turmas, desenvolvido em **React Native** com **Expo**. O projeto foi criado como parte do módulo de React Native do curso **Ignite** da **Rocketseat**, com o objetivo de praticar e aprofundar conceitos como navegação, gerenciamento de estado e armazenamento local.


### Funcionalidades

* **Criação de Turmas:** Permite que o usuário crie novas turmas (ou times).
* **Listagem de Turmas:** Exibe todas as turmas criadas em uma lista.
* **Adicionar Participantes:** Permite adicionar pessoas a uma turma específica, dividindo-as em times.
* **Exclusão de Participantes e Turmas:** Funcionalidade para remover um participante ou uma turma inteira.
* **Armazenamento Local:** As informações sobre turmas e participantes são salvas diretamente no dispositivo, garantindo que os dados persistam.
* **Feedback ao Usuário:** Componentes de loading e mensagens para listas vazias, melhorando a experiência de uso.

### Tecnologias Utilizadas

* **React Native:** Framework para desenvolvimento de aplicativos móveis multiplataforma.
* **Expo:** Plataforma e ferramentas para facilitar o desenvolvimento com React Native.
* **TypeScript:** Superset do JavaScript para tipagem estática, garantindo um código mais robusto.
* **Styled Components:** Para a estilização de componentes de forma isolada e dinâmica.
* **React Navigation:** Biblioteca para gerenciamento da navegação entre as telas do app.
* **Async Storage:** Para armazenamento de dados de forma local e assíncrona no dispositivo.
* **Expo Google Fonts (Roboto):** Tipografia utilizada na aplicação para manter a consistência visual.


### Estrutura de Pastas

A estrutura do projeto foi organizada para separar responsabilidades de forma clara:

```
src
├── @types
├── assets
├── components
├── routes
├── screens
├── storage
└── theme
```
* **`components`**: Contém os componentes reutilizáveis da aplicação (Botões, Inputs, Cards, etc.).
* **`screens`**: Contém as telas do aplicativo (Turmas, Nova Turma, Jogadores).
* **`storage`**: Contém toda a lógica para interagir com o AsyncStorage (criar, ler, remover turmas e jogadores).
* **`routes`**: Define as rotas de navegação da aplicação.
* **`theme`**: Arquivos de estilização globais, como cores e fontes, para o Styled Components.

### Aprendizados

Durante o desenvolvimento deste projeto, foram aplicados e aprofundados os seguintes conceitos:

* Criação de componentes reutilizáveis e componentização.
* Gerenciamento de estado com hooks como `useState` e `useEffect`.
* Navegação entre telas com `React Navigation`, incluindo passagem de parâmetros.
* Estilização avançada com `Styled Components` e criação de temas globais.
* Manipulação de armazenamento local com `Async Storage`.
* Uso de `TypeScript` para tipagem de componentes, rotas e dados.
* Renderização de listas otimizadas com `FlatList`.

---

<p align="center">
Desenvolvido com 💜 durante o curso Ignite da Rocketseat! 🚀
</p>
