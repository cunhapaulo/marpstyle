# MARP Themes - `marpstyle`

Repository for Marp themes, created with beauty and simplicity as first concerns.
Last update: 05.jun.2022

![](https://camo.githubusercontent.com/83d3746e5881c1867665223424263d8e604df233d0a11aae0813e0414d433943/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6c6963656e73652d4d49542d626c75652e737667)

| ![](img/plow_man.gif) | This set of styles (themes) were designed bearing mainly simplicity and beauty in mind as first class requirements. As the first theme (plato.css) got ready I decided to share. I hope sincerely you enjoy it and it comes to be useful to as many users as possible. More styles are due to come in a fashionable time. <br> <br> Stay tuned for more themes! |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |

# Available Themes

### Below are some examples of available themes. <br> Click on the picture to open a PFD example.

- ### THEME SOCRATES in honor of Σωκράτης (469–399 B.C.E.)
  [![](img/socrates.png)](examples/example-socrates.pdf)


- ### THEME PLATO in honor of Πλάτων (429?–347 B.C.E.)
  [![Style: Plato](img/plato.png)](examples/example-plato.pdf)


- ### THEME LEIBNIZ in honor of Gottfried Wilhelm Leibniz (1646–1716) 
  [![Style: Leibniz](img/leibniz.png)](examples/example-leibniz.pdf)

- ### THEME KANT in honor of Immanuel Kant (1724–1804)
  [![Style: Kant](img/kant.png)](examples/example-kant.pdf)

- ### THEME HEGEL in honor of Georg Wilhelm Friedrich Hegel (1770–1831)
  [![Style: Hegel](img/hegel.png)](examples/example-hegel.pdf)

- ### THEME FREUD in honor of Sigmund Freud (Sigismund Schlomo Freud) (1856-1939)
  [![Style: Freud](img/freud.png)](examples/example-freud.pdf)

- ### THEME HEIDEGGER in honor of Martin Heidegger (1889–1976) 
  [![Style: Freud](img/heidegger.png)](examples/example-heidegger.pdf)

- ### THEME JOBS in honor of Steven Paul Jobs (1955–2011) 
  [![Style: Freud](img/jobs.png)](examples/example-jobs.pdf)

<br>

# Install

As a prerequisite of MARP, remember to include the path to the theme files (CSS files) in your `workspace.code-workspace` in order to make them available to your slide deck.

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
            "./style/leibniz.css"
            "./style/kant.css"
            "./style/hegel.css"
            "./style/freud.css"
            "./style/heidegger.css"
            "./style/jobs.css"
            "./style/schema.css"
            "./style/structure.css"
        ]
    }
}
```

## You might as well use my themes directly from github using the url, just like depicted below:

```json
{
	"folders": [
		{
			"path": "."
		}
	],
	"settings": {
		"markdown.marp.themes": [
			"https://cunhapaulo.github.io/style/freud.css"
			"https://cunhapaulo.github.io/style/hegel.css"
			"https://cunhapaulo.github.io/style/heidegger.css"
			"https://cunhapaulo.github.io/style/kant.css"
			"https://cunhapaulo.github.io/style/leibniz.css"
			"https://cunhapaulo.github.io/style/plato.css"
			"https://cunhapaulo.github.io/style/schema.css"
			"https://cunhapaulo.github.io/style/simple.css"
			"https://cunhapaulo.github.io/style/socrates.css"
			"https://cunhapaulo.github.io/style/structure.css"
		]
	}
}
```

<br>

# Typefaces

Some of the fonts necessary to the available styles are listed below with its respective link for download:

- ## Socrates Theme:
  
  - Noto Sans (Google Fonts): https://fonts.google.com/noto/specimen/Noto+Sans

- ## Plato Theme:
  
  - Fira Sans Light (Google Fonts): https://fonts.google.com/specimen/Fira+Sans?query=fira
  - Fira Sans Light: https://github.com/bBoxType/FiraSans

- ## Leibniz Theme:
  
  - Georgia or Serif: 

- ## General
  
  - Metropolis: https://github.com/njugunagathere/Metropolis

# Credits

- **Plato** theme was inspired by [Metropolis Beamer Theme](https://github.com/matze/mtheme) for LaTeX by [Mathias Vogelgesang](https://github.com/matze/mtheme). Vielen Dank!!
- Used some parts of [Juan Vera del Campo](https://github.com/Juanvvc) CSS styles. Gracias!
