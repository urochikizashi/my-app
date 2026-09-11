# 3D Minecraft Web (Three.js MVP)

HTML5 / CSS / JavaScript と [Three.js](https://threejs.org/) を使用して作成された、ブラウザ上で動作する3Dボクセルクラフトゲーム（マインクラフトMVP）です。外部画像ファイルなどの外部依存なし（テクスチャやSEはプロシージャル生成）で単一のHTMLファイルで動作します。

## 🎮 操作方法

| キー / 操作 | アクション |
| :--- | :--- |
| **画面クリック** | ゲーム開始・マウスロック |
| **W, A, S, D** / 矢印キー | 前後左右に移動 |
| **SPACE** | ジャンプ |
| **マウス移動** | 視点回転（一人称FPS視点） |
| **左クリック** | 照準先のブロックを破壊 |
| **右クリック** | 照準面にブロックを設置 |
| **数字キー 1〜7** / **ホイール** | 設置するブロックの切り替え |
| **ESC** | マウスロック解除 |

## 🧱 ブロック種類
1. 草ブロック (Grass)
2. 土 (Dirt)
3. 石 (Stone)
4. 木材 (Wood)
5. 葉 (Leaves)
6. レンガ (Bricks)
7. 水 / ガラス (Glass)

## 🚀 GitHub Pages への公開について
- GitHub Actionsによる自動デプロイワークフロー (`.github/workflows/deploy.yml`) が含まれています。
- リポジトリの **Settings > Pages** で、Source が `GitHub Actions` に設定されていることをご確認ください。