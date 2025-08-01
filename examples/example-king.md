---
title       : Example Slides for Theme King
author      : Paulo Cunha
description : This is an example of how to use my themes
keywords    : Marp, Slides, Themes, Marpstyle
marp        : true
paginate    : true
theme       : king

--- 
   
<style>   

   .cite-author {     
      text-align        : right; 
   }
   .cite-author:after {
      color             : orangered;
      font-size         : 145%;
      /* font-style        : italic; */
      font-weight       : bold;
      font-family: 'Fira Sans Condensed', sans-serif; 
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

<!-- ![bg left:33%](https://controversia.com.br/wp-content/uploads/2017/04/martin-luther-king.jpg) -->
<!-- ![bg left:33%](https://img.cancaonova.com/cnimages/canais/uploads/sites/11/2023/01/Martin_Luther_King_Freepik.jpg) -->
<!-- ![bg left:33%](https://media1.ledevoir.com/images_galerie/nwdp_433257_294533/image.jpg) -->
<!-- ![bg left:33%](https://static.todamateria.com.br/upload/ma/rt/martinlutherking-cke.jpg) -->
<!-- ![bg left:33%](https://fotografias.larazon.es/clipping/cmsimages01/2021/01/18/2CE8ABC5-1666-45AA-9EC4-FFA38926E12A/98.jpg?crop=1818,1023,x0,y209&width=1900&height=1069&optimize=low&format=webply) -->
![bg left:33% brightness:0.9](https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Martin_Luther_King%2C_Jr..jpg/800px-Martin_Luther_King%2C_Jr..jpg)

<div class="title"         > I Have a Dream Today                                  </div>
<div class="subtitle"      > On the moral obligation of equal rights for all citizens</div>
<div class="author"        > Martin Luther King Jr.                                </div>
<div class="date"          > Washington, D.C., August 28, 1963                     </div>
<div class="organization"  > The March on Washington for Jobs and Freedom          </div>


---

<!-- _class: titlepage -->

#     I Have a Dream Today
##    On the moral obligation of equal rights for all citizens
###   Martin Luther King Jr. 
####  Washington, D.C., August 28, 1963
##### The March on Washington for Jobs and Freedom

---

<!-- _backgroundColor: #000000
 -->

![bg left h:80% drop-shadow:4px,5px,35px,#81A1C1](../img/king.jpg)

[Dr. Martin Luther King, JR. (1963). TEXT OF SPEECH DELIVERED IN THE MARCH ON WASHINGTON. August 28, 1963. <br> ![h:120](https://www.sethkaller.com/slideshow.php?id=2248&t=t-2248-001-26366_MLK_p1_w.jpg&1687796302548)](https://www.sethkaller.com/slideshow.php?id=2248&t=t-2248-001-26366_MLK_p1_w.jpg&1687796302548)


---
             
# Lists

<div class="columns">
<div>
      
<!-- _class: cool-list -->


1. *New York*
2. *Los Angeles*
3. *Chicago*
3. *Houston*
4. *Phoenix*
   
</div>  
<div>    
        
4. *Philadelphia* 
5. *San Antonio*
6. *San Diego*
7. *Dallas* 
8. *San Jose* 
 
</div>    
</div>        
            
---        
     
# Is Algebraic Graph Knowledge **Possible**?
 
Research has been conducted in order to evaluate the possibility of reaching meaningful knowledge from Algebraic Graph transformations.   
     
- Model Cheking and theorem prooving are viable paths. 

When the neet to  make strong assertions becomes inevitable:
- This is the first way: **outstanding assertion**!   
- Even greater impact comes from: _hilight text_!  
   
> ***Note**: This is a very long footnote line intended to test the layout of two. 
> 
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
<b>Formulae</b>: Exemples of use of LaTeX formulas.
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

* Published in 1807, marked a significant development in German idealism after Kant.

* In this book Hegel develops his concepts of dialectic.

[Price at Amazon](https://www.amazon.com/gp/product/0198245971/ref=ox_sc_act_image_2?smid=A1ZZFT5FULY4LN&psc=1): $ 17.83

</div>
</div>
     
--- 
 
<!-- _class: cite -->        

"There is an **increasing** demand of current information systems to incorporate the use of a higher degree of formalism in the development process. **Formal Methods** consist of a set of tools and techniques based on mathematical model and formal logic that are used to **specify and verify** requirements and designs for hardware and software systems."

--- 
  
<!-- _class: cite2 -->
 
<div class="cite-author" data-text="Mona Batra">

   "There is an **increasing** demand of current information systems to incorporate the use of a higher degree of formalism in the development process. **Formal Methods** consist of a set of tools and techniques based on mathematical model and formal logic that are used to **specify and verify** requirements and designs for hardware and software systems."

</div>
     
---
<!-- _class: transition -->  

 Transition Slide 1<br> _Aditional_ **Text**
    
---         
<!-- _class: transition2 -->  

 Transition Slide 2<br> _Aditional_ **Text**
    
---         

<!-- _class: biblio -->  

![bg left:33% opacity:20% blur:8px](https://images.unsplash.com/photo-1524995997946-a1c2e315a42f?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80)
 
# References       

1. PLATO. **Plato Republic**. Tradução: C. D. C. Reeve. Indianapolis, IN, USA: Hackett Publishing Company, 2004. 

1. PLATO. **Plato Republic**. Tradução: C. D. C. Reeve. Indianapolis, IN, USA: Hackett Publishing Company, 2004. 
2. ARISTOTELES. **Nikomachische Ethik**. Berlin: Akademie Verlag, 2010. (Klassiker Auslegen).v. 2
3. KANT, Immanuel. **Kritik der Praktischen Vernunft**. Berlin: Akademie Verlag, 2002. (Klassiker Auslegen).v. 26 
4. HEGEL, Georg Friederich Wilhelm. **Hegel´s Phenomenology of Spirit**. Tradução: A. V. Miller. New York: Oxford University Press, 2004.

--- 

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
 
