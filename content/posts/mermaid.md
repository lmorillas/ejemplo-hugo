+++
title = 'Gráficos con Mermaid'
date = 2023-09-24T16:51:30Z
draft = false  
+++
## Ejemplo de gráficos usando Mermaid en Markdown

### Diagramas GoAT

```goat
      .               .                .               .--- 1          .-- 1     / 1
     / \              |                |           .---+            .-+         +
    /   \         .---+---.         .--+--.        |   '--- 2      |   '-- 2   / \ 2
   +     +        |       |        |       |    ---+            ---+          +
  / \   / \     .-+-.   .-+-.     .+.     .+.      |   .--- 3      |   .-- 3   \ / 3
 /   \ /   \    |   |   |   |    |   |   |   |     '---+            '-+         +
 1   2 3   4    1   2   3   4    1   2   3   4         '--- 4          '-- 4     \ 4

```

```mermaid
flowchart LR
    A o--o B
    B <--> C
    C x--x D
```

