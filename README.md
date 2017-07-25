<!-- markdown-toc start - Don't edit this section. Run M-x markdown-toc-generate-toc again -->
**Table of Contents**

- [GA_Knapsack](#gaknapsack)
    - [参考](#参考)

<!-- markdown-toc end -->
# GA_Knapsack
ナップザック問題の遺伝的アルゴリズムの最適化に際し，GAを用いて最適化した．

ポケモンの手持ちを6体としたとき，限界重量の中で，人気ランキングを最大化する．という条件だ．

## コードの解説
遺伝子は，バイナリ表現型ではなく，6つのポケモンを辞書を内包したリストで持っている．


突然変異は，評価ランキングの上から保存している．


交叉は，一点交叉．


DEAPライブラリは使ってはいない．

## 実行環境
python2





## 結果の例

* 1500
```
Generation1499: 888 197.0 [(147, 4), (147, 4), (150, 90.5), (150, 90.5), (147, 4), (147, 4)]
```



## 参考

https://github.com/DEAP/deap
http://testpy.hatenablog.com/entry/2017/01/28/185219
