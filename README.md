# GLB2GIF

ブラウザだけで、アニメーション付き GLB を GIF に変換する小さなWebアプリです。

## 特徴

- GLBをドラッグ&ドロップ
- Three.jsによる3Dプレビュー
- GLB内の複数アニメーションを選択
- カメラ回転・ズーム・フィット
- 出力サイズ / FPS / 背景色を指定
- 透明背景GIF
- DRACO / Meshopt圧縮GLBに対応
- GIF生成はブラウザ内で完結
- 選択したGLBファイルをサーバーへアップロードしない

## 推奨設定

最初は **512 × 512 / 15 FPS** を推奨します。

GIFは最大256色なので、高精細なPBRテクスチャや滑らかなグラデーションでは色数が削減されます。

## 使用ライブラリ

- Three.js
- gifenc

## 公開

GitHub Pagesで公開するためのWorkflowを `.github/workflows/pages.yml` に含めています。
