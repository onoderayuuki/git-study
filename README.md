
## GIT STUDY
### 基本
- git add コマンドで、リポジトリに変更情報（ステージング）を追加する
    - git add .  カレントディレクトリの追加
- git commit -m "はじめてのコミット"
- git push --tags origin master
  - コマンドで、リポジトリのインデックスに追加された変更情報にコメントを付けてコミットできる
- git push origin{リモートリポジトリ} master｛ブランチ名｝コマンドで、ローカルのコミットをリモートのリポジトリに反映させることができる
- git pull
### 設定
- git config --global user.name "${あなたの名前}"
- git config --global user.email ${あなたのメールアドレス}
- git config --global core.editor "vim"
- git config -l コンフィグの確認
### その他
- git init　git リポジトリを作る
- git status 現在の変更情報の登録（ステージング）状況
- git log コミットログを確認
- git tag X.0
### ISSUE
 - #1    イシュー識別ID　リンクにもなるよ 
 - ${commit_hash}　コミットの識別ID 
