# kkkid333

Pythonで機械学習とエージェントの開発に取り組んでいます。仮説を立て、実装・テスト・比較実験を通じて検証することに関心があります。

## OSSへの貢献

既存のOSSへの修正・テストの貢献です。fork元のプロジェクト全体を自作したものではありません。

- **aeon — HMMSegmenterの予測時の状態変更を修正**  
  [PR #3870](https://github.com/aeon-toolkit/aeon/pull/3870)（提出済み・未マージ、2026年10月6日確認）。予測中の作業用データをローカル変数にし、回帰テストを追加。異なる長さの入力と繰り返し予測で、推定器の状態が変わらないことを検証しました。
- **jevlike — 合成データ生成のhash seed依存を修正**  
  [PR #4](https://github.com/vinnylarouge/jevlike/pull/4)（提出済み・未マージ、2026年10月6日確認）。シャッフル前に候補を整列し、異なるhash seedを使う別プロセスでの再現性テストを追加しました。

## コンペ・実験

- **[PTCG AI Battle Challenge](https://www.kaggle.com/competitions/pokemon-tcg-ai-battle)**  
  Transformerによる方策・価値推定、MLPによる補正、計算量制限付きbeam探索を組み合わせた提出エージェントに取り組みました。この説明は静的な実装確認の範囲に基づき、性能を保証するものではありません。コードや学習重みは配布していません。
- **[Kaggriculture](https://www.kaggle.com/competitions/kaggriculture)**  
  農場経営エージェント競技に参加。2026年10月6日時点では提出締切後の評価期間中で、最終成績・メダルは未確定です。
- **[RSNA Knee](https://www.kaggle.com/competitions/rsna-knee-abnormality-detection)**  
  ラベル品質、画像由来のOOF（out-of-fold）予測、学習量の比較実験に取り組みました。公開されている参照手法と自分の変更を分け、改善しない条件も記録しています。2026年10月6日時点で学習は停止中です。

## 開発と検証

AI支援を活用し、本人による設計判断・レビューと、AIによる実装支援を区別して記録しています。

[GitHub](https://github.com/kkkid333) · [Kaggle](https://www.kaggle.com/kaitoide31)
