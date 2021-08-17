<h1 align="center"><img src="icon.svg" width="124" /> <br />Resume</h1>
<p align="center"><strong>LaTex cv made easy.</strong></p>

Takes a resume in [latex](resume.tex) and generates a [pdf](resume.pdf). It was inspired by [resume](https://github.com/sb2nov/resume) and tweaked to my personal needs and improved with a simpler workflow. The original setup required docker and running commands every time you edited to regenerate the pdf. With this approach, you can edit latex and view the pdf all in one place, in real time.

## Pre-requisites

- MacOS
- [MiKTeX](https://miktex.org/) - LaTex binary
- [VSCode](https://code.visualstudio.com/) - editor
- [LaTeX-Workshop](https://github.com/James-Yu/LaTeX-Workshop) - VSCode extension for LaTex

### Getting LaTeX-Workshop to work

You are going to need a binary for LaTex. Per their [documentation](https://github.com/James-Yu/LaTeX-Workshop/wiki/Install#requirements), they list different LaTex distributions. And if you don't already have set up LaTex on your machine it's hard to figure out exactly what you need. Having gone through the trials and tribulations of installations, what I recommend is [MiKTeX](https://miktex.org/). It was the simplest to get set up without much additional configs. I found that TexLive and MacTex were confusing to set up and I could not get them to work.

### Steps

- Install MkTex and allow system permissions
- 