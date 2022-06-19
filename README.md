# Nord Matplotlib Styles
[Nord](https://www.nordtheme.com/) themed stylesheets for [Matplotlib](https://matplotlib.org/).
Styles strongly inspired by [Seaborn](https://seaborn.pydata.org/).

# Installation and Use
Download the mplstyle files and save them to your Matplotlib style library. To locate your Matplotlib style library, run:
```py
import matplotlib
matplotlib.get_configdir()
```
in an active environment; you may need to create the directory. Save the downloaded `.mplstyle` files there.

Once the styles are in ` mpl_configdir/stylelib` you can load them with `plt.style.use()`. For example:
```py
import matplotlib.pyplot as plt
plt.style.use("nord-light")
```
The styles work best when used together with Seaborn, especially `sns.despine()`.

All styles have a font stack that attempts to use Gill Sans, then falls back on Helvetica or Arial, then falls back on Matplotlib defaults. Gill Sans is a standard system font on both Windows (as Gill Sans MT) and macOS (as Gill Sans). Windows users can also get Gill Sans Nova as a system font by installing the optional [Pan-European Supplemental Fonts](https://docs.microsoft.com/en-us/windows/deployment/windows-10-missing-fonts#install-optional-fonts-manually-without-changing-language-settings).

# Examples
`nord`  
![nord-sample](https://user-images.githubusercontent.com/70354045/174460584-032be275-2386-46ea-8a5f-143904bd5b23.png)

`nord-talk`  
![nord-talk-sample](https://user-images.githubusercontent.com/70354045/174460591-f9909d09-e1b8-49d1-a718-8f7d83b9bc0b.png)

`nord-light`  
![nord-light-sample](https://user-images.githubusercontent.com/70354045/174460592-c06d416b-1354-4b84-8b09-89d5d96fa0ec.png)

`nord-light-talk`  
![nord-light-talk-sample](https://user-images.githubusercontent.com/70354045/174460593-bd596058-0334-4854-8b52-90e542008605.png)

`nord-dark`  
![nord-dark-sample](https://user-images.githubusercontent.com/70354045/174460596-7fdb2c12-4d9a-490c-92f0-0a5526a03c39.png)

`nord-dark-talk`  
![nord-dark-talk-sample](https://user-images.githubusercontent.com/70354045/174460597-65d189e3-79c0-4e65-88c1-01801ad1982f.png)

