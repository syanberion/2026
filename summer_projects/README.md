# 夏休みの課題

成果物を世に公開する

1. 自分のライブラリを開発する
2. 既存のライブラリに新しい機能を追加する
3. 勉強したことなどを Jupyter notebook にまとめて自分のレポジトリで公開する
   * 論文の結果の再現コード
   * QuantEcon のレクチャーの別実装

何をやるかについては教員と相談する

* [表のページ](../README.md) から課題を探すとよい

---

## 7/13までの課題

以下のいずれか一つ

* 面白そうなゲーム (標準形ゲーム) を見つけて `QuantEcon.py` の `game_theory` モジュールを使ってその Nash 均衡を求めてみる． ([マニュアル](https://quanteconpy.readthedocs.io/en/stable/game_theory/normal_form_game.html))
  * 必要なら [jlgametheory](https://github.com/QuantEcon/jlgametheory) も使ってみる．
  * 2人ゲームなら多い行動数でも解けるが，3人以上の場合は少ない行動数でないと解けないので注意．
  * 余力があれば，Julia 版の [GameTheory.jl](https://github.com/QuantEcon/GameTheory.jl) も使ってみる．
* QuantEcon の dynamic programming 関連のレクチャーを `QuantEcon.py` の `DiscreteDP` を使って解いてみる．
  * [Job Search I: The McCall Search Model](https://python.quantecon.org/mccall_model.html) や [Optimal Savings I: Cake Eating](https://python.quantecon.org/os.html) が比較的簡単かも．
  * [The Income Fluctuation Problem I: Discretization and VFI](https://python.quantecon.org/ifp_discrete.html)

コマンド例

```python
import quantecon.game_theory as gt
matching_pennies_bimatrix = [[(1, -1), (-1, 1)], [(-1, 1), (1, -1)]]
g = gt.NormalFormGame(matching_pennies_bimatrix)
print(g)
gt.vertex_enumeration(g)
```

結果は，それ用のレポジトリを作って，そこに Jupyter notebook を置く．

### 成果物のリスト

* 須田悠雅 [pricing_game.ipynb](https://github.com/sudayuga/2026_0713_homework.git)
