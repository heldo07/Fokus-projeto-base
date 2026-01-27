# 🕹️ Manipulação Dinâmica do DOM com JavaScript

Este projeto demonstra a aplicação prática de métodos essenciais do JavaScript para manipular o Document Object Model (DOM), permitindo a criação de interfaces interativas, responsivas e dinâmicas.

## 📝 Descrição

O objetivo deste projeto é exercitar como o JavaScript pode alterar o estado de uma página HTML em tempo real, respondendo às ações do usuário através da seleção de elementos, modificação de atributos e gerenciamento de eventos.

## 🚀 Tecnologias e Métodos Utilizados

Durante o desenvolvimento, foram explorados os seguintes recursos fundamentais:

*   **`querySelector`**: Método principal para selecionar e capturar elementos específicos do HTML (IDs, classes ou tags) de forma precisa.
*   **`addEventListener`**: Utilizado para monitorar e reagir a interações do usuário, como cliques e eventos de teclado, garantindo a interatividade.
*   **`innerHTML`**: Utilizado para atualizar e alterar o conteúdo de texto e as tags HTML internas dos elementos na tela.
*   **`setAttribute`**: Aplicado para modificar dinamicamente atributos de elementos, como a troca do caminho (`src`) de imagens ou links.
*   **`classList`**: Empregado para gerenciar classes CSS, permitindo adicionar, remover ou alternar (`toggle`) estilos e estados visuais.

## 🛠️ Como funciona o fluxo

A lógica da aplicação segue três pilares principais:

1.  **Seleção**: O script localiza os elementos necessários no HTML via `querySelector`.
2.  **Escuta**: Um "ouvinte" (`addEventListener`) aguarda uma ação específica do usuário (ex: um clique no botão).
3.  **Ação**: Ao detectar a interação, as funções disparam mudanças imediatas:
    *   Alteração de textos ou títulos com `innerHTML`.
    *   Troca de imagens ou ícones com `setAttribute`.
    *   Atualização de cores, visibilidade ou animações via `classList`.

## 💻 Exemplo Prático

```javascript
// Selecionando o botão e a imagem
const botao = document.querySelector('#meu-botao');
const imagem = document.querySelector('.banner');

// Escutando o clique
botao.addEventListener('click', () => {
    // Alterando o conteúdo e o estilo
    document.querySelector('h1').innerHTML = "Novo Título!";
    botao.classList.toggle('ativo');
    imagem.setAttribute('src', 'imagem-dinamica.png');
});
