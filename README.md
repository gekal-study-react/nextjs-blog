# Learn Next.js Demo

## What's Next.js

Next.js is a popular React-based framework designed for building modern web applications.

## Create a new project

```shell
npx create-next-app@latest nextjs-blog --use-npm --example "https://github.com/vercel/next-learn/tree/main/basics/learn-starter"
```

```text
  npm run dev
    Starts the development server.

  npm run build
    Builds the app for production.

  npm start
    Runs the built app in production mode.

We suggest that you begin by typing:

  cd nextjs-blog
  npm run dev
```

## プロジェクト構成例

```
my-nextjs-app/
├── public/             // 静的ファイル（画像、フォントなど）を格納
├── src/                // 主なソースコードを含むディレクトリ
│   ├── pages/          // ページコンポーネント（Next.jsの`pages`ディレクトリ）
│   ├── components/     // 再利用可能なReactコンポーネント
│   ├── styles/         // グローバルCSSやSassファイル
│   ├── utils/          // ユーティリティ関数やヘルパーモジュール
│   ├── hooks/          // カスタムReactフック
│   ├── contexts/       // React Context用プロバイダ
│   ├── services/       // API呼び出しまたはその他の外部サービスとの統合
│   └── types/          // TypeScriptの型定義（TypeScriptを使用している場合）
├── .env.local          // ローカル環境用の環境変数
├── .gitignore          // Gitで無視するファイルとディレクトリ
├── next.config.js      // Next.jsのカスタム設定
├── package.json        // プロジェクトの依存関係とスクリプト
└── tsconfig.json       // TypeScript構成ファイル（TypeScriptを使用している場合）
```

## Note

1. [Create a Next.js App](https://nextjs.org/learn-pages-router/basics/create-nextjs-app)
2. [Learn Next.js](https://nextjs.org/learn).
