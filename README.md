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

All styles have a font stack that attempts to use Gill Sans, then falls back on Helvetica or Arial, then falls back on Matplotlib defaults. Gill Sans is a standard system font on both Windows (as Gill Sans MT) and macOS (as Gill Sans). Windows users can also get Gill Sans Nova as a system font by installing the optional [Pan-European Supplemental Fonts](https://docs.microsoft.com/en-us/windows/deployment/windows-10-missing-fonts#install-optional-fonts-manually-without-changing-language-settings) for free.


# Examples
<details>
  <summary>nord</summary>

  ![nord](https://github.com/garland-culbreth/nord-matplotlib/assets/70354045/eb0dcd7b-23b5-4538-9ad7-ce2f128b2e07)
</details>

<details>
  <summary>nord-talk</summary>

  ![nord-talk](https://github.com/garland-culbreth/nord-matplotlib/assets/70354045/d79ecce5-159d-469b-a881-0d13d8c9be66)
</details>

<details>
  <summary>nord-light</summary>

  ![nord-light](https://github.com/garland-culbreth/nord-matplotlib/assets/70354045/5b1910f6-0730-410c-a87b-b912462490ab)
</details>

<details>
  <summary>nord-light-talk</summary>

  ![nord-light-talk](https://github.com/garland-culbreth/nord-matplotlib/assets/70354045/d3e16a89-6a88-415d-ac9f-ea90b8074917)
</details>

<details>
  <summary>nord-dark</summary>

  ![nord-dark](https://github.com/garland-culbreth/nord-matplotlib/assets/70354045/030b54e6-86bb-44ed-a6f7-949342515c7e)
</details>

<details>
  <summary>nord-dark-talk</summary>

  ![nord-dark-talk](https://github.com/garland-culbreth/nord-matplotlib/assets/70354045/c5843ada-fe90-41b9-a54a-99d1551bd9df)
</details>

