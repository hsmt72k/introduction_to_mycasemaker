<img src="./images/mycase_cover.png" />

<div align="center">
  <div>
    <img src="https://img.shields.io/badge/-Next_JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=000000" alt="nextdotjs" />
    <img src="https://img.shields.io/badge/Vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white" />
    <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6"   alt="typescript" />
    <img src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=fff" />
    <img src="https://img.shields.io/badge/kinde-000?style=for-the-badge&logoColor=fff" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?logoColor=white&style=for-the-badge&logo=tailwindcss&color=06B6D4"   alt="tailwindcss" />
    <img src="https://img.shields.io/badge/shadcn%2Fui-000?style=for-the-badge&logo=shadcnui&logoColor=fff" />
    <img src="https://img.shields.io/badge/Headless%20UI-66E3FF.svg?style=for-the-badge&logo=Headless-UI&logoColor=000" />
    <img src="https://img.shields.io/badge/Framer-0055FF.svg?style=for-the-badge&logo=Framer&logoColor=fff" />
    <img src="https://img.shields.io/badge/Prisma-2D3748.svg?style=for-the-badge&logo=Prisma&logoColor=fff" />
    <img src="https://img.shields.io/badge/Zod-3E67B1.svg?style=for-the-badge&logo=Zod&logoColor=fff" />
    <img src="https://img.shields.io/badge/Resend-000000.svg?style=for-the-badge&logo=Resend&logoColor=fff" />
    <img src="https://img.shields.io/badge/uploadthing-E41321.svg?style=for-the-badge&logoColor=fff" />
    <img src="https://img.shields.io/badge/Stripe-008CDD.svg?style=for-the-badge&logo=Stripe&logoColor=fff" />
  </div>

  <h3 align="center">A Modern Store for Custom High-Quality Phone Cases</h3>

  <div align="center">
    高品質なオリジナル iPhone ケースを数秒で作成
  </div>
</div>

## 📋 <a name="table">Table of Contents</a>

1. 🤖 [はじめに](#intro)
2. 🔗 [URL](#url)
3. 🔋 [アプリの機能](#feature)
4. 🚀 [アプリの利用サンプル](#example)
5. 🤸 [終わりに](#outro)

## <a name="intro">🤖 はじめに</a>

お気に入りの画像をアップロードして、オリジナルの iPhone ケースを作成・注文できるサービス、myCaseMaker のご紹介。

## <a name="url">🔗 URL</a>

myCaseMaker | Make Custom High-Quality Phone Cases in Seconds  
https://mycasemaker.vercel.app

## <a name="feature">🔋 アプリの機能</a>

🛠️ Complete shop built from scratch in Next.js 14

🎨 Custom artworks made by a professional illustrator

### 💻 サービス内容を伝える美しいランディングページ

### 🔑 ユーザ認証システム

メールアドレスまたは Google アカウントによるユーザ認証

### 💳 システム管理者専用ページで注文管理

メールアドレス、または Google アカウントのログインによりユーザ認証を保護

### 🖥️ ドラッグ＆ドロップによるファイルアップロード

### 🛍️ 顧客は貴社から直接購入できる

### 🌟 シンプルでモダンな UX/UI 設計

### 🛒 完全カスタムの携帯ケース設定ツール

### ✉️ 購入後にユーザにお礼メールを自動送信

### ✅ どんなデバイスでも崩れず美しく表示するレスポンシブレイアウト設計

### ⌨️ 100% TypeScript で作られた堅牢で保守性の高いソースコード

🎁 ...much more

## <a name="example">🚀 アプリの利用サンプル</a>

1. [認証機能](#authentication)
   1. [アカウント登録](#account-register)
   2. [ログイン](#login)
      1. [通常ユーザでのログイン](#login-with-normal-account)
      2. [管理者アカウントでのログイン](#login-with-admin-account)
   3. [ログアウト](#logout)
2. [ランディングページ](#landing-page)
   1. [ヒーローイメージ](#hero-image)
   2. [テスティモニアル（お客様の声）](#testimonials)
   3. [ショーケースアニメーション](#animation-of-show-case)
   4. [カスタマイズイメージ](#image-of-customization)
3. [アップロードページ](#uploading-page)
4. [カスタマイジングページ](#design-configurator)
   1. [画像の大きさ調整](#image-size-adjustment)
   2. [画像の位置調整](#image-positioning)
   3. [オプション選択](#select-options)
      1. [色の選択](#color-options)
      2. [iPhone モデルの選択](#model-options)
      3. [素材の選択](#material-options)
      4. [仕上げ加工の選択](#texture-options)
   4. [「続ける」ボタン](#continue-button)
   5. [ログインモーダル](#login-modal)
5. [内容確認ページ](#preview-page)
6. [決済ページ](#payment-page)
7. [Thank you ページ](#thank-you-page)
8. [Thank you メール](#thank-you-mail)
9. [システム管理者専用の注文管理ページ](#dashboard)

### <a name="authentication">1. 認証機能</a>

#### <a name="account_register">1-1. アカウント登録</a>

氏名とメールアドレス、または Google アカウントを使ってアカウント登録することができる。

メールアドレスでアカウント登録した場合は、登録したメールアドレスあてに確認コードがメールで送信される。確認コードを入力して、「続ける」ボタンをクリックすることでアカウント登録が完了する。

<img src="./images/mycase_account_register.webp" width="480px" />

#### <a name="login">1-2. ログイン</a>

##### <a name="login-with-normal-account">1-2-1. 通常ユーザでのログイン</a>

アカウント登録したメールアドレス、または Google アカウントを使ってログインすることができる。

ログインする前は、サイトヘッダにあるナビゲーションバーに「アカウント登録」「ログイン」のリンクが表示されていたが、ログインをすると表示されるリンクは「ログアウト」に変わる。

<img src="./images/mycase_login.webp" width="480px" />

##### <a name="login-with-admin-account">1-2-2. 管理者アカウントでのログイン</a>

管理者アカウントでログインすると、ナビゲーションバーに「ログアウト」リンクのほかに、「ダッシュボード ✨」リンクも表示される。

「ダッシュボード ✨」リンクをクリックすると、システム管理者専用ページに遷移する。

<img src="./images/mycase_login_with_admin_account.webp" width="480px" />

#### <a name="logout">1-3. ログアウト</a>

ヘッダナビゲーションバーの「ログアウト」リンクをクリックすると、ログアウトされる。

ログアウトすると、ランディングページ（入口のページ）に遷移する。

<img src="./images/mycase_logout.webp" width="480px" />

### <a name="landing-page">2. ランディングページ</a>

サイトの入り口として、ルートパス（https://mycasemaker.vercel.app）にアクセスすると、ランディングページが表示される。

サイトへの訪問者が最初にアクセスするページのことを通称、ランディングページ（LP）と呼んでいる。訪問者が最初に着地（landing）するページであることから、ランディングページと呼ばれる。

ランディングページには、ログインユーザも、未ログインユーザもアクセスすることができる。

#### <a name="hero-image">2-1. ヒーローイメージ</a>

ヒーローイメージとは、ウェブサイトのトップページの先頭に目立つように表示される、サイズの大きい、特徴的な画像のこと。

サイトのイメージとして、ユーザに強い印象を与えることを目的として、ヒーローイメージを表示させている。

このサイトでは、デバイスサイズが小さい（表示ブラウザの横幅が狭い）場合は、ヒーローイメージがトップのメインメッセージエリアの下に回り込むようにレイアウトが変化する。

<img src="./images/mycase_hero_image.webp" width="480px" />
