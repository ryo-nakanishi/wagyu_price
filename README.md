# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？

リモートリポジトリ・・・複数人で共有し利用するためにネット上でリポジトリを管理します。
ローカルリポジトリ・・・ユーザが個人で利用するために自分のパソコン内でリポジトリを管理します。

## プッシュとマージの違いは何でしょうか？

プッシュはローカルリポジトリで編集した内容（ブランチ）をリモートリポジトリに反映させることで、マージはリモート、ローカルの各リポジトリ内で編集した内容（ブランチ）を他ブランチに反映させることです。

## コミットとプッシュの違い

コミットとは対象のファイルをメッセージと共に変更履歴を保存することで、プッシュは変更した内容をローカルリポジトリからリモートリポジトリに反映させることです。

## コミットのメッセージはどのように書いてあげるのが最適でしょうか？

誰が見ても理解しやすいメッセージを書くことを心掛ける。
また、プロジェクトによって書き方が決まっていたらその書き方に合わせる。

## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？

ローカルでマージするフローはローカルの幹ブランチから直接リモートの幹ブランチに情報を反映するのに対して、プルリクエストでマージするフローはマージする前にチームリーダー等がレビューを行うことで事前に編集ミスやバグを防ぐことができます。

## コンフリクトを起こしてしまった場合、どう対処すべきですか？

どの情報を反映させるか確認し、編集した箇所のソースコードの差異を確認して修正した後にコミットします。