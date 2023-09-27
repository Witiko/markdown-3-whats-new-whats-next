# Markdown 3: Co je nového a co se chystá?

Tento repozitář obsahuje zdrojový kód článku *Markdown 3: Co je nového a co
se chystá?* s překladem [mé přednášky na konferenci TUG 2023][4], který se
chystám zveřejnit ve Zpravodaji CSTUGu.

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
