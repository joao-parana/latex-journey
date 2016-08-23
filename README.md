# latex-journey

> Aprendendo LaTeX

## Links

Primeiros passos no LaTeX: [http://posgraduando.com/introducao-ao-latex-os-primeiros-passos/](http://posgraduando.com/introducao-ao-latex-os-primeiros-passos/)

Video aulas sobre LaTeX: [https://www.youtube.com/watch?v=4pTf8vB9Ezg](https://www.youtube.com/watch?v=4pTf8vB9Ezg)

Editor LaTeX on line: [https://pt.sharelatex.com/](https://pt.sharelatex.com/)

## Instalando LaTeX

### macOS

```bash
brew doctor
brew update 
brew cask install texstudio
```

Faça o Download do `BasicTeX.pkg` em [https://tug.org/mactex/morepackages.html](https://tug.org/mactex/morepackages.html) e instale o software.

```bash
open /Applications/TeXstudio.app
```

#### Resolução de Problemas

**Problema:**

```tex
\RequirePackage{titlesec}
\titlelabel{\thetitle.\hspace{1ex}}
```
gera o erro: 

```
File `titlesec.sty' not found. \titlelabel
```

** Solução:**

Instale o [TeX Live Utility Versão 1.2.6](https://github.com/amaxwell/tlutility/releases)

Depois instale o pacote `titlesec`

![tex-live-utility](docs/tex-live-utility.png)

### Windows

>TBD

