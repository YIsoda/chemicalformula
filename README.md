# chemicalformula
組版システム [SATySFi](https://github.com/gfngfn/satysfi) で化学式を楽に表現できるように作ってみたパッケージです。

注意: このパッケージは非推奨となっているプリミティブを使用しているので，現行のバージョンのSATySFiで動作するかはわかりません。
（SATySFi 0.0.1(SATySFi for Windows 20180707)で動作することを確認しています。）

# 使用例

```
@import chemicalformula
% 例えば+p{}の中で
\chem(`CH3CH2OH`);
```
>CH<sub>3</sub>CH<sub>2</sub>OH
