# Prototype: Immersal AR + 8thWall Template

![](immersal.gif)

[English README](readme.md)


## 概要
- Immersal ARと8th Wallを使った最小限の位置合わせサンプルです
- WebARにはThree.jsを使用しています
- 点群(PLY)またはGLBファイルをダウンロードして表示することができます<br>
https://github.com/tkada/immersal-8thwall-template/blob/main/js/classes/Immersal.js


## セットアップ

1. `.env.local` ファイルをプロジェクトのルートに作成します。その中に8th WallのAPI Key, Immersal developer token, map idを記述します

```
VITE_8THWALL_APP_KEY=xxxxxxxxxxxxxxxxxxxxxxxxx
VITE_IMMERSAL_TOKEN=xxxxxxxxxxxxxxxxxxxxxxxxx
VITE_MAP_ID=xxxxx
```

2. 8th WallプロジェクトにローカルIPを設定します。8th WallプロジェクトのHosting > Edit > add your local ip addressから設定することができます

3. 下記のコマンドで実行できます

```bash
# 初期セットアップ
yarn

# ローカルサーバの実行
yarn dev

# ビルド
yarn build
```
