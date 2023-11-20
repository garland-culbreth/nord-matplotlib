# Nord Matplotlib Styles
[Nord](https://www.nordtheme.com/) themed stylesheets for [Matplotlib](https://matplotlib.org/).
Styles strongly inspired by [Seaborn](https://seaborn.pydata.org/).


# Installation and Use
Download the mplstyle files and save them to your Matplotlib style library. To locate your Matplotlib style library, run:
```py
import matplotlib
matplotlib.get_configdir()
```
in an active environment. In the directory returned by the command, look for a subdirectory named `stylelib`; you may need to create one. Save the downloaded `.mplstyle` files in the `stylelib` directory.

Once the styles are in ` mpl_configdir/stylelib` you can load them with `plt.style.use()`. For example:
```py
import matplotlib.pyplot as plt
plt.style.use("nord")
```
The styles work best when used together with Seaborn, especially `sns.despine()`.

All styles have a font stack that attempts to use Roboto, then falls back on Helvetica or Arial, then falls back on Matplotlib defaults. Roboto is available for free on [Google fonts](https://fonts.google.com/specimen/Roboto).


# Examples
<details>
  <summary>nord</summary>

  ![nord](https://github.com/garland-culbreth/nord-matplotlib/assets/70354045/52b45c20-e738-4e6c-b610-9c376871ae19)
</details>

<details>
  <summary>nord-talk</summary>

  ![nord-talk](https://github.com/garland-culbreth/nord-matplotlib/assets/70354045/a2fa0a02-2d5f-4b77-b4ea-f87b5b434b6c)
</details>

<details>
  <summary>nord-light</summary>

  ![nord-light](https://github.com/garland-culbreth/nord-matplotlib/assets/70354045/fa7ae3c6-1b46-4a16-85b5-ec913bbb86e0)
</details>

<details>
  <summary>nord-light-talk</summary>

  ![nord-light-talk](https://github.com/garland-culbreth/nord-matplotlib/assets/70354045/efbdfdc3-14d3-4dc4-a1cd-e703cd4df2ef)
</details>

<details>
  <summary>nord-dark</summary>

  ![nord-dark](https://github.com/garland-culbreth/nord-matplotlib/assets/70354045/8d4fe843-783a-45a5-9637-c6ea00914eac)
</details>

<details>
  <summary>nord-dark-talk</summary>

  ![nord-dark-talk](https://github.com/garland-culbreth/nord-matplotlib/assets/70354045/e63f8bcf-2293-41f7-8a80-5f5eb222f77a)
</details>

