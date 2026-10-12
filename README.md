# fukurou-care

「ふくろうのこころ相談室」サイトです。Xサーバーで公開中の最新版を、MacとGitHubで管理します。

## 保存場所

- Mac：デスクトップ `muneimunei/GPTS/fukurou-care`
- GitHub：https://github.com/muneimunei-arch/fukurou-care
- Xサーバー：https://muneiserver.xsrv.jp/fukurou-care/

`public` が公開用ファイルです。入力内容は公開ページ内だけで処理され、外部へ送信されません。Xサーバーの非公開領域にあるAPIキーは現在の公開ページでは使用しておらず、GitHubには保存しません。

## 日常の使い方

1. 作業前に `01_GitHubから更新.command` を実行します。
2. `public` 内を編集します。
3. 作業後に `02_GitHubへ保存.command` を実行します。
4. 必要に応じて `03_Xサーバーをバックアップ.command` を実行します。

バックアップは `muneimunei/GPTS/fukurou-care-非公開バックアップ` に保存され、GitHubには入りません。Xサーバーへの公開更新は、別途アップロードが必要です。
