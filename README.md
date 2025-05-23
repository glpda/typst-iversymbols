
# IverSymbols

Symbols definition for Iversonian languages.


## Features

Currently include symbol dictionaries for:
- [BQN](https://mlochbaum.github.io/BQN/index.html)
- [Uiua](https://www.uiua.org/)
- [APL\360](https://aplwiki.com/wiki/APL%5C360)
- [APL64](https://aplwiki.com/wiki/APL64)
- [Dyalog APL](https://aplwiki.com/wiki/Dyalog_APL)
- [Extended Dyalog APL](https://aplwiki.com/wiki/Extended_Dyalog_APL)
- [NARS](https://aplwiki.com/wiki/NARS)
- [NARS2000](https://nars2000.org/)

TODO:
- [dzaima/APL](https://aplwiki.com/wiki/Dzaima/APL)
- [Kap](https://aplwiki.com/wiki/Kap)
- [Sharp APL](https://aplwiki.com/wiki/SHARP_APL)


## Usage

```typst
#import "@preview/iversymbols:0.1.0": bqn

Euclidean norm: $+ bqn.fold bqn.under (bqn.mult bqn.self)$  // +´⌾(×˜)
```


## Font Recommendation

You can find typefaces with good support for Iversonian languages' character sets there:
- [APL Wiki - Fonts](https://aplwiki.com/wiki/Fonts)
- [Fonts for BQN](https://mlochbaum.github.io/BQN/fonts.html)
- [Uiua386, colored](https://github.com/jonathanperret/uiua386color)


## License

This package is under the [MIT license](LICENSE).



