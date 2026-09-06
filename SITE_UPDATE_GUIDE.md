# mirror lab. サイト更新メモ

## 今回の確認用データ
- GitHub: ar2580y-cloud/mirror-lab-portfolio
- 確認用ブランチ: draft/mirror-lab-refresh-20260906
- 新サイト: index.html（CSS・プロフィール画像を含む単独HTML）
- 現在公開中の旧ページ: main / portfolio.html
- 公開ページ・プレーリーカード・ペライチ契約は未変更。

## 変更したこと
サービス紹介と実績を1ページに統合。オンライン秘書の受託を主役にせず、業務整理・AI活用・研修と定着への伴走を中心に再構成。既存イラスト、予約URL、GoogleフォームURLを再利用。

## 内容の確認が必要な点
既存portfolio.htmlの業種別件数（社労士3社、税理士2社など）は過去の説明と相違があるため新稿では件数を掲載していない。「登壇70本」も教材動画の納品数との区別が必要なため未掲載。ペライチの数値入り事例は裏付けを確認していないため転記していない。料金と「無料」表記は、現在の提供条件が確定していないため掲載していない。
予約枠の現在の利用可否、フォームの回答受付・通知先は公開前に確認すること。今回は既存URLの転記まで。

## 次回の編集
このリポジトリの確認用ブランチにあるindex.htmlを指定し、変更したい文章・実績・デザインを伝える。元のClaudeの会話は不要。mainや旧portfolio.htmlを直接上書きしない。

## 公開前
1. あやさんが初稿を確認し、公開内容を承認。
2. 追加費用0円の公開先を確定。独自ドメインを新規購入しない。GitHub Pagesには商取引を主目的とするサイトの利用制限があるため、事業サイトの移行先はCloudflare Pages等の無料枠も含めて確認する。
3. 予約・フォームの受付、スマホでの表示と動作を確認。
4. 公開時にrobotsのnoindex,nofollowを解除。公開先決定後にcanonical等を設定。
5. プレーリーカードのリンクを新URLへ変更（本人のOK後）。ログインが必要なら本人に依頼。
6. 外部からサイトと相談先を開けることを確認してから、ペライチの契約更新・解約を判断。既存ドメインやメールへの影響も確認。

## 検証
HTMLのID重複、ページ内リンクの参照先、画像の埋め込み、H1を1つに限定、確認用noindexを確認。ブラウザによる実表示検証は未実施。

## 参照元
- https://ar2580y-cloud.github.io/mirror-lab-portfolio/portfolio.html
- https://401ii.hp.peraichi.com/consulting_site_p1_1
- https://docs.github.com/en/pages/getting-started-with-github-pages/github-pages-limits
- https://developers.cloudflare.com/pages/functions/pricing/
