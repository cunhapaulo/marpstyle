---
title       : Slide de Teste dos Styles
author      : Paulo Cunha
description : Slides para teste dos Styles disponíveis.
keywords    : Marp, Slides, Teste.
marp        : true
paginate    : true
theme       : plato
---


<style>

   .cite-author {
      text-align        : right;
   }
   .cite-author:after {
      color             : orangered;
      font-size         : 125%;
      /* font-style        : italic; */
      font-weight       : bold;
      font-family       : Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
      padding-right     : 130px;
   }
   .cite-author[data-text]:after {
      content           : " - "attr(data-text) " - ";      
   }

   .cite-author p {
      padding-bottom : 40px
   }

</style>



<!-- _class: titlepage -->

![bg left:33%](https://images.unsplash.com/photo-1436891620584-47fd0e565afb?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=687&q=80)

<div class="title">Graph Algebra Formally Defined in Z Notation</div>
<div class="subtitle">Using Haskell to Reason about Programs </div>
<div class="author">Leonard Kleinrock</div>
<div class="date">01.jan.2022</div>
<div class="organization">Formal Methods International Congress</div>

---

<!-- _class: titlepage -->

![bg left:33%](https://images.unsplash.com/photo-1502675135487-e971002a6adb?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=688&q=80)

# Graph Algebra Formally Defined in Z Notation
## Using Haskell to Reason about Programs
### Leonard Kleinrock
#### 01.jan.2022
##### Formal Methods International Congress

---

# Lists

<div class="columns">
<div>

<!-- _class: cool-list -->

1. *Uno*
1. *Dos*
1. *Cinco*

</div>
<div>

4. *Uno*
1. *Dos*
1. *Cinco*

</div>
</div>

---

# Is Algebraic Graph Knowledge possible?

O Espiritismo é uma ciência que trata da natureza, origem e destino dos Espíritos, bem como de suas relações com o mundo corporal. 

- Existe apenas uma Doutrina Espírita com tríplice aspecto!

Texto realçado ficará assim:
- Realce tipo 1 é assim: **texto realçado**!
- Realce tipo 2 é assim: _texto realçado_!
- Texto sem realce algum.


> **Footenote**: This is a footnote.
---

<div class="columns">
<div>

# H1
## H2 
### H3
#### H4
##### H5
###### H6
</div>
<div>

- This is a fragment o normal text written here in order to exemplify the use of several featrues in CSS.

- This is a fragment o normal text written here in order to exemplify the use of several featrues in CSS.

  - This is one **feature**
  - This is another subjetc.

</div>
</div>

---

# Lists

<div class="columns">
<div>

1. One
2. Two in italic
3. Three is a bold number;
   1. abc
   2. def
4. End of list.
   
</div>
<div>

```haskell

primes = filterPrime [2..]
  where filterPrime (p:xs) =
          p : filterPrime [x | x <- xs, x `mod` p /= 0]

seqLength :: Num b ⇒ Sequence a → b
seqAppend :: Sequence a → Sequence a → Sequence a

seqLength Nil = 0
seqLength (Cons _ xs) = 1 + seqLength xs

seqAppend Nil ys = ys
seqAppend (Cons x xs) ys = Cons x (seqAppend xs ys)    
     
```

</div>
</div>

---

# Tables

| Column A | Column B | Column C | Column D |
| -------- | -------- | -------- | :------: |
| A1       | B1       | C1       |    D1    |
| A2       | B2       | C2       |    D2    |
| A3       | B3       | C3       |    D3    |

<center>
<b>Table</b>: Exemple of table use.
</center>

---

# LaTeX Equations

$$\frac{1}{c^2}\frac{\partial^2\mathbf{\psi}}{\partial t^2} = \nabla^2 \circ\mathbf{\psi}$$
$$\nabla \times \textbf{E}=- \frac{\partial \textbf{B}}{\partial t}$$
$$\nabla^2 \textbf{E} = \mu \epsilon \frac{\partial^2 \textbf{E}}{\partial t^2}$$
$$c=\sqrt{\frac{1}{\mu \epsilon}}$$

---

# Imagens in Two Columns

<div class="columns-center">
<div>

![h:450px](https://d1w7fb2mkkr3kw.cloudfront.net/assets/images/book/lrg/9780/4715/9780471555681.jpg)
   
</div>
<div>

![h:450px](https://m.media-amazon.com/images/P/B008BBM9B8.01._SCLZZZZZZZ_SX500_.jpg)

</div>
</div>

---

<!-- _class: cite -->

"O Espiritismo é uma ciência cujo fim é a **demonstração** experimental da **existência** da alma e sua imortalidade, por meio de comunicações com aqueles aos quais impropriamente têm sido chamados mortos."

---

<!-- _class: cite -->

<div class="cite-author" data-text="Allan Kardec">

   "O Espiritismo é uma ciência cujo fim é a **demonstração** experimental da **existência** da alma e sua imortalidade, por meio de comunicações com aqueles aos quais impropriamente têm sido chamados mortos."

</div>

---
<!-- _class: transition -->

# Slide de Transição

---

<!-- 
############################### [ SECTION ] #################################### 
-->

<!-- _class: biblio -->

![bg left:33% opacity:20% blur:8px](https://images.unsplash.com/photo-1524995997946-a1c2e315a42f?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80)

# Referências Bibliográficas

1. KARDEC, Allan. [O Evangelho segundo o Espiritismo](https://www.febnet.org.br/wp-content/uploads/2014/05/Livro-dos-Espiritos.pdf). Tradução: Guillon Ribeiro. 131. ed. 1. imp. Brasília: FEB, 2013. 

2. Imagens livres usadas dos sites [Unsplash](https://unsplash.com/) e [Picsum](https://picsum.photos/).

---
<!-- 
############################### [ SECTION ] #################################### 
-->

<!-- _class: biblio -->

![bg opacity:20% blur:8px](https://images.unsplash.com/photo-1524995997946-a1c2e315a42f?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80)

# Referências Bibliográficas

1. KARDEC, Allan. [O Evangelho segundo o Espiritismo](https://www.febnet.org.br/wp-content/uploads/2014/05/Livro-dos-Espiritos.pdf). Tradução: Guillon Ribeiro. 131. ed. 1. imp. Brasília: FEB, 2013. 

2. Imagens livres usadas dos sites [Unsplash](https://unsplash.com/) e [Picsum](https://picsum.photos/).


---

<div class="center">

Retornar: [Página Inicial](#1)

</div>