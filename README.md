#GIT STUDY

## 基本
- git add コマンドで、リポジトリに変更情報を追加する
    - このことをステージングと言う
- git commit -m "はじめてのコミット"
- git push --tags origin master
  - コマンドで、リポジトリのインデックスに追加された変更情報にコメントを付けてコミットできる
- git push コマンドで、ローカルのコミットをリモートのリポジトリに反映させることができる

- git pull

##設定
- git config --global user.name "${あなたの名前}"
- git config --global user.email ${あなたのメールアドレス}
- git config --global core.editor "vim"
- git config -l コンフィグの確認

## その他
- git init　git リポジトリを作る
- git status 現在の変更情報の登録（ステージング）状況
- git log コミットログを確認
- git tag X.0


