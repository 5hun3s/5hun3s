- 👋 Hi, I’m @5hun3s
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
- 📝 Memo
# 学んだことなど
- [学んだことなど](#学んだことなど)
  - [githubアカウントの切り替え](#githubアカウントの切り替え)
  - [githubコミットのメッセージ書き方](#githubコミットのメッセージ書き方)
  - [githubプルリクメッセージ書き方](#githubプルリクメッセージ書き方)


## githubアカウントの切り替え
- [参考](https://almonta2021blog.com/github-switch-multi-accounts/)

## githubコミットのメッセージ書き方
- テンプレ
    ```
    1行目：変更内容の要約（タイトル、概要）
    2行目 ：空行
    3行目以降：変更した理由（内容、詳細）
    ```
- 一行目の種類
	•	fix：バグ修正
	•	hotfix：クリティカルなバグ修正
	•	add：新規（ファイル）機能追加
	•	update：機能修正（バグではない）
	•	change：仕様変更
	•	clean：整理（リファクタリング等）
	•	disable：無効化（コメントアウト等）
	•	remove：削除（ファイル）
	•	upgrade：バージョンアップ
	•	revert：変更取り消し
- [参考](https://qiita.com/itosho/items/9565c6ad2ffc24c09364)

## githubプルリクメッセージ書き方
- テンプレ
    ```
    このプルリクエストでは、ユーザー認証機能を新たに追加しました。ユーザーはメールアドレスとパスワードでログインできるようになります。

    変更点:
    - `auth.py`: 認証ロジックを含む新しいファイルを追加しました。
    - `login.html`: 新しいログインフォームを追加しました。
    - `models.py`: Userモデルにパスワードフィールドを追加しました。

    影響範囲:
    - 既存のユーザーモデルに新しいフィールドが追加されているため、データベースのマイグレーションが必要です。

    テスト:
    - 新規登録とログインのユニットテストを追加し、全てパスしています。
    - 手動でのブラウザテストを行い、フォームのバリデーションと認証フローが期待通りに動作することを確認しました。

    考慮事項:
    - パスワードはデータベースに平文で保存していません。安全なハッシュ関数を使用して暗号化しています。

    関連資料/リンク:
    - 関連リンク
    ```






<!---- [](#)
5hun3s/5hun3s is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
