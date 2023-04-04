# TODO管理アプリケーション仕様書

### 実行手順

- PCにNode.jsをインストールしてください
  - └node.jsのバージョン10.0.0以降をインストールしてください
    - └最新のバージョンはこちらhttps://nodejs.org/ja/download
- プロジェクトディレクトリ内で任意のコンソールを起動してください（ディレクトリ名：warc_pj）
  - コンソールで下記コマンド入力しツールを起動します
    - node app.js
- 下記画面が立ち上がったら、1~7の番号の中から操作方法を選び実行してください
```
---【 TODO管理アプリケーション 】-----------------------------------------------------
1. タスク追加
2. タスク一覧
3. タスク条件検索
4. 詳細
5. 更新
6. 削除
7. 終了
--1~7の番号の中から操作方法をお選びください-- 選択項目:
```

### テスト項目
- タイトル、詳細、締切日、優先度が正しく入力された場合、タスクが追加されること
- タスク一覧を表示すること
- タスク一覧を表示する際に、締切日が近い順に並び替えられること
- タスク一覧を表示する際に、優先度が高い順に並び替えられること
- タスク詳細が表示されること
- タスクが更新されること
- タスクが削除されること