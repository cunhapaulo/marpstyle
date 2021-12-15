---
title       : Example Slides for Themes
author      : Paulo Cunha
description : This is an example of how to use my themes.
keywords    : Marp, Slides, Themes.
marp        : true
paginate    : true
theme       : socrates   
---

 
<style>
   
   .cite-author {
      text-align        : right;
   }
   .cite-author:after {  
      color             : red;
      font-size         : 120%;
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

![bg left:33%](https://images.unsplash.com/photo-1560914210-08431b749ff5?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1974&q=80)
<!-- _class: titlepage -->

<div class="title">Graph Algebra Representation of Formally Defined Programs in Z</div>
<div class="subtitle">Using Haskell to Reason and Verify Programs</div>
<div class="author">Leonard Kleinrock</div>
<div class="date">01.jan.2022</div>
<div class="organization">Formal Methods International Congress</div>

---

<!-- _class: titlepage -->

# Graph Algebra Representation of Formally Defined Programs in Z
## Using Haskell to Reason and  Verify Programs
### Leonard Kleinrock
#### 01.jan.2022
##### Formal Methods International Congress

---

# Lists

<div class="columns">
<div>

<!-- _class: cool-list -->

1. *Berlin*
2. *Hannover*
3. *Freiburg im Breisgau*
3. *Heidelberg*
4. *Hamburg*

</div>
<div> 

4. *Leipzig*
5. *Dresden*
6. *München*
7. *Köln*
8. *Köningsberg und Praga*

</div>
</div>   

--- 

# Is Algebraic Graph Knowledge Possible?

Research has been conducted in order to evaluate the possibility of reaching meaningful knowledge from Algebraic Graph transformations.

- Model Cheking and theorem prooving are viable paths.

When the neet to  make strong assertions becomes inevitable:
- This is the first way: **outstanding assertion**!   
- Even greater impact comes from: _hilight text_!

> \***Note**: This is a very long footnote line intended to test the layout of two lines.

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
2. Two 
3. Three
   1. abc
   2. def
4. End of list
   
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
<caption>
<b>Code</b>: Haskell code fragment.
</caption>

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
<caption><b>Table</b>: Exemple of use of tables.</caption>
</center>

---

# LaTeX Equations

$$\frac{1}{c^2}\frac{\partial^2\mathbf{\psi}}{\partial t^2} = \nabla^2 \circ\mathbf{\psi}$$
$$\nabla \times \textbf{E}=- \frac{\partial \textbf{B}}{\partial t}$$
$$\nabla^2 \textbf{E} = \mu \epsilon \frac{\partial^2 \textbf{E}}{\partial t^2}$$
$$c=\sqrt{\frac{1}{\mu \epsilon}}$$

---

# Images in Two Columns

<div class="columns-center">
<div>         
 
![h:450px](https://d1w7fb2mkkr3kw.cloudfront.net/assets/images/book/lrg/9780/4715/9780471555681.jpg)
   
</div>
<div>

![h:450px](https://m.media-amazon.com/images/P/B008BBM9B8.01._SCLZZZZZZZ_SX500_.jpg)

</div>
</div>

---

# Image and text

<div class="columns">
<div>

<center>

![](https://images-na.ssl-images-amazon.com/images/I/51sIPBiMS7L._SX325_BO1,204,203,200_.jpg)
<caption>
<b>Figure</b>: Oxford edition (1979).
</caption>

</center>

</div>
<div>

## Hegel's Phenomenology

The book was originally entitled "Phänomenologie des Geistes" by its author, G.W.F. Hegel.

* Published in 1807, marked a significant development in German idealism after Kant.

* In this book Hegel develops his concepts of dialectic.

[Price at Amazon](https://www.amazon.com/gp/product/0198245971/ref=ox_sc_act_image_2?smid=A1ZZFT5FULY4LN&psc=1): $ 17.83

</div>
</div>

--- 
 
<!-- _class: cite -->  

"There is an **increasing** demand of current information systems to incorporate the use of a higher degree of formalism in the development process. **Formal Methods** consist of a set of tools and techniques based on mathematical model and formal logic that are used to **specify and verify** requirements and designs for hardware and software systems."

---

<!-- _class: cite -->

<div class="cite-author" data-text="Mona Batra">

   "There is an **increasing** demand of current information systems to incorporate the use of a higher degree of formalism in the development process. **Formal Methods** consist of a set of tools and techniques based on mathematical model and formal logic that are used to **specify and verify** requirements and designs for hardware and software systems."

</div>
     
---
<!-- _class: transition -->

# Transition Slide
 
---

<!-- 
############################### [ SECTION ] #################################### 
-->

<!-- _class: biblio -->

![bg left:33% opacity:20% blur:8px](https://images.unsplash.com/photo-1524995997946-a1c2e315a42f?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80)

# References

1. Boehm B. W.: **Software  Engineering Economics**. Prentice Hall, 1981.

2. Pressman Roger S: **Software Engineering - A Practitioner’s Approach**, McGraw Hill, 5th edition. 2000.

3. Rushby John: **Formal Methods and the Certication of Critical Systems**. Tech. Rep. SRI-CSL-93-7, Computer Science Laboratory, SRI International, Menlo Park, CA, Dec. 1993.

4. Gallian, J. A. **Contemporary Abstract Algebra**. 9. ed. Boston, MA: Cengage Learning, 2017. 
---
<!-- 
############################### [ SECTION ] #################################### 
--> 
    
<!-- _class: biblio -->

![bg opacity:20% blur:8px](https://images.unsplash.com/photo-1524995997946-a1c2e315a42f?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80)

# References
<div class="columns">
<div>

1. Boehm B. W.: **Software Engineering Economics**. Prentice Hall, 1981.

2. Pressman Roger S: **Software Engineering - A Practitioner’s Approach**, McGraw Hill, 5th edition. 2000.

3. Rushby John: **Formal Methods and the Certication of Critical Systems**. Tech. Rep. SRI-CSL-93-7, Computer Science Laboratory, SRI International, Menlo Park, CA, Dec. 1993.

</div>
<div>

4. Gallian, J. A. **Contemporary Abstract Algebra**. 9. ed. Boston, MA: Cengage Learning, 2017. 


</div>
 
---

<center>

  Retornar: [Página Inicial](#1)

</center>
