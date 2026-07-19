# Subscription Management App

サブスク管理アプリのプロトタイプです。

## 機能

- 📱 ホーム画面：月間支出と今月のサービス一覧表示
- 📅 カレンダー：更新予定日の確認
- 📊 分析：カテゴリ別の支出管理
- ⚙️ 設定：プロフィール管理

## セットアップ

```bash
# 依存関係のインストール
npm install

# 開発サーバーの起動
npm run dev
```

開発サーバーは `http://localhost:3000` で起動します。

## 技術スタック

- Next.js 14
- React 18
- TypeScript
- Tailwind CSS
- Recharts (グラフ表示)

## プロジェクト構成

```
subscription-manager/
├── app/              # Next.js App Router
├── components/       # React コンポーネント
├── public/          # 静的ファイル
└── styles/          # グローバルスタイル
```
