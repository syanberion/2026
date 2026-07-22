# 2026
ゼミ2026年度

* [夏休みの課題](summer_projects)

## 課題の候補

* ナッシュ均衡計算アルゴリズムを実装してみる
  - 「[Nash 均衡の計算](https://github.com/OyamaZemi/algorithms/blob/master/nash_equilibrium/README.md)」参照
  - 大規模ゲーム
  - 1. [Imitation game アルゴリズム](https://github.com/QuantEcon/QuantEcon.py/blob/fae512cde11f2264618b515184f38bede37ae52f/quantecon/_compute_fp.py#L159)を Julia に翻訳する ([QuantEcon.jl](https://github.com/QuantEcon/QuantEcon.jl) に入れる)
    2. [Mclennan-Tourky アルゴリズム](https://github.com/QuantEcon/QuantEcon.py/blob/main/quantecon/game_theory/mclennan_tourky.py)を Julia に翻訳する ([GameTheory.jl](https://github.com/QuantEcon/GameTheory.jl) に入れる)
  - 1. Polymatrix game 関連コード
      ([polymatrix_game.py](https://github.com/QuantEcon/QuantEcon.py/blob/main/quantecon/game_theory/polymatrix_game.py),
       [howson_lcp.py](https://github.com/QuantEcon/QuantEcon.py/blob/main/quantecon/game_theory/howson_lcp.py))
      を改善する
    2. それらを Julia に翻訳する ([GameTheory.jl](https://github.com/QuantEcon/GameTheory.jl) に入れる)

* 展開形ゲームの情報構造・アルゴリズムを実装してみる
  - B. von Stengel,
    "[Equilibrium Computation for Two-Player Games in Strategic and Extensive Form](http://www.maths.lse.ac.uk/personal/stengel/TEXTE/agt-stengel.pdf),"
    Chapter 3, Algorithmic Game Theory, 2007
  - D. Koller, N. Megiddo, and B. von Stengel,
    "[Eﬃcient Computation of Equilibria for Extensive Two-Person Games](http://www.maths.lse.ac.uk/personal/stengel/TEXTE/geb1996b.pdf),"
    Games and Economic Behavavior 14, 247–259, 1996

* 動的計画問題を解いてみる
  - [The Income Fluctuation Problem I: Discretization and VFI](https://python.quantecon.org/ifp_discrete.html)
    - [QuantEcon.py](https://github.com/QuantEcon/QuantEcon.py) の
      [DiscreteDP](https://quanteconpy.readthedocs.io/en/stable/markov/ddp.html) を使って実装してみる．
      最初は `a_size` と `y_size` を小さめにしてみる．
      そのあと sparse matrix を使って実装してみる ("State-action pairs formulation" で実装する)．
    - [ContinuousDPs.jl](https://github.com/QuantEcon/ContinuousDPs.jl) を使って実装してみる．
  - Miranda and Fackler, [Applied Computational Economics and Finance](https://www.amazon.co.jp/dp/0262633094),
    Chapters 8, 9
    - [MirandaFackler.notebooks](https://github.com/OyamaZemi/MirandaFackler.notebooks)
  - [ContinuousDPs.jl](https://github.com/QuantEcon/ContinuousDPs.jl) を使ってみる/機能を追加する
  - Santos (1999)
    "[Numerical solution of dynamic economic models](https://www.sciencedirect.com/science/article/abs/pii/S1574004899010083),"
    Handbook of Macroeconomics, Chapter 5
  - Job Search III: Search with Learning
    [[Python](https://python.quantecon.org/odu.html)]
    [[Julia](https://julia.quantecon.org/dynamic_programming/odu.html)]
    - [POMDPs.jl](https://github.com/JuliaPOMDP/POMDPs.jl) を使って実装してみる．

* 既存論文の数値解析を再現してみる
  - ...

* 『[実証ビジネス・エコノミクス](https://sites.google.com/view/keisemi-ebiz/)』のRコードの Python 版を作る

* - [QuantEcon.py](https://github.com/QuantEcon/QuantEcon.py) [Issues](https://github.com/QuantEcon/QuantEcon.py/issues)
  - [QuantEcon.jl](https://github.com/QuantEcon/QuantEcon.jl) [Issues](https://github.com/QuantEcon/QuantEcon.jl/issues)
  - [GameTheory.jl](https://github.com/QuantEcon/GameTheory.jl) [Issues](https://github.com/QuantEcon/GameTheory.jl/issues)
  - [ContinuousDPs.jl](https://github.com/QuantEcon/ContinuousDPs.jl) [Issues](https://github.com/QuantEcon/ContinuousDPs.jl/issues)

## PRの練習用  
こんにちは
## PRの練習用

どんも〜✋
2026/4/27 環境設定で一苦労
村田匠　はじめまして
* - 山禄凛多郎（さんろくりんたろう）
  - 東京大学経済学部金融学科4年・青木ゼミ尾山ゼミ所属
本橋薫です

こんにちは
- 須田悠雅
- さくらい
