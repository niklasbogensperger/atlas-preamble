# atlas-preamble

My personal standard LaTeX preamble, written as a modular package.


## Installation & Usage
Download the ```.sty``` file and put it into your current project folder or, to make it available for all your current and future projects, include it in your editor's preferences (if available) or copy it to your TeX distribution's file tree (instructions can be found online).

Then, include ```\usepackage[options]{atlas-preamble}``` in your LaTeX file's preamble like with any other package.


## Options
Any of the following options in the first column can be selected (even in combination with one of the presets) using ```\usepackage[options and/or preset]{atlas-preamble}```.

The **_complete_** preset option is recommended if you want the most comprehensive combination of options without any problems (hopefully!). It should be noted that this preset and the **_script_** preset include the **headings** option, which defines my own preferred style of chapter/section/subsection headings and may not suit your taste. Your results may vary when using the **_all_** preset (which includes the **code** option already) or setting the **code** or **toc** options manually. This is because the **code** option may not play nice with your setup or require extra configuration of your editor of choice because it needs to invoke LaTeX' shell-escape function to let the ```minted``` package perform syntax highlighting, which has to happen outside of your LaTeX editor. The omission of the **toc** option from every preset is due to the fact that the packages loaded with the **toc** and **spacings** options (```tocloft``` and ```parskip``` packages, respectively) necessarily conflict and cannot be made to work together reliably in every case.

Somewhat more detailed descriptions, explanations, and potential caveats can be found in the comments of the code itself.

|     | *base* | *extra* | *experiment* | *script* | *compsci* | *probability* | *complete* | *all* |
| --- |:------:|:-------:|:------------:|:--------:|:---------:|:---------:|:----------:|:-----:|
| **encoding** | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ |
| **graphics** | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ |
| **math** | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ |
| **tables** | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ |
||||||||||
| **columns** |  | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ |
| **lists** |  | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ |
| **spacings** |  | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ |
| **typesetting** |  | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ |
||||||||||
| **captionsfootnotes** |  |  | ⬤ | ⬤ |  |  | ⬤ | ⬤ |
| **cs** |  |  |  |  | ⬤ |  | ⬤ | ⬤ |
| **headings** |  |  |  | ⬤ |  |  | ⬤ | ⬤ |
| **physics** |  |  | ⬤ | ⬤ | ⬤ |  | ⬤ | ⬤ |
| **references** |  |  | ⬤ | ⬤ |  |  | ⬤ | ⬤ |
| **statistics** |  |  |  |  |  | ⬤ | ⬤ | ⬤ |
| **theorems** |  |  |  | ⬤ |  |  | ⬤ | ⬤ |
||||||||||
| **code** |  |  |  |  |  |  |  | ⬤ |
| **toc** |  |  |  |  |  |  |  |  |
