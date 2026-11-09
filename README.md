# grep2FIP2
- A PS script for processing grep results(Sakura Editor) for the Idea Processor Frieve Editor V3.00.

# 検索結果をカード化するアイデアを整理する(日本語説明) #
- サクラエディタのgrep検索結果をFrieve Editorで活用するためカードデータに加工するPowerShellスクリプト。
- Frieve Editor Version 3.00(FIP2)対応版

## 使用するツール
1. [サクラエディタはMS Windows上で動作する日本語テキストエディタです](https://sakura-editor.github.io/)
2. [feditor複雑な思考や斬新なアイデアの発想を支援するアイデアプロセッサ](https://www.frieve.com/software/frieve-editor) (V3.00)

## grep検索を実行する
1. サクラエディタでgrepを実行する
    - 結果出力:該当行
    - 結果出力形式:ノーマル または ファイル毎<br>
            複数の検索結果を扱う場合は結果出力形式は同一のものでまとめる<br>
2. 検索結果をファイルに保存する
    - 現状これらはSJISを前提とする
    - grep検索結果ファイルのフルパスを取得する

## grep検索結果から.fip2ファイルを生成する
1. PowerShellで「grep2FIP2.ps1」を実行する
```PowerShell
./grep2FIP2.ps1
```
- grep検索結果ファイルのフルパスを応答する

## feditorでアイデアを整理する
- .fip2ファイルを開く
- feditorのUIを活用する

## 以下の機能を実現するにはfeditorの変更が必要
- 外部リンクがサクラエディタのタグジャンプの書式に従う場合は、タグジャンプする
- インポート「フォルダ内テキスト」で外部リンクする(grepとは独立要件)
- Viewウインドのラベル名欄を大きくする(grepとは独立要件)

