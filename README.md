# LaTeX Ludography

A shared ludography (and associated LaTeX formatting code), allowing game scholars to cite popular games without needing to look up boilerplate information.

We accept contributions!

## How to Use
1. Download the `games.bib` file and place it in your LaTeX source code.
2. Copy the header code at the top of `main.tex` marked `--- LUDOGRAPHY ---` and similarly the bibliography code at the bottom. Place these appropriately into your main tex file.
3. Cite games using `\citegame{name}`, see the `main.tex` provided for examples.

**Remember**: Check the accuracy of any game you cite — this repository is provided as-is. If you find any inaccuracies, please contribute changes via a pull request.


## Licenses
The ACM bibliography is copyrighted (C) 1986, 1988, 2010 Howard Trickey and Oren Patashnik. Per their header, unlimited copying and redistribution of this file are permitted as long as it is unmodified. Modifications (and redistribution of modified versions) are also permitted, but only if the resulting file is renamed.

The remaining code is licensed under the Unlicense, which effectively places it in the public domain. Feel free to use anything in the `.bib` and `.tex` files as you like without attribution, although attribution is appreciated!


## Adding new citations

This template can be used to create a new game citation entry, following the recommendations of the ACM ([https://chiplay.acm.org/2020/guidelines/](https://chiplay.acm.org/2020/guidelines/))


```
@misc{example,
      Title = {\emph{Game}},
      Address = {City, Country},
      Author = {{Developer}},
      Day = {d},
      Month = {m},
      Year = {y},
      Howpublished = {Game [platforms]},
      Note = {Publisher, Address. Last played Month Year.},
      Publisher = {Pub}
}
```

We encourage authors who add to `games.bib` to create a [Pull Request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request) to continue building this shared ludography. Prior to creating your pull request, ensure that the list remains alphabetically sorted using a BibTeX tidying program like [this one](https://flamingtempura.github.io/bibtex-tidy/).
