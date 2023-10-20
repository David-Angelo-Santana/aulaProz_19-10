# Estilos CSS

Neste repositório, você encontrará um arquivo CSS que define os estilos para uma página da web. Abaixo está uma descrição dos principais estilos aplicados:

## Estilos Gerais

- O seletor universal (*) define estilos que se aplicam a todos os elementos na página.
  - `font-family`: Define a fonte principal como 'Maven Pro' com uma fonte sans-serif genérica de backup.
  - `margin` e `padding`: Redefine as margens e preenchimentos padrão para zero.
  - `text-decoration`: Remove decorações de texto, como sublinhados.

- O estilo do corpo (body) define as configurações gerais para a página.
  - `background-color`: Define a cor de fundo como um tom de roxo (#68008d).
  - `color`: Define a cor do texto como branco (#fff).

## Estilos do Cabeçalho (header)

- O cabeçalho (header) é estilizado da seguinte forma:
  - `background-color`: Tem um fundo cinza claro.
  - `display`: Usa um layout flex para organizar elementos internos.
  - `justify-content`: Espalha uniformemente o conteúdo no cabeçalho.
  - `padding`: Adiciona espaço interno.
  - `margin-bottom`: Cria um espaço entre o cabeçalho e o próximo elemento.

## Estilos dos Cards

- Os cartões (cards) são usados para exibir informações.
  - `background-color`: Têm um fundo laranja (#EF7D19).
  - `width` e `height`: Têm uma largura de 350px e uma altura de 200px.
  - `border-radius`: Arredonda as bordas dos cartões.
  - `padding`: Adiciona espaço interno.
  - `display`: Usa um layout flex para organizar elementos internos em coluna.
  - `align-items` e `justify-content`: Alinham o conteúdo ao início dos cartões.
  - `box-shadow`: Adiciona um efeito de sombra.
  - `cursor`: Altera o cursor para uma mãozinha ao pairar sobre os cartões.
  - `transition`: Fornece uma transição suave quando os cartões são destacados.

- Quando um cartão é destacado (hover), ele é dimensionado ligeiramente e sua cor de fundo muda.

## Estilos dos Títulos

- Os títulos (h1 e h3) têm tamanhos de fonte específicos.

  - `h1`: Tamanho da fonte definido em 3rem.
  - `h3`: Tamanho da fonte definido em 1.5rem.

## Estilos das Listas

- As listas não ordenadas (ul) têm estilos específicos.
  - `display`: Usam um layout flex para alinhar verticalmente os itens da lista.

- Os itens de lista (li) têm um recuo à esquerda e removem os marcadores de lista.


