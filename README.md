Implementation of [precious themes](https://github.com/precious-themes) for KDiff3.

Installing
---

Instead of manually copying values from txt files into `kdiff3rc` file, there is a much faster way by using KDiff3
itself:

- Open kdiff3, choose a txt file with colors as **`A`**, and `kdiff3rc` file as **`B`**
- Go to `Configure -> Diff -> Line matching preprocessor command` and set it to:  
  `sed -r 's/(\w+?)=.*$/\1/g' -`
- Press `F5` to refresh, then merge using `Choose A for all unsolved whitespace conflicts`, then
  `Choose B for all unsolved conflicts`, save, reload KDiff3 and remove the preprocessor command

Screenshots
---

(_Click to view an image in full size_)

[<img src="https://raw.githubusercontent.com/precious-themes/.github/master/screenshots/precious-themes-kdiff3/kdiff3-precious-dark-eleven.avif" width=49% alt="konsole-precious-dark-eleven" />](https://raw.githubusercontent.com/precious-themes/.github/master/screenshots/precious-themes-kdiff3/kdiff3-precious-dark-eleven.png) [<img src="https://raw.githubusercontent.com/precious-themes/.github/master/screenshots/precious-themes-kdiff3/kdiff3-precious-dark-fifteen.avif" width=49% alt="konsole-precious-dark-fifteen" />](https://raw.githubusercontent.com/precious-themes/.github/master/screenshots/precious-themes-kdiff3/kdiff3-precious-dark-fifteen.png)
[<img src="https://raw.githubusercontent.com/precious-themes/.github/master/screenshots/precious-themes-kdiff3/kdiff3-precious-light-warm.avif" width=49% alt="konsole-precious-light-warm" />](https://raw.githubusercontent.com/precious-themes/.github/master/screenshots/precious-themes-kdiff3/kdiff3-precious-light-warm.png) [<img src="https://raw.githubusercontent.com/precious-themes/.github/master/screenshots/precious-themes-kdiff3/kdiff3-precious-light-white.avif" width=49% alt="konsole-precious-light-white" />](https://raw.githubusercontent.com/precious-themes/.github/master/screenshots/precious-themes-kdiff3/kdiff3-precious-light-white.png)
