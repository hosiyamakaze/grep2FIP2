# grep2FIP2
A PS script for processing grep results(Sakura Editor) for the Idea Processor Frieve Editor V3.00.

サクラエディタのgrep検索結果をFrieve Editorで活用するためカードデータに加工するPowerShellスクリプト。
Frieve Editor Version 3.00(FIP2)対応版

----- console sample
> .\grep2FIP2.ps1
grep検索結果ファイル名?N:\fipアイデアプロセッサ【Grep】\コロナ.txt
fipファイル名:N:\fipアイデアプロセッサ【Grep】\コロナ.fip2
カード枚数を集計中...済み.
カードは重複を取り除いて、237枚あります。
同名のfipファイルが存在します。更新しますか(y/n)?y
[Global]セクション出力中...済み.
LABELS type=0カードラベルセクション出力中...済み.
LABELS type=1リンクラベルセクション出力中...済み.
CARDS focus=-1カード本体セクション出力中...済み.
終了しました。

> 
