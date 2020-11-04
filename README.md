# atlas-preamble

My personal standard LaTeX preamble, written as a modular package.


## Installation & Usage
Download the ```.sty``` file and put it into your current project folder or, to make it available for all your current and future projects, include it in your editor's preferences (if available) or copy it to your TeX distribution's file tree (instructions can be found online).

Then, include ```\usepackage[options]{atlas-preamble}``` in your LaTeX file's preamble like with any other package.


## Options
Any of the following options in the first column can be selected (even in combination with one of the six presets) using ```\usepackage[options and/or preset]{atlas-preamble}```. It should be noted that the **_mega_** preset option is recommended, and your results with the **_giga_** option may vary. This is due to the fact that packages loaded with the **toc** and **spacings** options necessarily conflict (this concerns the ```tocloft``` and ```parskip``` packages). Furthermore, the option **headings** defines my own preferred style of chapter/section/etc. headings, so it is also not in the recommended preset.

Somewhat more detailed descriptions, explanations, and potential caveats can be found in the comments of the code itself.

|     | *nano* | *micro* | *milli* | *kilo* | *mega* | *giga* | 
| --- |:------:|:-------:|:-------:|:------:|:------:|:------:| 
| **encoding** | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ |
| **math** | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ |
| **graphics** | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ |
| **tables** | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ |
| **lists** |  | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ |
| **columns** |  | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ |
| **spacings** |  | ⬤ | ⬤ | ⬤ | ⬤ | ⬤ |
| **typesetting** |  |  | ⬤ | ⬤ | ⬤ | ⬤ |
| **captionsfootnotes** |  |  | ⬤ | ⬤ | ⬤ | ⬤ |
| **hyperref** |  |  | ⬤ | ⬤ | ⬤ | ⬤ |
| **theorems** |  |  |  | ⬤ | ⬤ | ⬤ |
| **physics** |  |  |  | ⬤ | ⬤ | ⬤ |
| **code** |  |  |  |  | ⬤ | ⬤ |
| **toc** |  |  |  |  |  | ⬤ |
| **headings** |  |  |  |  |  | ⬤ |
