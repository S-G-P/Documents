## git command manual
maked by daisuke-awaji

しきくん

#### ローカルにリポジトリを作成

```
git init
```
＜使い方＞

$ cd <好きなディレクトリ>

$ git init

カレントディレクトリを Git リポジトリに変換します。このコマンドを実行するとカレントディレクトリに .git フォルダーが作成され、プロジェクトのバージョンの管理を開始することができます。

#### リモートリポジトリをクローン

```
git clone <repository>
```

リモートリポジトリをローカルにコピーします。

＜使い方＞

$ cd <好きなディレクトリ>

$ git clone https://github.com/daisuke-awaji/SGP.git


#### ローカルのブランチ一覧を表示

```
git branch
```
リポジトリのブランチ一覧を表示します。

＜使い方＞

$ git branch

`* master`

#### ローカルにブランチを作成

```
git checkout -b <branch>
```

「-b」オプションで指定したブランチ名で、新しいブランチを切る。

＜使い方＞

$ git checkout -b develop-issues-1

`Switched to a new branch 'develop-issues-1'`

$ git branch

`* FIX-001`

`  master`


#### ソースコードの差分を表示

```
git diff
```

ソースコードの差分を表示します。

＜使い方＞

#### 変更されたファイルの一覧を表示

```
git status
```

変更されたファイルの一覧を表示します。


＜使い方＞


#### ステージング

```
git add <file>
```

差分をステージングします。

＜使い方＞


#### コミット

```
git commit -m  "コメント内容"
```

ステージ環境のファイル差分をリポジトリにコミット（ローカル）

＜使い方＞

#### プッシュ

```
git push <repository> <branch>
```

ローカルリポジトリのコミット差分をリモートリポジトリに更新（プッシュ）する。

＜使い方＞
