# Quality Diversity アルゴリズム/最適化

- Quality-Diversity（QD）アルゴリズムとは
  - 最高性能を持つ解（Quality）と，性質が異なる多様な解（Diversity）を同時に探索・獲得する進化計算手法．
  - 単一の最良解のみを探索する従来の最適化法と異なり，行動や特徴の領域ごとにアーカイブを構築し，各領域の最良解を網羅的に蓄積する．
  - 代表例 MAP-Elites:
    - 特徴空間をグリッド分割し，変異と評価を繰り返して優秀な解のマップを構築．
    - 強みは，局所解からの自動脱出とロバスト性．一見非効率な挙動も保存して探索の踏み台とすることで，革新的な解に到達する．さらに，解のライブラリを蓄積することで，故障等にも即座に代替動作へ適応する．

- Python ライブラリ
  - [pyribs](https://pyribs.org/)
  - [Releases · adaptive-intelligent-robotics/QDax](https://github.com/adaptive-intelligent-robotics/QDax/releases)