# MARP Themes - `marpstyle` ![](https://camo.githubusercontent.com/83d3746e5881c1867665223424263d8e604df233d0a11aae0813e0414d433943/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6c6963656e73652d4d49542d626c75652e737667)

Marp Themes was created with beauty and simplicity as its main concerns, while taking functionality into account. <br> 
This set of styles (themes) was designed primarily with simplicity and beauty as first-class prerequisites. Back in 2021, when the first plato.css theme was ready, I decided to share it here on Github. <br> 
I sincerely hope you like it and that it's as useful to as many users as it was to me. <br><br>

More styles will be released soon. <br> Stay tuned for more `Marpstyle Themes`! 



## Last update: 20.jul.2023 - What´s new? 

- 🆕 **Just arrived**! Enjoy!
  - **Hannah Arendt** 	
  - **Albert Einstein**, 
  - **Martin Luther King**, 
  - **Kurt Gödel**, and 
  - **Alan Turing**.  
- 🆕 Theme **JOBS** updated!!!


## One Example of Marp slide creation with style!
This slide deck was created for a presentarion about Artifical Inteligence (AI). It show some of the capabilities of MARP as well my CSS styles. I hope you like it.

[![](https://cunhapaulo.github.io/ai/main.png)](https://cunhapaulo.github.io/ai/)
- [Link for the presentation](https://cunhapaulo.github.io/ai/)
- [Source code used in this presentation](examples/presentation-ai/)

## What is Marp?

- As you will find better explained in [Marp´s site at Github](https://github.com/marp-team/marp), Marpit /mɑːrpɪt/ is the skinny framework for creating slide deck from Markdown,  created by [Yuki Hattori](https://github.com/yhatt), to whom I am very thankful.

- All the themes here presented are destinated to be used with the [Marpit: Markdown slide deck framework](https://marpit.marp.app/markdown). In order to install Marp in your VS Code, take a look at [Marp for VS Code](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode).

## Available Themes

 Here you´ll find examples of the available themes. Click on the picture to open a corresponding PDF example.

### ![](img/marpstyle-ready.svg) In honor of Σωκράτης - Socrates (469–399 B.C.E.)
  [![Style: Socrates](img/socrates.png)](examples/example-socrates.pdf)

### ![](img/marpstyle-ready.svg)  In honor of Πλάτων - Platon (429?–347 B.C.E.)
  [![Style: Plato](img/plato.png)](examples/example-plato.pdf)

### ![](img/marpstyle-ready.svg)  In honor of René Descartes (1596–1650) 
  [![Style: Descartes](img/descartes.png)](examples/example-descartes.pdf)

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

### ![](img/marpstyle-brand-new.svg)  In honor of Albert Einstein (1879–1955) 
  [![Style: Einstein](img/einstein.png)](examples/example-einstein.pdf)

### ![](img/marpstyle-ready.svg) In honor of Martin Heidegger (1889–1976) 
  [![Style: Heidegger](img/heidegger.png)](examples/example-heidegger.pdf)

### ![](img/marpstyle-brand-new.svg) In honor of Kurt Gödel (1906-1978) 
[![Style: Gödel](img/godel.png)](examples/example-godel.pdf)

### ![](img/marpstyle-brand-new.svg) In honor of Hannah Arendt (1906-1975) 
[![Style: Arendt](img/arendt.png)](examples/example-arendt.pdf)

### ![](img/marpstyle-brand-new.svg) In honor of Alan Turing (1912-1954) 
[![Style: Turing](img/turing.png)](examples/example-turing.pdf)

###  ![](img/marpstyle-brand-new.svg) In honor of Martin Luther King (1929-1968)
  [![Style: King](img/king.png)](examples/example-king.pdf)

### ![](img/marpstyle-updated.svg) In honor of Steven Jobs (1955–2011) 
  [![Style: Jobs](img/jobs.png)](examples/example-jobs.pdf)

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
			"./style/arendt.css",
			"./style/descartes.css",
			"./style/einstein.css",
			"./style/freud.css",
			"./style/godel.css",
			"./style/hegel.css",
			"./style/heidegger.css",
			"./style/husserl.css",
			"./style/jobs.css",
			"./style/kant.css",
			"./style/king.css",
			"./style/leibniz.css",
			"./style/plato.css",
			"./style/schema.css",
			"./style/socrates.css",
			"./style/structure.css",
			"./style/turing.css",
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
			"https://cunhapaulo.github.io/style/arendt.css",
			"https://cunhapaulo.github.io/style/descartes.css",
			"https://cunhapaulo.github.io/style/einstein.css",
			"https://cunhapaulo.github.io/style/freud.css",
			"https://cunhapaulo.github.io/style/godel.css",
			"https://cunhapaulo.github.io/style/hegel.css",
			"https://cunhapaulo.github.io/style/heidegger.css",
			"https://cunhapaulo.github.io/style/husserl.css",
			"https://cunhapaulo.github.io/style/jobs.css",
			"https://cunhapaulo.github.io/style/kant.css",
			"https://cunhapaulo.github.io/style/king.css",
			"https://cunhapaulo.github.io/style/leibniz.css",
			"https://cunhapaulo.github.io/style/plato.css",
			"https://cunhapaulo.github.io/style/schema.css",
			"https://cunhapaulo.github.io/style/socrates.css",
			"https://cunhapaulo.github.io/style/structure.css",
			"https://cunhapaulo.github.io/style/turing.css",
		]
	}
}
```

<br>

# Typefaces (TTF Fonts)

In the first editions of Marpstyle, it was necessary to download and install some of the fonts used. Now this is no longer necessary, as they are automatically downloaded from a website. Even so, I've kept here the reference and the sites from which these fonts can be downloaded and installed locally. See below:

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
- Special thanks go to the [CDN Fonts](https://www.cdnfonts.com/) website, wherefrom those fantastic fonts are downloaded!
