# short-term-forecasting <!-- omit in toc -->

Short-term forecasting of electricity generation, demand and prices using machine learning, by Nithiya Streethran (nmstreethran@gmail.com).

This is a work-in-progress. Please feel free to suggest improvements (see the [contributing guidelines](/CONTRIBUTING.md)). 

## Table of contents <!-- omit in toc -->
- [Files and folders](#files-and-folders)
- [Resources](#resources)
- [Documentation](#documentation)
- [Funding](#funding)
- [Licenses and terms of use](#licenses-and-terms-of-use)
- [Credits](#credits)

## Files and folders

* [Code of conduct](/CODE_OF_CONDUCT.md)
* [Contributing guidelines](/CONTRIBUTING.md)
* [Code license](/LICENSE.md)
* [data/](https://drive.google.com/drive/folders/1_3Y30j_c-4iai0WuhcrysXHYdZ4F2AKB) contains datasets and their terms of use (available externally on Google Drive)
* [images/](/images/) contains images used and [image license](/LICENSE-images.md)
* [scripts/](/scripts/) contains all Python scripts
* [jupyter-notebooks/](/jupyter-notebooks/) contains Python files in Jupyter notebook format
* [docs/](/docs/) contains the documentation (wiki converted to .html, .tex and .pdf)

## Resources 

The source code editor I use is [VSCodium](https://vscodium.github.io/) (fully open-source alternative to [Visual Studio Code](https://code.visualstudio.com/)), with Git integration and the following extensions:

* [Anaconda Extension Pack](https://marketplace.visualstudio.com/items?itemName=ms-python.anaconda-extension-pack)
* [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
* [Visual Studio IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)
* [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
* [Markdown All in One](https://marketplace.visualstudio.com/itemdetails?itemName=yzhang.markdown-all-in-one)
* [GitHub Pull Requests](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github)
* [YAML](https://marketplace.visualstudio.com/itemdetails?itemName=redhat.vscode-yaml)
* [VS Code Jupyter Notebook Previewer](https://marketplace.visualstudio.com/items?itemName=jithurjacob.nbpreviewer)

Computing:
* Python version 3.6.8
* conda version 4.6.11
* git version 2.18.0.windows.1
* Processor: Intel(R) Core(TM) i5-7200U CPU @ 250 GHz 2.71 GHz
* RAM: 8 GB

My coding notes can be found in my [coding](https://github.com/nmstreethran/coding) repository.

## Documentation

Documentation can be found in the [wiki](https://github.com/ENSYSTRA/short-term-forecasting/wiki). The documentation is also converted into the following formats and can be found in [docs/](/docs/):

GitHub Wiki to HTML using [yakivmospan/github-wikito-converter](https://github.com/yakivmospan/github-wikito-converter):

```
$ gwtc ./wiki ./docs
```

HTML to TeX using [Pandoc](https://pandoc.org/MANUAL.html):

```
$ pandoc -o docs/documentation.tex docs/documentation-input.html
```

## Funding

This work is part of my research as Early-Stage Researcher (ESR) 9 of the [ENSYSTRA (ENergy SYStems in TRAnsition)](https://ensystra.eu/) Innovative Training Network. ENSYSTRA is funded by the European Union's Horizon 2020 research and innovation programme under the Marie Skłodowska-Curie grant agreement No: 765515.

## Licenses and terms of use

Unless otherwise stated:
* Code: [![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
* Documentation: [![License: FDL 1.3](https://img.shields.io/badge/License-FDL%20v1.3-blue.svg)](https://www.gnu.org/licenses/fdl-1.3)
* Images: [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

Licenses and terms of the data used can be found in their corresponding folders within the [data](https://drive.google.com/drive/folders/1_3Y30j_c-4iai0WuhcrysXHYdZ4F2AKB) folder on Google Drive. More information is provided in the [wiki](https://github.com/ENSYSTRA/short-term-forecasting/wiki).

## Credits

Contributing guidelines: adapted from the [Open Science MOOC](https://github.com/OpenScienceMOOC/Module-5-Open-Research-Software-and-Open-Source/blob/master/CONTRIBUTING.md)

License badges: [lukas-h/license-badges.md](https://gist.github.com/lukas-h/2a5d00690736b4c3a7ba); made with [Shields.io](http://shields.io/)

Markdown-formatted Creative Commons licenses: [idleberg/Creative-Commons-Markdown](https://github.com/idleberg/Creative-Commons-Markdown)