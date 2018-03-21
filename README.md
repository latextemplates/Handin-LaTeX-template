# Handin/submission LaTeX template
Light weight template for handing in school submissions using LaTeX. Suitable for math, physics, statistics and the like.

## Quickstart
Download the [quickstart.zip](https://github.com/Strauman/Handin-LaTeX-template/blob/master/quickstart.zip?raw=true). It contains two files: [example.tex](https://raw.githubusercontent.com/Strauman/Handin-LaTeX-template/master/example.tex) and [handin.sty](https://raw.githubusercontent.com/Strauman/Handin-LaTeX-template/master/handin.sty). Build example.tex and you're all good to go.

## Example files
Look at the [example.pdf](https://raw.githubusercontent.com/Strauman/Handin-LaTeX-template/master/example.pdf) generated by [example.tex](https://raw.githubusercontent.com/Strauman/Handin-LaTeX-template/master/example.tex) for an example that could be used at UiT - The Arctic University of Norway.

## Dependencies
`inputenc,graphicx,lastpage,scrextend,fancyhdr,geometry,amsmath,mathtools,bm,esint,iflang`

## Internationalization
Currently using `iflang` to decide betwen norwegian and english.

## Quick docs:
### Commands
`\problem{1}` would create a *Problem 1* headline and `\pproblem{a}` would then print *1a)* subheadline (with some margin magic and other snacks). More functionality will be made, also feel free to request functionality.

### Front page (`\maketitle`)
In the [layout.pdf](https://raw.githubusercontent.com/Strauman/Handin-LaTeX-template/master/layout.pdf) is an overview of what commands go where. They are all used as commands to be set:
- `\title{Assignment title}`
- `\author{Author(s)}`
- `\coursename{TST-101}`
- `\coursetitle{Test course}`
- `\institute{Institute of Physics and Technology}`
- `\logo{path/to/logo/or/image}`
- `\pagetext{Page \thepage~of \pageref{LastPage}}`
- `\containspages{Contains \pageref{LastPage} pages, front page included}`

`pagetext` and `containspages` are set to the values you see above.
