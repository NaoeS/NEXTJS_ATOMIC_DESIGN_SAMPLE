# Next.js + アトミックデザインのサンプル
- 引用元のサンプルプロジェクト
  * https://github.com/vercel/next.js/tree/master/examples/blog-starter

## /components/atoms
- 機能の最小単位を保つコンポーネント群
  * HTML タグ毎に分割した要素ではない
- 再利用性が高く汎用性を備えた抽象的な要素
  * 例: <button> + CSS + 任意の処理を実行する機構
- アプリケーションデザインの統一性を担保するための層であることも意識する

## /components/molecules
- atoms を組み合わせて具体的な役割を持たせたコンポーネント群
  * 機能が組み合わさることで業務となる

## /components/organisms
- atoms, molecules を組み合わせたコンポーネント群
  * organisms 自体を内包する場合もある（アイテムとリストの関係等）
- 独立して存在が可能

## /pages
- Next.js の pages の概念と同様
- コンポーネントを配置して各ページを作成する
