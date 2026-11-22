# PAC-MAN

Jogo desenvolvido em **C++** com a biblioteca **SDL2**.

**Desenvolvedor:** Agnaldo Alves Barreto\
**Ano:** 2026

------------------------------------------------------------------------

## Sobre o jogo

Este projeto é uma versão autoral de um jogo inspirado no clássico
Pac-Man. Foi desenvolvido em C++ utilizando a biblioteca SDL2, com foco
em programação de jogos, lógica, movimentação, colisões, renderização e
inteligência artificial.

O jogo possui labirintos, guloseimas para coletar, pílulas de energia e
fantasmas com comportamentos próprios.

## Tecnologias utilizadas

-   C++
-   SDL2
-   Visual Studio 2022

## Características

-   Jogo 2D inspirado no estilo clássico de Pac-Man.
-   Labirintos editáveis por arquivo de texto.
-   Coleta de guloseimas e pílulas de energia.
-   Fantasmas com inteligência artificial.
-   Algoritmo de busca em largura (BFS) para busca de caminhos.
-   Comportamentos de perseguição, fuga, patrulhamento e retorno à casa.
-   Detecção de colisões.
-   Animações e movimentação dos personagens.
-   Sistema de pontuação, vidas e níveis.
-   Controle de tempo e atualização do jogo.

## Como executar

1.  Baixe o pacote do jogo disponibilizado neste
    repositório.
2.  Extraia todos os arquivos do ZIP para uma pasta.
3.  Mantenha o executável, as bibliotecas necessárias e a pasta `dados`
    juntos, respeitando a estrutura distribuída.
4.  Execute `PacMan.exe`.

> O nome do executável pode variar conforme a versão publicada. Se o
> Windows informar que falta uma DLL, verifique se todos os arquivos do
> pacote foram extraídos e mantidos na mesma estrutura. Não baixe DLLs
> de sites desconhecidos.

## Edição e personalização dos labirintos

Uma característica do jogo é permitir a edição dos labirintos por meio
de um arquivo de texto.

Os mapas utilizados pelo jogo ficam no arquivo:

`dados/labirinto.txt`

É possível abrir esse arquivo em um editor de texto, como o Bloco de
Notas, e modificar o desenho dos cinco labirintos sem precisar alterar
ou recompilar o código-fonte.

Cada mapa deve manter a estrutura de **25 linhas por 21 colunas**.

### Legenda dos caracteres

-   `#` --- Parede
-   `_` --- Caminho vazio
-   `P` --- Pílula de energia
-   `0` a `9` --- Guloseimas
-   `CCC` --- Casa dos fantasmas
-   `J` --- Posição inicial do jogador

### Cuidados ao editar

-   Mantenha cada mapa com 25 linhas e 21 colunas.
-   Preserve os caracteres utilizados pelo jogo.
-   Cada labirinto precisa ter uma posição inicial válida para o jogador
    (`J`).
-   Cada labirinto precisa ter uma casa dos fantasmas válida (`CCC`).
-   Evite apagar ou acrescentar caracteres sem conferir o tamanho das
    linhas.
-   Os mapas são separados por linhas em branco no arquivo.

As alterações feitas em `labirinto.txt` são carregadas pelo jogo quando
ele inicia.
Se ocasionar algum erro na inicialização,
um arquivo Erro.txt será criado na pasta do executável
reportando o problema.

## Distribuição e direitos autorais

Este projeto é disponibilizado gratuitamente para fins pessoais e
educacionais.

É permitido baixar, executar e compartilhar o link da página oficial do
projeto, mantendo os créditos do autor.

**Não é permitido vender o jogo, cobrar pelo acesso, redistribuí-lo
comercialmente ou utilizá-lo em atividades com finalidade comercial sem
autorização prévia e por escrito do autor.**

O código-fonte não faz parte desta distribuição pública. A
disponibilização do executável não transfere a propriedade intelectual
do projeto.

O projeto pode utilizar bibliotecas, ferramentas ou outros recursos de
terceiros, que permanecem sujeitos às respectivas licenças e condições
de uso.

Para solicitar autorização de uso comercial ou esclarecer dúvidas sobre
a distribuição, entre em contato com o autor.

## Contato

**Agnaldo Alves Barreto**\
E-mail: agnaldo_alves_barreto@hotmail.com

------------------------------------------------------------------------

Obrigado por conhecer e experimentar o projeto!
