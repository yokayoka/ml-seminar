# MLゼミ・学習ノート（Numpy & pandas 入門スターター）

このリポジトリは、**Colab ですぐに実行できる** 入門ノートブックと、
MkDocs(Material) を使ったドキュメントサイトの最小構成です。

## 使い方（最短経路）
1. GitHub に新規リポジトリを作成して、このスターターのファイル一式をアップロード
2. `docs/tracks/` のページから **Open in Colab** バッジを押す
3. ノート冒頭の `pip` セルを実行してから学習を進める

## 構成
- `notebooks/10_numpy/intro_numpy.ipynb`
- `notebooks/20_pandas/intro_pandas.ipynb`
- `docs/` + `mkdocs.yml`（GitHub Pages で公開可能）
- `env/requirements.txt`（ローカル学習用の最小依存）

## GitHub Pages（公開）
- Settings → Pages → Build with GitHub Actions を選択し、
  [mkdocs-material のビルド手順]に従って Actions を設定してください（後日自動化 YAML を追加可能）。

## ライセンス
教育目的の再利用しやすさを優先するなら CC BY 4.0 を推奨します（`LICENSE` を追加してください）。