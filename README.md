## AutoML を用いたサロゲートモデル構築

本リポジトリは、AutoML ライブラリ PyCaret と AutoGluon を用いて  
NACA4 / NACA5 データセットの Drag / Lift のサロゲートモデルを構築した初期実装です

### 内容
- PyCaret によるモデル比較
- AutoGluon によるアンサンブル学習
- NACA 系翼型パラメータからの Drag / Lift 予測

### ディレクトリ構成
```
.
├── README.md
└── src
├── AutoGluon.ipynb # AutoGluon によるモデル探索
├── data/ # 提供されたデータを置く
├── internal_basemodel_NACA4.ipynb # PyCaret によるモデル探索（NACA4）
├── internal_basemodel_NACA5.ipynb # PyCaret によるモデル探索（NACA5）
└── preprocessing.ipynb # データの前処理
```
### License
本リポジトリのコードは 自由に利用・改変・再配布 して構いません。
形式上は MIT License とします。


