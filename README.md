# linux_practice1 で使ったコマンドメモ

- `mkdir -p` : ディレクトリを階層ごと作成  
  例）`mkdir -p ~/server_lesson/linux_practice1/public`

- `cp -p` : 権限/時刻を保持してファイルコピー  
  例）`cp -p public/index.php public/index_bk.php`

- `cp -R` : ディレクトリを配下ごとコピー  
  例）`cp -R public tmp`

- `rm -f` : ファイル削除（存在しなくてもエラーにしない）  
  例）`rm -f tmp/index_bk.php`

- `ls -l` : 詳細表示で中身確認  
  例）`ls -l ~/server_lesson/linux_practice1/public`

- `diff -u` : 2つのファイル差分を見る  
  例）`diff -u public/index_bk.php public/index.php`
