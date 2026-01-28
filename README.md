# Manipulação Dinâmica do DOM com JavaScript

Este projeto demonstra a aplicação prática de métodos essenciais do JavaScript para manipular o **Document Object Model (DOM)**, permitindo a criação de interfaces interativas, responsivas e dinâmicas.

## 🔗 [Clique aqui para acessar o projeto em tempo real](https://heldo07.github.io/Fokus-projeto-base/)

## 📝 Descrição
O objetivo deste projeto é exercitar como o JavaScript pode alterar o estado de uma página HTML em tempo real, respondendo às ações do usuário através da seleção de elementos, modificação de atributos e gerenciamento de eventos.

## 🎯 Objetivos e Aprendizados
Durante o desenvolvimento, foram alcançados os seguintes marcos técnicos:
*   **Seletores CSS:** Identificação e utilização de seletores para interação precisa com elementos HTML via JS.
*   **Manipulação do DOM:** Aplicação de lógica JavaScript para alterar a estrutura e o estilo da página.
*   **Gestão de Eventos:** Controle total sobre interações do usuário, como cliques, envios de formulário e eventos de teclado.
*   **Gestão de Estado:** Resolução de problemas complexos utilizando manipulação de **Arrays** e lógica de programação.
*   **Persistência de Dados:** Implementação de estratégias eficientes com [LocalStorage](https://developer.mozilla.org) para garantir que as informações persistam entre as sessões do navegador.
*   **UX Dinâmica:** Criação de interfaces que melhoram a experiência do usuário através de elementos que reagem instantaneamente.

## 🚀 Tecnologias e Métodos Utilizados
*   `querySelector`: Seleção precisa de IDs, classes ou tags.
*   `addEventListener`: Monitoramento de interações (cliques, formulários).
*   `innerHTML`: Atualização dinâmica de conteúdos e tags.
*   `setAttribute`: Modificação de atributos (como caminhos de imagens `src`).
*   `classList`: Gerenciamento de estilos CSS (add, remove, toggle).
*   `JSON.stringify()` / `JSON.parse()`: Essenciais para salvar e recuperar dados no navegador.

## 🛠️ Como funciona o fluxo
1.  **Seleção:** O script localiza os elementos necessários no HTML via `querySelector`.
2.  **Escuta:** Um ouvinte (`addEventListener`) aguarda uma ação específica do usuário (ex: um clique no botão).
3.  **Ação e Persistência:** Ao detectar a interação, as funções disparam mudanças imediatas na interface e salvam o estado atualizado para persistência entre sessões.

