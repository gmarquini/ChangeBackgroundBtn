# Projeto: Botão de Mudança de Cor com Efeito de Sombra

Este é um projeto simples em **HTML**, **CSS** e **JavaScript** que demonstra:

- Um **botão estilizado em forma de círculo**, que muda a cor de fundo da página ao ser clicado.
- Um efeito visual de **sombra personalizada**, simulando profundidade com CSS.
- Estrutura limpa e responsiva para fins didáticos, testes ou estética.

---

## Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript Vanilla

---

## Funcionalidades

- Ao clicar no botão “Change Color!”, a cor de fundo da página muda para uma cor aleatória.
- A sombra é criada por uma `<div>` posicionada de forma absoluta, com:
  - Mesma largura do container principal
  - Metade da altura
  - `border-radius` apenas nos cantos inferiores
  - Camada superior controlada com `z-index`
- O botão fica parcialmente fora do container para gerar um efeito visual de destaque.
- Efeitos de `hover` e `active` no botão simulam interações mais naturais.
