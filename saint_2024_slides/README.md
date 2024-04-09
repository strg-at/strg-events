# SAINT 2024: ThatMetricTimeline

This directory hosts the latex source codes (and the necessary assets) to build the slides presented in the talk `ThatMetricTimeline: a simple, fully
open source metric and code tracking library`, given by Alessio Molinari (@levnikmyskin).

The output pdf is already built in the `main.pdf` file. If you wish to compile the slides yourself, please see next section.

## Building
In order to compile the slides, you need a working tex installation, and in particular the `lualatex` compiler.  
Furthermore, you will need the Python [pygments](https://pygments.org/download/) library installed. Once this is working, run:

```shell
lualatex -interaction=nonstopmode -shell-escape -recorder -synctex=1 main.tex
```

If you get errors, it probably means that either your tex installation is not working, or that you're missing a package. Please, install the tex package first, and then retry the build command.
