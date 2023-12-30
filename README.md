# Markdown 3: Co je nového a co se chystá?

Tento repozitář obsahuje zdrojový kód článku *Markdown 3: Co je nového a co
se chystá?* s překladem [mé přednášky na konferenci TUG 2023][4] ze
Zpravodaje CSTUGu 2023/3–4.

Pro sazbu článku potřebujeme unixový systém s nainstalovaným programem
[FFmpeg][5].

PDF dokument [`main.pdf`][1] s textem článku vysázíme následujím příkazem:

``` bash
latexmk -lualatex -shell-escape main.tex
```

Jako vedlejší produkt sazby vzniknou soubory [`markdown-3-cs.srt`][2] a
[`markdown-3-en.srt`][3] s českými a anglickými titulky k [videozáznamu
přednášky][4].

 [1]: https://github.com/Witiko/markdown-3-whats-new-whats-next/releases/download/latest/main.pdf
 [2]: https://github.com/Witiko/markdown-3-whats-new-whats-next/releases/download/latest/markdown-3-cs.srt
 [3]: https://github.com/Witiko/markdown-3-whats-new-whats-next/releases/download/latest/markdown-3-en.srt
 [4]: https://youtu.be/U8XjTOhJkg0
 [5]: https://ffmpeg.org/

## Citace

Pro citování tohoto článku použijte následující kód pro BibLaTeX:

``` bib
@article{starynovotny2023markdown,
  title = {Markdown 3},
  subtitle = {Co je nového a co se chystá?},
  author = {Starý Novotný, Vít},
  journal = {Zpravodaj \CSTUG u},
  issn = {1211-6661},
  year = {2023},
  volume = {33},
  number = {3--4},
  doi = {10.5300/2023-3-4/111},
  pages = {111-124},
}
```
