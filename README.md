この [Next.js](https://nextjs.org/) はブートストラップしたプロジェクトです  [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## はじめに

まず、開発用サーバーを起動します:

```bash
npm run dev
# or
yarn dev
```

[http://localhost:3000](http://localhost:3000) をブラウザで表示し、結果を確認することができます。

`pages/index.js`を修正することで、ページの編集を開始することができます。  ファイルを編集すると、ページが自動で更新されます。

[API routes](https://nextjs.org/docs/api-routes/introduction) は、 [http://localhost:3000/api/hello](http://localhost:3000/api/hello) でアクセスすることができます。 このエンドポイントは `pages/api/hello.js` で編集することができます。

この `pages/api` ディレクトリは `/api/*` にマップされます。 このディレクトリのファイルは React ページではなく、 [API routes](https://nextjs.org/docs/api-routes/introduction) として扱われる。

## もっと詳しく

Next.jsの詳細については、以下のリソースを参照してください。:

- [Next.js ドキュメント](https://nextjs.org/docs) - Next.jsの機能とAPIについて学びます。
- [Learn Next.js](https://nextjs.org/learn) - インタラクティブなNext.jsチュートリアル。

[the Next.js GitHub repository](https://github.com/vercel/next.js/) をチェックアウトしてみてください。 - あなたのフィードバックや貢献を歓迎します!

## Vercelにデプロイする

Next.jsのアプリをデプロイする最も簡単な方法は、Next.jsの制作者が提供する [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) を利用することです。

詳しくは、 [Next.js deployment ドキュメント](https://nextjs.org/docs/deployment) をご覧ください。
