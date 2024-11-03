# Pyxel VNC Template
このプロジェクトは、GitHub CodespacesでPyxelを使用するためのテンプレートです。

使い方:
1. このリポジトリからプロジェクトを作成します。 
2. Codespacesでプロジェクトを開きます。
3. 環境がセットアップされたら、仮想ディスプレイとVNCサーバーでPyxelを実行します。 

## 実行コマンド
xvfb-run -s "-screen 0 1024x768x24" python your_pyxel_game.py
