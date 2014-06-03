# lextech


## terminal command
view |  | vimの読み取り専用でファイルを開く

cat | ファイル名 | ファイルの内容を表示する

clear |  | 画面をクリア

cp |  | ファイルやディレクトリをコピー

ll |  |  ls -lの省略形

pwd |  | 現在のディレクトリを表示

cd | ../ | 一つ上のディレクトリに移動

cd (tab２回push)
ファイル内表示

mv |  | ファイルの移動、ファイル名変更

zip | file.zip file.md | ファイルの圧縮

unzip |  | ファイル解凍

touch |  | 指定したファイルを現在の時刻に書き換える
		ファイルがない場合には新規に作成する

less | ファイル名 | 表示しきれないファイルを分割して表示 , Enterで次の行に進む

find | pass -name ファイル名 | ファイルの検索を行う

cd | - | 異動前のディレクトリに戻る

grep | -irn 検索文字 pass | ファイル内に文字があるか検索

diff |  | 2つのファイルを比較する

set | -o | vi
viライクに変更

set | -o | emacs
emacsライクに変更

tar | zxvf | filename 
tarファイルを解凍する



## vim command
dd 
カーソル行を切り取り

yy 
カーソル行をコピー

v 
選択

y 
選択範囲をコピー

0 
行頭

$ 
行末

:0 
ファイル先頭

:$ 
ファイル末尾

:数字
指定行へ

/検索文字
文字を検索

:set number
行数表示

/検索文字
文字を検索

n or N
ヒット文字に移動

i
文字書き込みモード

esc
vimを起動した状態に戻る

:q!
保存せず終了

:wq!
保存して終了

数字 G
指定した行数へ移動

u (アンドゥ)
戻る

control r (リドゥ)
進む

control f
一ページ下に移動

control b
一ページ上へ移動

:入力後 control+p control+n
vimを開いた状態で検索履歴を調べる

control g
現在の行番号を表示

control v
矩形選択

gv
前回選択したいた範囲を選択

shift v
行を範囲選択


## terminal
ctrl a
行頭へ移動

ctrl e
行末へ移動

ctrl k
カーソルの後ろの文字を切り取る

ctrl y
カーソルの後ろの文字を貼付け

ctrl r
コマンドを履歴から検索する

control L
画面のクリア

↑↓
コマンド履歴を表示


## php snippeds

```php
<?php
echo "hogehoge";

```
## ruby hogehoge
test
