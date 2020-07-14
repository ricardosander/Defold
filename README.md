# Defold
Minhas anotações dos meus estudos sobre a game engine Defold.

# Conceitos Básicos

## Collection (Coleção)

Um arquivo Collection (Collection File) é um tipo de arquivo que contém Game Objects (Objetos Jogo) e outras coleções (Collections). É uma forma de organizar e agrupar esses outros componenetes. Uma Collection pode ser usada para cirar personagens jogáveis, chefões e até mesmo leveis inteiros.  A inicialização de um jogo se dá a partir de um arquivo Collection, definido no ```game.project```.

## Game Object (Objeto Jogo)

Objetos Jogo (Objetos Jogo) contém sprites (imagens para animação), sons, modelos 3D, tiles (imagens de mapas), ou scripts (comportamentos programados). Um Game Object tem tamanho, posição e rotação. Podemos escrever scripts que manipulem essas propriedades durante o tempo de execução do jogo. Exemplos de Game Object são uma bala, um objeto coletável e um level loader.

## Component (Componente)

Components são os elementos que são desenhados na tela, fazem som ou fazem as interaçes ocorreram. Components não existem por si só, eles são colocados do Game Objects. Alguns componentes tem propriedades que podem ser alteradas durante a execução do jogo e a maioria deles pode ser ligado e desligado. Existem diversos tipos de Components e cada tipo pode ter como fonte diferentes tipos de arquivo como imagens atlas, arquivos de áudio, arquivos de animação, etc.
