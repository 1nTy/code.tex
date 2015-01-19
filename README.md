# code.tex

`code.tex` is a template for rendering codes in LaTeX with a nice looking syntax highlighting for most used languages.


## Installation

All you need to do is add `\input{\path\code.tex}` before `\begin{document}` in your LaTeX document.

## Usage

`code.tex` use this syntax:
```
\begin{code_<language>}
 ...
\end{code_<language>}
```

## Example


```
\begin{code_c}
// B. Kernighan & D. Ritchie

#include <stdio.h>

int main(int argc, char *argv[])
{
    printf("hello, world\n");
}
\end{code_c}
```

![screen](https://raw.githubusercontent.com/1nTy/code.tex/master/screen.png)


