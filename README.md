
## Install

```
sudo apt install texlive-xetex
sudo apt install python-pygments
```
```
sudo apt install ttf-mscorefonts-installer scalable-cyrfonts-tex
sudo apt install texlive-luatex
```

Setup Fonts
```
fc-cache -f -v
luaotfload-tool -u -f
```

Change settings inside TexMaker
```
add flag to xelatex and luatex: -shell-escape
```

## Build PDF

```
spell-check.sh
```
```
build-pdf.sh -f file.tex
```

## Editor

Default editor is TexMaker (http://www.xm1math.net/texmaker/)


# Documents

