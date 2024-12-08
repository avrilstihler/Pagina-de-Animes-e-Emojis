# Projeto de Animes e Emojis 🎥🍥⚔️

Este projeto foi desenvolvido totalmente em **HTML**, sem o uso de CSS externo ou frameworks. A proposta é criar uma página interativa e simples para explorar diferentes animes usando emojis. Cada anime é representado por um emoji, e ao clicar no emoji, o usuário é redirecionado para uma página com detalhes sobre o anime, incluindo uma breve descrição, imagem e o link para assistir à abertura no YouTube.

## Objetivo
O objetivo deste projeto é explorar e aprender os conceitos básicos de HTML através da criação de uma página simples e interativa, utilizando apenas HTML e sem o uso de CSS ou JavaScript externos. O projeto foi desenvolvido para ajudar a entender como estruturar conteúdo na web e aplicar estilos diretamente nas tags HTML, de forma acessível e fácil de entender. Com esse projeto, é possível aprender sobre a estrutura de páginas web, links, imagens, e interatividade de uma maneira prática e divertida.

## Funcionalidade

- **Página inicial**: A página principal apresenta emojis que representam animes populares. Ao clicar em um emoji, o usuário é levado a uma página com informações sobre o anime selecionado.
  
- **Páginas dos animes**: Cada página contém:
  - Uma breve descrição do anime.
  - Uma imagem do anime, com bordas arredondadas.
  - Um link para assistir à abertura do anime no YouTube.
  - Um link para retornar à página inicial.

Tudo foi feito de forma simples e visualmente agradável, sem o uso de CSS externo, com os estilos aplicados diretamente no próprio HTML.

## Estrutura do Projeto

A estrutura do projeto é composta pelos seguintes arquivos e pastas:

- **`index.html`**: Página inicial com os emojis dos animes e links para as páginas dos animes.
- **`naruto.html`**: Página com detalhes sobre o anime *Naruto*.
- **`attackontitan.html`**: Página com detalhes sobre o anime *Attack on Titan*.
- **`deathnote.html`**: Página com detalhes sobre o anime *Death Note*.
- **`onepiece.html`**: Página com detalhes sobre o anime *One Piece*.
- **`demonslayer.html`**: Página com detalhes sobre o anime *Demon Slayer*.
- **`images/`**: Pasta que contém as imagens dos animes.

## Como Usar

Acesse o site pelo link: [https://avrilstihler.github.io/Pagina-Simples-em-HTML/](https://avrilstihler.github.io/Pagina-Simples-em-HTML/)


Ou siga os passos abaixo:


1. **Clonar o Repositório**:
   Para clonar o repositório em sua máquina local, utilize o seguinte comando:

   ```bash
   git clone https://github.com/avrilstihler/Pagina-Simples-em-HTML.git
   ````
2. **Abrir o Projeto no Navegador**: Após clonar o repositório, abra o arquivo index.html em seu navegador. A partir dessa página, você pode explorar os animes clicando nos emojis.

## Interatividade:
   - Ao clicar em qualquer emoji, você será redirecionado para a página específica daquele anime.
   - Cada página de anime contém uma descrição, uma imagem e um link para assistir à abertura no YouTube.
   - Use o link "Voltar para a Página Inicial" para retornar à página principal.

## Tecnologias Usadas
 - HTML5: Toda a estrutura foi criada utilizando apenas HTML, sem uso de CSS externo ou JavaScript.
 - Estilos em HTML: Os estilos (como tamanho de fonte, cor, bordas arredondadas nas imagens e efeitos de hover nos links) foram definidos diretamente dentro das tags <style> no próprio arquivo HTML.
 - Imagens: As imagens dos animes estão localizadas na pasta images/ e são usadas para complementar as descrições e tornar a experiência mais visual e interativa.

## Como Personalizar
Para adicionar mais animes, basta criar uma nova página HTML, seguindo a mesma estrutura das páginas já existentes, e adicionar o emoji correspondente na página index.html.
   - As imagens dos animes devem ser colocadas na pasta images/ e nomeadas de acordo com o anime.


Exemplo de como adicionar um novo anime:

````html
<h1>Nome do Anime 🏴‍☠️</h1>
<img src="images/nomedoanime.jpg" alt="Nome do Anime" style="width: 80%; max-width: 400px; border-radius: 15px; margin-bottom: 20px;">
<p>Descrição do anime. 🌟</p>
<a href="https://www.youtube.com/watch?v=linkdovideo" target="_blank">📺 Nome do Anime Opening</a>
````
## Considerações Finais
Este projeto é um exemplo simples de como é possível criar uma página interativa utilizando apenas HTML e estilos internos, sem a necessidade de CSS externo. A ideia é apresentar uma maneira divertida de explorar animes através de emojis, com uma navegação simples e intuitiva. A estrutura do projeto é fácil de entender e pode ser expandida facilmente, caso você queira adicionar mais animes ou personalizar o conteúdo.


A navegação entre as páginas é intuitiva e não requer recursos complexos. O uso de estilos diretamente no HTML torna o projeto mais acessível e fácil de entender, sem a necessidade de aprender ou configurar ferramentas adicionais.


