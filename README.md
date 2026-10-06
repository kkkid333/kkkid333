# kkkid333

Pythonで機械学習とエージェントの開発に取り組んでいます。仮説を立て、実装・テスト・比較実験を通じて検証することに関心があります。

## OSSへの貢献

既存のOSSへの修正・テストの貢献です。fork元のプロジェクト全体を自作したものではありません。

- **aeon — HMMSegmenterの予測時の状態変更を修正**  
  [PR #3870](https://github.com/aeon-toolkit/aeon/pull/3870)（提出済み・未マージ、2026年10月6日確認）。予測中の作業用データをローカル変数にし、回帰テストを追加。異なる長さの入力と繰り返し予測で、推定器の状態が変わらないことを検証しました。
- **jevlike — 合成データ生成のhash seed依存を修正**  
  [PR #4](https://github.com/vinnylarouge/jevlike/pull/4)（提出済み・未マージ、2026年10月6日確認）。シャッフル前に候補を整列し、異なるhash seedを使う別プロセスでの再現性テストを追加しました。

## コンペ・実験

- **[PTCG AI Battle Challenge](https://www.kaggle.com/competitions/pokemon-tcg-ai-battle)**：1,673位 / 6,807チーム
- **[Kaggriculture](https://www.kaggle.com/competitions/kaggriculture)**：暫定832位・銅メダル圏内（2026年10月6日時点）
- **[RSNA Knee](https://www.kaggle.com/competitions/rsna-knee-abnormality-detection)**：参加中

## 開発と検証

AI支援を活用し、本人による設計判断・レビューと、AIによる実装支援を区別して記録しています。

[GitHub](https://github.com/kkkid333) · [Kaggle](https://www.kaggle.com/kaitoide31)
