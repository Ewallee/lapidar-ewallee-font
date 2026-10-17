# Lapidar-Ewallee

[![License](https://img.shields.io/badge/License-OFL%201.1-green)](LICENSE)
![Version](https://img.shields.io/badge/Version-0.6-9070D0)
![Weights](https://img.shields.io/badge/Weights-400%E2%80%93900-c8862a)
![Scripts](https://img.shields.io/badge/Scripts-Latin%20%2B%20Cyrillic-c8862a)

<a href="https://github.com/Ewallee/lapidar-ewallee-font/raw/main/LapidarEwallee.zip"><img height="44" alt="СКАЧАТЬ / DOWNLOAD" src="https://img.shields.io/badge/%D0%A1%D0%9A%D0%90%D0%A7%D0%90%D0%A2%D0%AC%20%2F%20DOWNLOAD-Lapidar--Ewallee%20fonts-c8862a?style=for-the-badge"></a>

A display serif in the spirit of Roman inscriptional capitals, for Latin and Cyrillic.

Wedge serifs, slightly waisted stems and contrast with an inclined axis, like letters cut
in stone. Upper and lower case, plus small caps for headings in the inscriptional manner.

![Lapidar-Ewallee: Latin, Cyrillic and figures](images/hero.png)

## What's inside

- **Latin and Cyrillic.** Upper and lower case, A–Z, А–Я and Ё, figures, punctuation, № and ₽.
- **Small caps.** OpenType features `smcp` and `c2sc`: lower case or capitals to small capitals.
- **Three weights.** Regular, Bold and Black as separate OTF files.
- **Variable font.** One file with a weight axis from 400 to 900.
- **Alternate Д and Л.** Stylistic set `ss01` switches to triangular forms, in every case.
- **Kerning.** Pairs like AV, LT, ТА and УА are kerned.
- **Web fonts.** WOFF2 with a ready CSS file.

![Weights from 400 to 900](images/weights.png)

## Install

1. Download [LapidarEwallee.zip](https://github.com/Ewallee/lapidar-ewallee-font/raw/main/LapidarEwallee.zip) - the button above.
2. Unpack it.
3. Install the fonts: on Windows right-click the files → **Install**, on macOS open them in Font Book.

Install either the three OTF files or the variable font, not both: apps may mix them up.

## Files

| File | |
|---|---|
| `otf/LapidarEwallee-Regular.otf` | Regular, 400 |
| `otf/LapidarEwallee-Bold.otf` | Bold, 700 |
| `otf/LapidarEwallee-Black.otf` | Black, 900 |
| `variable/LapidarEwallee[wght].ttf` | variable, 400–900: Regular, Medium, SemiBold, Bold, ExtraBold, Black |
| `web/` | WOFF2 and CSS for websites |

<img src="images/smallcaps.png" width="49%" alt="Lower case and small caps"> <img src="images/alternates.png" width="49%" alt="Stylistic set ss01: triangular Д and Л">

## On the web

```html
<link rel="stylesheet" href="web/lapidar-ewallee.css">
```

```css
h1   { font-family: "Lapidar-Ewallee", serif; font-weight: 700; }
.sc  { font-variant-caps: small-caps; }      /* smcp: lower case to small caps */
.alt { font-feature-settings: "ss01"; }       /* triangular Д and Л */
```

Any weight from 400 to 900 works, for example `font-weight: 650`.

## License

[SIL Open Font License 1.1](LICENSE). Free to use, embed and modify, including in commercial work.
The fonts cannot be sold by themselves, and modified versions must stay under the same license.
Documents, sites and images made with the fonts carry no obligations.
