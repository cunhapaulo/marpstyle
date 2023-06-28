# MARP Themes - `marpstyle` ![](https://camo.githubusercontent.com/83d3746e5881c1867665223424263d8e604df233d0a11aae0813e0414d433943/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6c6963656e73652d4d49542d626c75652e737667)

Marp themes repository, created with beauty and simplicity as first concerns.<br>
This set of styles (themes) were designed mainly concerning simplicity and beauty as first class prerequisites. Back in 2021, as the first theme `plato.css` got ready, I decided to share it here at Github. <br> I do sincerely hope you enjoy it and that it comes to be useful to as many users as it has been to me. <br> <br> More styles are due to come in a timely fashion. <br> Stay tuned for more `Marpstyle Themes`! 



## Last update: 26.jun.2023 - What´s new? 

🆕 **Just arrived**! The **Kurt Gödel**, **Alan Turing** and **Martin Luther King** themes have just arrives! Enjoy!


## One Example of Marp slide creation with style!
This slide deck was created to be used in a presentarion about Artifical INeligênce. It show some of the capabilities of MARP as well my CSS styles. I hope you like it.

[![](https://cunhapaulo.github.io/ai/main.png)](https://cunhapaulo.github.io/ai/)
[Link for the presentation](https://cunhapaulo.github.io/ai/)

## What is Marp?

- As you will find better explained in [Marp´s site at Github](https://github.com/marp-team/marp), Marpit /mɑːrpɪt/ is the skinny framework for creating slide deck from Markdown,  created by [Yuki Hattori](https://github.com/yhatt), to whom I am very thankful.

- All the themes here presented are destinated to be used with the [Marpit: Markdown slide deck framework](https://marpit.marp.app/markdown). In order to install Marp in your VS Code, take a look at [Marp for VS Code](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode).

## Available Themes

 Here you´ll find examples of the available themes. Click on the picture to open a corresponding PDF example.

### ![](img/marpstyle-ready.svg) In honor of Σωκράτης - Socrates (469–399 B.C.E.)
  [![](img/socrates.png)](examples/example-socrates.pdf)

### ![](img/marpstyle-ready.svg)  In honor of Πλάτων - Platon (429?–347 B.C.E.)
  [![Style: Plato](img/plato.png)](examples/example-plato.pdf)

### ![](img/marpstyle-ready.svg)  In honor of René Descartes (1596–1650) 
  [![Style: Leibniz](img/descartes.png)](examples/example-descartes.pdf)

### ![](img/marpstyle-ready.svg)  In honor of Leibniz (1646–1716) 
  [![Style: Leibniz](img/leibniz.png)](examples/example-leibniz.pdf)

### ![](img/marpstyle-ready.svg) In honor of Immanuel Kant (1724–1804)
  [![Style: Kant](img/kant.png)](examples/example-kant.pdf)

### ![](img/marpstyle-ready.svg)  In honor of Hegel (1770–1831)
  [![Style: Hegel](img/hegel.png)](examples/example-hegel.pdf)

### ![](img/marpstyle-ready.svg) In honor of Sigmund Freud (1856-1939)
  [![Style: Freud](img/freud.png)](examples/example-freud.pdf)

### ![](img/marpstyle-ready.svg)  In honor of Edmund Husserl (1859–1938) 
  [![Style: Husserl](img/husserl.png)](examples/example-husserl.pdf)

### ![](img/marpstyle-ready.svg) In honor of Martin Heidegger (1889–1976) 
  [![Style: Heidegger](img/heidegger.png)](examples/example-heidegger.pdf)

### ![](img/marpstyle-brand-new.svg) In honor of Kurt Gödel (1906-1978) 
[![Style: Gödel](img/godel.png)](examples/example-godel.pdf)

### ![](img/marpstyle-brand-new.svg) In honor of Alan Turing (1912-1954) 
  
  [![Style: Gödel](img/turing.png)](examples/example-turing.pdf)

###  ![](img/marpstyle-brand-new.svg) In honor of Martin Luther King (1929-1968)
  [![Style: Gödel](img/king.png)](examples/example-king.pdf)

### ![](img/marpstyle-ready.svg) In honor of Steven Jobs (1955–2011) 
  [![Style: Freud](img/jobs.png)](examples/example-jobs.pdf)

<br>

# What´s necessary to install?

Course you need `Marp` installed and operational. I created the available styles having the VSCode environment in mind, and only it. But it doesn´t mean they don´t work well with other environments, I only did not test it at all.

1. My suggestion is that you create a separate folder for each presentation you intend to create. Inside this presentarion folder I do also recomend you to create another folder, which might be called `/style`, specifically destinated for the `CSS` style files you intend do use in your presentation.

2. A prerequisite for using some extra fonts is that you have them installed on your computer. That said, some of the `styles` available here require special fonts not available by default in most OS installations. I intend to make some modifications so that these fonts are automatically downloaded from internet, but until this modification ins implemented, you will find below a section containing informations about the special fonts use in some of my styles and a possible locations where from you can download them (for free).

3. If you use `MARP` for VSCode, remember to include the path to the theme files (`CSS` files) in your `workspace.code-workspace` in order to make them available to your slide deck.

## It might look similar to:

<br>

```json
{
	"folders": [
		{
			"path": "."
		}
	],
	"settings": {
		"markdown.marp.themes": [
			"./style/socrates.css"
			"./style/plato.css"
			"./style/descartes.css"
			"./style/leibniz.css"
			"./style/kant.css"
			"./style/hegel.css"
			"./style/freud.css"
			"./style/husserl.css"
			"./style/godel.css"
			"./style/heidegger.css"
			"./style/turing.css"
			"./style/king.css"
			"./style/jobs.css"
			"./style/schema.css"
			"./style/structure.css"
		]
	}
}
```

## Styles directly from the internet
You might as well use my themes directly from github using the url, just like depicted below:

```json
{
	"folders": [
		{
			"path": "."
		}
	],
	"settings": {
		"markdown.marp.themes": [
			"https://cunhapaulo.github.io/style/descartes.css"
			"https://cunhapaulo.github.io/style/freud.css"
			"https://cunhapaulo.github.io/style/godel.css"
			"https://cunhapaulo.github.io/style/hegel.css"
			"https://cunhapaulo.github.io/style/heidegger.css"
			"https://cunhapaulo.github.io/style/husserl.css"
			"https://cunhapaulo.github.io/style/jobs.css"
			"https://cunhapaulo.github.io/style/kant.css"
			"https://cunhapaulo.github.io/style/king.css"
			"https://cunhapaulo.github.io/style/leibniz.css"
			"https://cunhapaulo.github.io/style/orwell.css"
			"https://cunhapaulo.github.io/style/plato.css"
			"https://cunhapaulo.github.io/style/schema.css"
			"https://cunhapaulo.github.io/style/simple.css"
			"https://cunhapaulo.github.io/style/socrates.css"
			"https://cunhapaulo.github.io/style/turing.css"
			"https://cunhapaulo.github.io/style/structure.css"
		]
	}
}
```

<br>

# Typefaces (TTF Fonts)

Some of the fonts necessary to the available styles are listed below with its respective link for download:

- ## Socrates Theme:
  
  - Noto Sans: https://fonts.google.com/noto/specimen/Noto+Sans

- ## Plato Theme:
  
  - Fira Sans Light: https://fonts.google.com/specimen/Fira+Sans?query=fira
  - Fira Sans Light: https://github.com/bBoxType/FiraSans

- ## Leibniz Theme:
  
  - Georgia or Serif: 

- ## Husserl Theme:

  <!-- - Montserrat: https://fonts.google.com/specimen/Montserrat?query=Mont -->
  - Lora: https://fonts.google.com/specimen/Lora?query=Lora
  - Fira Sans Light: https://fonts.google.com/specimen/Fira+Sans?query=fira

- ## General
  
  - Metropolis: https://github.com/njugunagathere/Metropolis
  - Open Sans: https://fonts.google.com/specimen/Open+Sans?query=Open+Sans

## Observation about fonts:
> Recently I decided to make use of downloading fonts from internet instead of forcing the user to install TTF fonts in their systems. Should it break in the future, due to the stop of the site proving the sources, be advised to resort to the old method instead.


# Credits

- **Plato** theme was inspired by [Metropolis Beamer Theme](https://github.com/matze/mtheme) for LaTeX by [Mathias Vogelgesang](https://github.com/matze/mtheme). Vielen Dank!!
- Used some parts of [Juan Vera del Campo](https://github.com/Juanvvc) CSS styles. Gracias!
