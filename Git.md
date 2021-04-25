## Git
2021.04.11
<br><br>
- Step1.コードを変更する
- Step2.コードの変更を一旦記録する
- Step3.コードの変更を共有する

1. Gitを使う準備をする<br>
「Initialized empty Git repository in...」と表示されたら準備OK
```
$ git init
```
2. ファイルの変更を一旦記録しておく
```
$ git add ファイル名
```
3. ファイルの変更を確定させる
```
$ git commit -m "コミットメッセージ"
//コミットメッセージ例："Create index.html"
```
4. リモート(リモートリポジトリ）を登録する
```
$ git remote add リモートリポジトリの名前 "URL"
// リモートリポジトリを登録する際は名前をつける必要があり、一般的に origin とすることが多い
```
5. リモートリポジトリにファイルをアップロードする
```
$ git push origin main
//origin: git remote addの時に付けたリモートリポジトリ名
//mina: ファイルをあげたいブランチの名前
```
6. ファイルをリモートからダウンロードする
```
$ git pull origin main
```
7. 変更したファイルを把握する
```
$ git status
//変更があったファイルが赤色で表示される
```
8. 変更内容を把握する
```
$ git diff
// 追加された部分が緑色で表示される
// 変更前のコードが赤色、変更後が緑色で表示される
```
9. addしたファイルを確認する
```
$ git status
// addされたファイルが緑色、まだaddされていないファイルが赤色で表示される
```
10. コミット履歴を表示する
```
$ git log
//コミットメッセージが見れる
```
11. コミットの変更内容を見る
```
$ git log -p
//上下キーで表示範囲を変更でき、Qキーを押して終了する
```
12. 設定の一覧を見る
```
$ git config　--list
// global listにするとgrobalの登録情報を見れる
```
13. 設定ファイルに情報を登録する
```
$ git config
// git config --global user.name "ユーザー名"
// git config --global user.email "アドレス"
```
14. 




