### タスクリスト

擬似的な Twitter 風 Web アプリ（タイムラインへの投稿・閲覧ができる簡易 SNS）を対象とした開発とドキュメント作成の作業を整理する。

- [ ] 開発者向けドキュメントの作業
  - [x] 対象とするシステムの決定（擬似 Twitter） :thinking:
  - [ ] データ構造の決定（ツイート配列の構造など） :thinking:
  - [ ] ページ構造の検討（`/` と `/timeline` など） :thinking:
  - [ ] ページ遷移の検討 :thinking:
  - [ ] HTTPメソッドとリソース名の決定（`GET /timeline` など）
  - [ ] ページ遷移図の作成 :writing_hand:
  - [ ] ページ構造の決定（ワイヤーフレームの確定）
  - [ ] ドキュメントの構成の検討 :thinking:
  - [ ] 概要（システム全体の説明） :writing_hand:
  - [ ] HTTPメソッドとリソース名一覧 :writing_hand:
  - [ ] データ構造（ツイートオブジェクト・配列） :writing_hand:
  - [ ] リソース名ごとの機能の詳細 :writing_hand:

- [ ] 管理者向けドキュメントの作業
  - [ ] インストールから起動までの手順確認 :computer:
  - [ ] インストール方法（Node.js の導入・依存パッケージのインストール） :writing_hand:
  - [ ] 起動方法（`npm start` など） :writing_hand:
  - [ ] 起動できない場合の対処（ポート競合・依存関係エラーなど） :writing_hand:
  - [ ] 終了方法 :writing_hand:
  - [ ] 分かっている不具合・制限事項 :writing_hand:

- [ ] 利用者向けドキュメントの作業
  - [ ] 構成の検討 :thinking:
  - [ ] スクリーンショットの保存と整理（トップ・タイムライン・投稿フォームなど） :computer:
  - [ ] 概要（ユーザーができること） :writing_hand:
  - [ ] 使用できる機能（投稿・閲覧など） :writing_hand:
  - [ ] 起動画面の説明 :writing_hand:
  - [ ] タイムライン表示の説明 :writing_hand:
  - [ ] ツイート投稿の手順 :writing_hand:
  - [ ] （任意）ツイート削除やエラー表示の説明 :writing_hand:

- [ ] システム実装とテスト
  - [ ] ルーティング実装（`/`, `/timeline`） :computer:
  - [ ] テンプレート実装（`index.ejs`, `timeline.ejs`） :computer:
  - [ ] 投稿処理・バリデーションの実装 :computer:
  - [ ] タイムライン表示処理の実装 :computer:
  - [ ] 手動テスト（複数ブラウザからの投稿確認など） :computer:

- [ ] 提出準備
  - [ ] コードとドキュメントの最終確認 :thinking:
  - [ ] README の作成・更新 :writing_hand:
  - [ ] 提出用リポジトリ／アーカイブの作成 :computer:
  - [ ] 提出 :tada: