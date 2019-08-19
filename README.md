# CSS GRID

# GRID

- Bidimensional
- Divisão de toda a página em linhas e colunas
- Colocar elementos onde quiser nessa divisão

---

## GRID OU FLEXBOX

- Grid: Duas dimensões (colunas e linhas)
- Flexbox: Uma dimensão (ou coluna ou linha)
- Um complementa o trabalho do outro
- Verificar quais navegadores ainda não aceitam o Grid

## PROPRIEDADES

Vamos separara em 2 grupos:
`container` e `item(s)`

### CONTAINER

- display: grid;
- grid-template-columns;
- grid-template-rows;
- grid-gap
    - grid-row-gap;
    - grid-column-gap;
- grid-template-areas;

... e mais 4 propriedades e de **alinhamentos**

### ITEM(S)

- grid-column
    - grid-column-star;
    - grid-column-end;
- grid-row;
    - grid-row-start;
    - grid-row-end;
- grid-area;

... e mais 2 propriendades e de **alinhamento**

## GRID: ALINHAMENTO
---

Existem 6 propriedades para alinhamento:
1. `justify-content`
2. `align-content`
3. `justify-itens`
4. `align-itens`
5. `justify-self`
6. `align-self`

Vamos separá-los em 2 grupos:
1. `justify` e `align`
2. `content`, `items` e `self`

---

### JUSTIFY E ALIGN

Sabendo que o grid é bidimensional, nós temos o eixo x e o y.

O **eixo x** é o posicionalmento horizontal, da esquerda para a direita.

O **eixo y** é o posicionamento vertical, de cima para baixo.

---

### CONTENT, ITENS E SELF

Juntando o `justify`, ou `align`, com esses elementos: `content`, `items` e `self`; nós observamos nossas propriedades.

