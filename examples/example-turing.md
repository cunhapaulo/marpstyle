---
title: Example Slides for Theme Alan Turing
author: Paulo Cunha
description: This is an example of how to use this theme.
keywords: Marp, Slides, Themes.
marp: true
paginate: true
theme: turing
---

<style>   

   .cite-author {     
      text-align        : right; 
   }
   .cite-author:after {
      color             : white;
      font-size         : 125%;
      font-style        : italic;
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
<!-- ![bg left:33%](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a1/Alan_Turing_Aged_16.jpg/200px-Alan_Turing_Aged_16.jpg) -->

![bg left:33% grayscale:1 brightness:1.1](https://www.thesun.co.uk/wp-content/uploads/2019/07/NINTCHDBPICT000491505127.jpg)

<!-- ![bg left:33% h:100%](https://www.macworld.com/wp-content/uploads/2021/10/steve-jobs-2-1.jpg?quality=50&strip=all) -->

<div class="title"         > Computing Machinery and Intelligence </div>
<div class="subtitle"      > Can machines think?                  </div>
<div class="author"        > Alan Mathison Turing                 </div>
<div class="date"          > Mind, , 1950               </div>
<div class="organization"  > Oxford University - Oxfordshire, UK.     </div>

---

<!-- _class: titlepage -->

# Computing Machinery and Intelligence

## Can machines think?

### Alan Mathison Turing

#### Mind, , 1950

##### Oxford University - Oxfordshire, UK.

---

![bg h:80% left drop-shadow:0,5px,10px,rgba(0,0,0,.4)](../img/turing01.jpg)

[A. M. Turing (1950) **Computing Machinery and Intelligence**. Mind 49: 433-460. <br> ![h:120](https://logowik.com/content/uploads/images/638_pdf_icon.jpg)](https://redirect.cs.umbc.edu/courses/471/papers/turing.pdf)

---

# Lists

<div class="columns">
<div>
      
<!-- _class: cool-list -->

1. _London_
2. _Manchester_
3. _Birmingham_
4. _Glasgow_
5. _Liverpool_

</div>  
<div>    
        
6. *Newcastle* 
7. *Sheffield*
8. *Nottingham*
9. *Southampton* 
10. *Edinburgh*

</div> 
</div>           
            
---        
     
# Is Algebraic Graph Knowledge **Possible**?
 
Research has been conducted in order to evaluate the possibility of reaching meaningful knowledge from Algebraic Graph transformations.   
     
- Model Cheking and theorem prooving are viable paths.

When the neet to make strong assertions becomes inevitable:

- This is the first way: **outstanding assertion**!
- Even greater impact comes from: _hilight text_!  


> **\*Note**: This is a very long footnote line intended to test the layout of two.

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

<figcaption align="center">
<b>Code</b>: Haskell code fragment.
</figcaption>

</div>
</div>
 
---

# Tables

| Column A | Column B | Column C | Column D |
| -------- | -------- | -------- | :------: |
| A1       | B1       | C1       |    D1    |
| A2       | B2       | C2       |    D2    |
| A3       | B3       | C3       |    D3    |

<figcaption align="center">
<b>Table</b>: Exemple of use of tables.
</figcaption>

---

# LaTeX Equations

$$\frac{1}{c^2}\frac{\partial^2\mathbf{\psi}}{\partial t^2} = \nabla^2 \circ\mathbf{\psi} $$
$$\nabla \times \textbf{E}=- \frac{\partial \textbf{B}}{\partial t}$$
$$\nabla^2 \textbf{E} = \mu \epsilon \frac{\partial^2 \textbf{E}}{\partial t^2}$$
$$c=\sqrt{\frac{1}{\mu \epsilon}}$$

<figcaption align="center">
<b>Formulae</b>: Exemples of LaTeX formulas use.
</figcaption>

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

# Images in Two Columns

<div class="columns-center" align="center">
<div>         
 
![h:450px](https://d1w7fb2mkkr3kw.cloudfront.net/assets/images/book/lrg/9780/4715/9780471555681.jpg)
<figcaption>
<b>Figure</b>: Kleinrock, Gail (1979).
</figcaption>
   
</div>
<div>

![h:450px](https://m.media-amazon.com/images/P/B008BBM9B8.01._SCLZZZZZZZ_SX500_.jpg)

<figcaption>
<b>Figure</b>: Springer Verlag (1979).
</figcaption>

</div>
</div>

---

# Image and text

<div class="columns">
<div>

<center>

![h:450](https://images-na.ssl-images-amazon.com/images/I/51sIPBiMS7L._SX325_BO1,204,203,200_.jpg)

<figcaption align="center">
<b>Figure</b>: Oxford edition (1979).
</figcaption>

</center>

</div>
<div>

## Hegel's Phenomenology

The book was originally entitled "Phänomenologie des Geistes" by its author, G.W.F. Hegel.

- Published in 1807, marked a significant development in German idealism after Kant.

- In this book Hegel develops his concepts of dialectic.

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

 Transition Slide <br> _Aditional_ **Text**
    
---         
<!-- _class: transition2 -->  

 Transition Slide <br> _Aditional_ **Text**
    
---    

<!--   
############################### [ SECTION ] #################################### 
-->

<!-- _class: biblio -->

![bg left:25% opacity:70% blur:1px](https://images.unsplash.com/photo-1524995997946-a1c2e315a42f?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80)

# References

1. PLATO. **Plato Republic**. Tradução: C. D. C. Reeve. Indianapolis, IN, USA: Hackett Publishing Company, 2004.

1. PLATO. **Plato Republic**. Tradução: C. D. C. Reeve. Indianapolis, IN, USA: Hackett Publishing Company, 2004.
1. ARISTOTELES. **Nikomachische Ethik**. Berlin: Akademie Verlag, 2010. (Klassiker Auslegen).v. 2
1. KANT, Immanuel. **Kritik der Praktischen Vernunft**. Berlin: Akademie Verlag, 2002. (Klassiker Auslegen).v. 26
1. HEGEL, Georg Friederich Wilhelm. **Hegel´s Phenomenology of Spirit**. Tradução: A. V. Miller. New York: Oxford University Press, 2004.

---

<!-- 
############################### [ SECTION ] #################################### 
-->

<!-- _class: biblio -->

# References

<div class="columns">
<div>

1. PLATO. **Plato Republic**. Tradução: C. D. C. Reeve. Indianapolis, IN, USA: Hackett Publishing Company, 2004.
2. ARISTOTELES. **Nikomachische Ethik**. Berlin: Akademie Verlag, 2010. (Klassiker Auslegen).v. 2
3. KANT, Immanuel. **Kritik der Praktischen Vernunft**. Berlin: Akademie Verlag, 2002. (Klassiker Auslegen).v. 26
4. HEGEL, Georg Friederich Wilhelm. **Hegel´s Phenomenology of Spirit**. Tradução: A. V. Miller. New York: Oxford University Press, 2004.

</div>
<div>

5. HUSSERL, Edmund. **The Crisis of European Sciences and Transcendental Phenomenology**. Evanston, USA: Northwestern University Press, 1970.
6. CASSIRER, Ernst. **The Myth of the State**. New Haven, USA: Yale University Press, 1946.
7. HEIDEGGER, Martin. **Sein und Zeit**. 11. ed. Tübingen: Max Niemeyer Verlag, 1967.
8. GADAMER, Hans-Georg. **Wahrheit und Methode**. Berlin: Akademie Verlag, 2007. v. 30.
</div>
