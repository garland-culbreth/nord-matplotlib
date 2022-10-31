# Nord Matplotlib Styles
[Nord](https://www.nordtheme.com/) themed stylesheets for [Matplotlib](https://matplotlib.org/).
Styles strongly inspired by [Seaborn](https://seaborn.pydata.org/).


# Examples
`nord`  
![nord-sample](https://user-images.githubusercontent.com/70354045/198936552-aac91759-fa18-48f8-bcc4-f2c2175e036a.png)

`nord-talk`  
![nord-talk-sample](https://user-images.githubusercontent.com/70354045/198936569-20f91790-7324-4dfe-be4b-b6cdfc8b11ac.png)

`nord-light`  
![nord-light-sample](https://user-images.githubusercontent.com/70354045/198936588-7ef505be-5e50-4ba7-b8b3-65ad8291cee0.png)

`nord-light-talk`  
![nord-light-talk-sample](https://user-images.githubusercontent.com/70354045/198936630-2300079b-8fd3-476b-b90b-067af65f0c54.png)

`nord-dark`  
![nord-dark-sample](https://user-images.githubusercontent.com/70354045/198936651-06511aa3-1241-44bc-acb1-abb0958011c4.png)

`nord-dark-talk`  
![nord-dark-talk-sample](https://user-images.githubusercontent.com/70354045/198936676-dc09c39e-163b-4c63-a631-9779ed2cca73.png)


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
plt.style.use("nord")
```
The styles work best when used together with Seaborn, especially `sns.despine()`.

All styles have a font stack that attempts to use Myriad Pro, then Gill Sans, then falls back on Helvetica or Arial, then falls back on Matplotlib defaults. Myriad Pro is a commercial font and to use it you must buy a license from Adobe. Gill Sans is a standard system font on both Windows (as Gill Sans MT) and macOS (as Gill Sans). Windows users can also get Gill Sans Nova as a system font by installing the optional [Pan-European Supplemental Fonts](https://docs.microsoft.com/en-us/windows/deployment/windows-10-missing-fonts#install-optional-fonts-manually-without-changing-language-settings).
