# POTI-board改
phpお絵かき掲示板スクリプトPOTI-boardを改良していくプロジェクトです。

Punyu NetのSakaQさん承諾のもと進めております。

Punyu Net
http://www.punyu.net/php

**Flashやhtml5のお絵描きサイトはいっぱいあるんだけど、そうじゃないんだ。  
おじさんは昔のjavaアプレットそっくりの環境が欲しいんだ。**

というPaintBBSNEO https://github.com/funige/neo/ を応援するためにまずはphp7に対応させました！

potiboard.zip がスクリプト一式、5u.zip/5r.zip が拙作テンプレート一式です。  
ディレクトリ内に未圧縮ソースが入っています。掲示板設置法等は中のテキストファイルを読んで下さい。  

## サンプル/サポート掲示板

サンプルとして<a href="https://sakots.red/nee/">「nee」</a><a href="https://sakots.red/5u/">「5u」</a><a href="https://sakots.red/5r/">「5r」</a>をオープンしました。  
質問や動作確認にご利用ください。

## 履歴

[2018/01/30] v1.32.12 lot.180130  
【仕様変更】  
　・オートリンクで相手のアクセスログにURLが残らないようにした (by さとぴあ)  
　・拒絶する文字列の指定で大文字小文字の区別をしないように変更 (by さとぴあ)  
　・管理画面の画像へのリンクがおかしかったのを修正 (by さとぴあ)  
  
[2018/01/24] v1.32.11 lot.180124  
【仕様変更】  
　・NEOを使う/使わない選択式のスキンに対応  
　・readme整理  

[2018/01/22] v1.32.10 lot.180122  
【仕様改善】  
　・phpの些細なエラーを減らした  
　・githubに公開  

[2018/01/16] v1.32.5 lot.180116  
【仕様変更】  
　・オートリンク時のURLにリファラを送信しない、またそれにともなう脆弱性修正  

[2018/01/15] v1.32.4 lot.180115  
【障害対応】  
　・コメント無しでイラストのみ投稿した場合に設定問わず弾かれる問題を修正  
【仕様追加】  
　・メール通知クラスphp7対応版を同梱  

[2018/01/13] v1.32.3 lot.180113  
【障害対応】  
　・「拒絶する文字列」の設定が効かない問題を修正  
【仕様変更】  
　・バージョン表記の仕方を変更  

[2018/01/12] v1.32 lot.050602b  
【障害対応】  
★picpost.php  
　・php7環境で8kB以上の画像が送信できなくなっていた問題を修正  

[2018/01/11] v1.32 lot.050602a  
【仕様変更】  
　・php7対応  

## テンプレートneeの履歴

[2008/04/18]  
・お絵かきレス時の表示幅を変更  
  
※アップデートは nee_main.html nee_paint.html nee_main.css template_ini.php 上書き  

[2018/04/16]  
・コードの記述ミスを修正  
  
※アップデートはnee_main.html php nee_paint.html nee_main.css template_ini.上書き  
  
[2018/04/11]  
・公開  

## テンプレート5u/5rの履歴

[2018/01/30]  
・(5u)レスが長いときでも変な位置で改行されないように修正  
  
※アップデートは n5u_main.css template_ini.php 上書き  
  
[2018/01/24]  
・外部メタファイル追加  

※5uアップデートは n5u_main.html n5u_catalog.html template_ini.php 上書き  
　meta.php追加  
　5r新規公開

[2018/01/23]  
・コメントスパム対策  

※アップデートは n5u_main.html template_ini.php 上書き  

[2018/01/22]  
・githubに公開  
・template_ini.phpの最適化  

※アップデートは template_ini.php 上書き  

[2018/01/16]  
・外部URLからwindow.openerで掲示板を操作できる可能性がある問題を修正  

※アップデートは n5u_main.html template_ini.php 上書き  

[2018/01/13]  
・URL入力欄復活  
・レスフォーム表示の場合に省略されたレスが読めなかった問題修正  

※アップデートは n5u_main.html n5u_other.html template_ini.php 上書き  

[2018/01/12]  
・お絵描き画面のUI改善  
・NEOを1.2.3にアップデート  

※アップデートは n5u_paint.html n5u_main.css template_ini.php PaingBBS.js PaingBBS.css 上書き  

[2018/01/11]  
・ブラウザにhtmlファイルをキャッシュさせないようにした  

※アップデートは n5u_main.html n5u_catalog.html template_ini.php 上書き  

[2018/01/10]  
・URL変更、また管理のしやすさの観点からスキンのファイル名を変更  

※アップデートは全て上書き  
