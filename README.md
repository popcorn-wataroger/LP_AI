# IIDA AI BUILD — LP

飯田 祐基（株式会社イデオロギー CEO / AIエンジニア）のAI開発サービス向けランディングページ。

## 概要

「最短1日・10万円〜」をコンセプトに、AIを活用したサービス・ツール開発の受注を目的としたLP。
ビルドレス・静的HTMLで構成されており、Cloudflare Pages で配信。

## 構成

```
lp/
├── index.html        # メインLP（全セクション）
└── figure/
    ├── iida.jpg      # 飯田祐基プロフィール写真
    └── sns-video-generator-flow.png  # SNS投稿用動画生成アプリのフロー画像
```

## セクション構成

| セクション | 内容 |
|---|---|
| Hero | キャッチコピー + プロフィールカード |
| Ticker | 制作実績ワードのスクロールバナー |
| What I Can Build | SNS自動化・業務効率化・カメラAIの制作例一覧 |
| Works | 実際に制作したシステムのモックUI付きカード |
| Voice | 飯田のメッセージセクション |
| How It Works | 相談〜納品までの6ステップフロー |
| Pricing | 3プラン（10万〜 / 50万〜 / 100万〜） |
| FAQ | よくある質問 |
| Contact | 無料相談フォーム |

## Works カード一覧

- 切り抜き動画自動生成システム
- SNS自動投稿システム
- SNS投稿用動画生成アプリ
- こども寝返り検知アプリ
- 社内文書検索・FAQチャットボット
- レシート自動家計簿システム

## 技術スタック

- 素のHTML / CSS / JavaScript（ビルド不要）
- Google Fonts（Dela Gothic One / Noto Sans JP / Space Mono）
- Cloudflare Pages でホスティング

## デプロイ

`main` ブランチへの push で Cloudflare Pages が自動デプロイ。

```bash
git add .
git commit -m "変更内容"
git push origin main
```
