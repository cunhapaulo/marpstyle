# `Marpstyle`: styles for the Marp package

`Marpstyle` was created with beauty and simplicity as its main concerns, while taking functionality into account. Back in 2021, when the first plato.css theme was ready, I decided to share it freely here on Github.
I sincerely hope you make good use of it and that it comes to be as useful to you as it has been to me. 

## What is Marp?

- As you will find better explained in [Marp´s site at Github](https://github.com/Marp-team/Marp), Marpit /mɑːrpɪt/ is the skinny framework for creating slide deck from Markdown,  created by [Yuki Hattori](https://github.com/yhatt), to whom I am very thankful.

- All the themes here presented are destinated to be used with the [Marpit: Markdown slide deck framework](https://Marpit.Marp.app/markdown). In order to install Marp in your VS Code, take a look at [Marp for VS Code](https://marketplace.visualstudio.com/items?itemName=Marp-team.Marp-vscode).

> Please, REMEMBER! <br>
>  If you find my styles and Marp's ecosystem useful, we kindly ask you to include the credits in your presentations!

## **New Feature**: List Items Highlight (18.03.2024) 

I´ve just implemented the highlighting of list elements in all styles when you move the mouse pointer over them. 

![alt text](image.png)

> Please note that this function, like many others, only works if you export your presentation in HTML mode.

If you don't like the highlight feature or the default color used, you can disable it or change the color of the highlight bar as follows:

### To disable list item highlight:


Insert the following code at the beginning of your presentation code:

```html
<style>
	li:hover {
		background-color: inherit;
	}
</style>

```

### To change the highlighting color:

Insert the following code at the begining of your presentation code:

```html
<style>
	li:hover {
  		background-color: rgb(46, 253, 6); 
	}
</style>
```


##  Good Examples of Slidedecks in Marpstyle

Here I've selected some presentations built with Marp using my styles (`Marpstyle`).

### Example 1. A presentation on the philosopher Harry Frankfurt:



| [![](img/frankfurt.png)](https://cunhapaulo.github.io/frankfurt) |
| ---------------------------------------------------------------- |
Academic presentation on Harry Frankfurt - [Link for the presentation](https://cunhapaulo.github.io/frankfurt).


### Example 2. A presentation on Harry Frankfurt.

| [![](https://cunhapaulo.github.io/ai/main.png)](https://cunhapaulo.github.io/ai/) |
| --------------------------------------------------------------------------------- |
Academic presentation on philosophical aspects of Artificial Intelligence (AI) - [Link for the presentation](https://cunhapaulo.github.io/ai/) - [Source code used in this presentation](examples/presentation-ai/)


# Available Marpstyle Themes

 Here you´ll find examples of the available themes. Click on the picture to open a corresponding PDF example.

### ![](img/marpstyle-ready.svg) In honor of Σωκράτης - Socrates (469–399 B.C.E.)
  [![Style: Socrates](img/socrates.png)](examples/example-socrates.pdf)

### ![](img/marpstyle-ready.svg)  In honor of Πλάτων - Platon (429?–347 B.C.E.)
  [![Style: Plato](img/plato.png)](examples/example-plato.pdf)

### ![](img/marpstyle-ready.svg)  In honor of Niklas Koppernigk - Nicolaus Copernicus (1473–1543)
  [![Style: Descartes](img/copernicus.png)](examples/example-copernicus.pdf)

### ![](img/marpstyle-ready.svg)  In honor of René Descartes (1596–1650) 
  [![Style: Descartes](img/descartes.png)](examples/example-descartes.pdf)

### ![](img/marpstyle-ready.svg)  In honor of Leibniz (1646–1716) 
  [![Style: Leibniz](img/leibniz.png)](examples/example-leibniz.pdf)

### ![](img/marpstyle-updated.svg)  In honor of Immanuel Kant (1724–1804)
  [![Style: Kant](img/kant.png)](examples/example-kant.pdf)

### ![](img/marpstyle-ready.svg)  In honor of Hegel (1770–1831)
  [![Style: Hegel](img/hegel.png)](examples/example-hegel.pdf)

### ![](img/marpstyle-ready.svg) In honor of Sigmund Freud (1856-1939)
  [![Style: Freud](img/freud.png)](examples/example-freud.pdf)

### ![](img/marpstyle-ready.svg)  In honor of Edmund Husserl (1859–1938) 
  [![Style: Husserl](img/husserl.png)](examples/example-husserl.pdf)

### ![](img/marpstyle-ready.svg) In honor of Max Weber (1864–1920) 
  [![Style: Weber](img/weber.png)](examples/example-weber.pdf)

### ![](img/marpstyle-ready.svg)  In honor of Albert Einstein (1879–1955) 
  [![Style: Einstein](img/einstein.png)](examples/example-einstein.pdf)

### ![](img/marpstyle-ready.svg) In honor of Martin Heidegger (1889–1976) 
  [![Style: Heidegger](img/heidegger.png)](examples/example-heidegger.pdf)

### ![](img/marpstyle-brand-new.svg) In honor of George Orwell (1903-1950) 
[![Style: Orwell](img/orwell.png)](examples/example-orwell.pdf)

### ![](img/marpstyle-ready.svg) In honor of Kurt Gödel (1906-1978) 
[![Style: Gödel](img/godel.png)](examples/example-godel.pdf)

### ![](img/marpstyle-updated.svg) In honor of Hannah Arendt (1906-1975) 
[![Style: Arendt](img/arendt.png)](examples/example-arendt.pdf)

### ![](img/marpstyle-ready.svg) In honor of Alan Turing (1912-1954) 
[![Style: Turing](img/turing.png)](examples/example-turing.pdf)

###  ![](img/marpstyle-updated.svg) In honor of Martin Luther King (1929-1968)
  [![Style: King](img/king.png)](examples/example-king.pdf)

### ![](img/marpstyle-updated.svg) In honor of Steven Jobs (1955–2011) 
  [![Style: Jobs](img/jobs.png)](examples/example-jobs.pdf)

<br>

# What´s necessary to install?

0. First of all, you must have [`Marp`](https://Marpit.Marp.app/markdown) installed and operational on your system. I created these styles with the VSCode environment in mind, and only it, but that doesn't mean they won't work well in other environments, only that I haven't tested them yet.

1. My suggestion is that you create a separate folder for each intended presentation of yours. Inside this folder I do also recomend you to create another folder, which might be called `/style`, specifically destinated for the `CSS` style files you intend do use in your presentation.

2. If you use `Marp` for VSCode, remember to include the path to the theme files (`CSS` files) in your `workspace.code-workspace` in order to make them available to your slide deck.

3. A prerequisite for using some extra fonts is that you have them installed on your computer. That said, some of the `styles` available here require special fonts not available by default in most OS installations. I intend to make some modifications so that these fonts are automatically downloaded from internet, but until this modification ins implemented, you will find below a section containing informations about the special fonts use in some of my styles and a possible locations where from you can download them (for free).



	It might look similar to this:

<br>

```json
{
	"folders": [
		{
			"path": "."
		}
	],
	"settings": {
		"markdown.Marp.themes": [
			"./style/arendt.css",
			"./style/descartes.css",
			"./style/einstein.css",
			"./style/freud.css",
			"./style/godel.css",
			"./style/hegel.css",
			"./style/heidegger.css",
			"./style/hume.css",
			"./style/husserl.css",
			"./style/jobs.css",
			"./style/kant.css",
			"./style/king.css",
			"./style/leibniz.css",
			"./style/orwell.css",
			"./style/pascal.css",
			"./style/plato.css",
			"./style/schema.css",
			"./style/simple.css",
			"./style/socrates.css",
			"./style/structure.css",
			"./style/turing.css",
			"./style/weber.css",
		]
	}
}
```
Example of `workspace.code-workspace` content.

## Styles downloaded directly from the internet
You might as well use my themes directly from github using the url below:

```json
{
	"folders": [
		{
			"path": "."
		}
	],
	"settings": {
		"markdown.Marp.themes": [
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
			"https://cunhapaulo.github.io/style/orwell.css",
			"https://cunhapaulo.github.io/style/pascal.css",
			"https://cunhapaulo.github.io/style/plato.css",
			"https://cunhapaulo.github.io/style/schema.css",
			"https://cunhapaulo.github.io/style/simple.css",
			"https://cunhapaulo.github.io/style/socrates.css",
			"https://cunhapaulo.github.io/style/structure.css",
			"https://cunhapaulo.github.io/style/turing.css",
			"https://cunhapaulo.github.io/style/weber.css",	
				
		]
	}
}
```
Example of `workspace.code-workspace` content.

<br>

## Typefaces (TTF Fonts)

In the first editions of Marpstyle, it was necessary to download and install some of the fonts used. Now this is no longer necessary, as they are automatically downloaded from a website. Even so, I've kept here the reference and the sites from which these fonts can be downloaded and installed locally. See below:

- ### Socrates Theme:
  
  - Noto Sans: https://fonts.google.com/noto/specimen/Noto+Sans

- ### Plato Theme:
  
  - Fira Sans Light: https://fonts.google.com/specimen/Fira+Sans?query=fira
  - Fira Sans Light: https://github.com/bBoxType/FiraSans

- ### Leibniz Theme:
  
  - Georgia or Serif: 

- ### Husserl Theme:

  <!-- - Montserrat: https://fonts.google.com/specimen/Montserrat?query=Mont -->
  - Lora: https://fonts.google.com/specimen/Lora?query=Lora
  - Fira Sans Light: https://fonts.google.com/specimen/Fira+Sans?query=fira
 
- ### Orwell Theme:

  - Bookerly [https://online-fonts.com/fonts/bookerly](https://online-fonts.com/fonts/bookerly)

- ### General
  
  - Metropolis: https://github.com/njugunagathere/Metropolis
  - Open Sans: https://fonts.google.com/specimen/Open+Sans?query=Open+Sans

## Observation about fonts:
Recently I decided to make use of downloading fonts from internet instead of forcing the user to install TTF fonts in their systems. Should it break in the future, due to the stop of the site proving the sources, be advised to resort to the old method instead.


## Credits

- **Plato** theme was inspired by [Metropolis Beamer Theme](https://github.com/matze/mtheme) for LaTeX by [Mathias Vogelgesang](https://github.com/matze/mtheme). Vielen Dank!!
- Used some parts of [Juan Vera del Campo](https://github.com/Juanvvc) CSS styles. Gracias!
- Special thanks go to the creators of [CDN Fonts](https://www.cdnfonts.com/) website, wherefrom those fantastic fonts are downloaded!
