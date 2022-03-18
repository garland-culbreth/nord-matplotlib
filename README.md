# Nord Matplotlib Styles
[Nord](https://www.nordtheme.com/) themed stylesheets for [Matplotlib](https://matplotlib.org/).
Styles strongly inspired by [Seaborn](https://seaborn.pydata.org/).

# Installation
Download the mplstyle files and save them to your Matplotlib style library.  

To locate your Matplotlib style library, run:
```py
import matplotlib
matplotlib.maplotlib_fname()
```
in an active environment. It will return a filepath containing `.../mpl-data/...`. Inside `/mpl-data/` will be a directory named `/stylelib/`. This is your style library; save the mplstyle files there.

# Use
Apply styles with `plt.style.use()`. For example:
```py
import matplotlib.pyplot as plt
plt.style.use("nord-light")
```
They work best when used together with Seaborn, especially `sns.despine()`.

All styles have a font stack that attempts to use Gill Sans, then falls back on Helvetica or Arial, then falls back on Matplotlib defaults. Gill Sans is a standard system font on both Windows (as Gill Sans MT) and macOS (as Gill Sans). Windows users can also get Gill Sans Nova as a system font by installing the optional [Pan-European Supplemental Fonts](https://docs.microsoft.com/en-us/windows/deployment/windows-10-missing-fonts#install-optional-fonts-manually-without-changing-language-settings).

# Examples
`nord-light`  
![light-example](https://user-images.githubusercontent.com/70354045/158936026-be7d077c-3925-47c3-a24d-d3d42afeb1a7.png)

`nord-light-talk`  
![light-talk-example](https://user-images.githubusercontent.com/70354045/158936040-56a89ce8-7679-4ff0-a592-2da5baaffd8e.png)

`nord-dark`  
![dark-example](https://user-images.githubusercontent.com/70354045/158936050-666afdad-eec3-4259-ba2b-e78b1cd6e6e9.png)

`nord-dark-talk`  
![dark-talk-example](https://user-images.githubusercontent.com/70354045/158936060-bc10d54b-4f76-431e-b5e8-43e05d975735.png)
