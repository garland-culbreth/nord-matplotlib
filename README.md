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

  ![ex-nord](https://github.com/garland-culbreth/nord-matplotlib/assets/70354045/7a0cfc00-5272-45f2-85a9-4ebc84e34d8c)
</details> 

<details>
  <summary>nord-talk</summary>

  ![ex-nord-talk](https://github.com/garland-culbreth/nord-matplotlib/assets/70354045/1e7d02d5-9818-4038-ba2e-e075e0d909e1)
</details>

<details>
  <summary>nord-light</summary>

  ![ex-nord-light](https://github.com/garland-culbreth/nord-matplotlib/assets/70354045/6e4eb298-e01a-4794-9551-20c410d8ac90)
</details>

<details>
  <summary>nord-light-talk</summary>

  ![ex-nord-light-talk](https://github.com/garland-culbreth/nord-matplotlib/assets/70354045/99e12bb5-a72f-4c55-bbd4-e9ab34397c1b)
</details>

<details>
  <summary>nord-dark</summary>

  ![ex-nord-dark](https://github.com/garland-culbreth/nord-matplotlib/assets/70354045/ff67c57f-cc08-4881-b280-1d4c465ed558)
</details>

<details>
  <summary>nord-dark-talk</summary>

  ![ex-nord-dark-talk](https://github.com/garland-culbreth/nord-matplotlib/assets/70354045/026604f2-bfdb-462c-a06c-c7a05bfc29b0)
</details>

