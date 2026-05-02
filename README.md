# 糸島旬送和食 喜友 公式HP - アップロード手順

## 重要：アップロード手順（GitHub Pages）

### Step 1: ZIPを解凍する
Windowsの場合: 右クリック→「すべて展開」
Macの場合: ダブルクリック

### Step 2: GitHubリポジトリを開いて既存ファイルを削除

### Step 3: 「Add file」→「Upload files」
解凍してできた**全ファイル**と**imagesフォルダ**を一緒にドラッグ＆ドロップ

⚠️ **最重要：imagesフォルダ「ごと」アップロードする**
GitHubのドラッグ＆ドロップは、フォルダもそのまま受け付けます。
個別にHTMLだけ選択しないこと。

### Step 4: Commit changes

### Step 5: ブラウザキャッシュをクリアして確認
- Windows: Ctrl + Shift + R
- Mac: Cmd + Shift + R
- または、シークレットモード（プライベートブラウジング）で開く

---

## ファイル構成

```
ルート/
├── index.html              ← TOPページ
├── kiyu_kodawari.html      ← こだわり
├── kiyu_menu.html          ← 夜会席
├── kiyu_hiru.html          ← 昼会席（ランチタブ含む）
├── kiyu_lunch.html         ← ランチ独立ページ
├── kiyu_drink.html         ← ドリンク
├── kiyu_taidai.html        ← 夫婦鯛お祝い
├── kiyu_access.html        ← アクセス
├── lp-settai.html          ← 接待特集
├── lp-enkai.html           ← 宴会特集
├── lp-kaowase.html         ← 顔合わせ特集
├── lp-nihonshu.html        ← 日本酒特集
├── lp-lunch-taicha.html    ← ランチ・鯛茶漬け特集
├── column-settai-eraikata.html  ← 記事：接待店選び
├── column-kaowase-mistake.html  ← 記事：顔合わせの条件
├── column-nomihoudai.html       ← 記事：飲み放題問題
├── robots.txt              ← SEO（クローラー指示）
├── sitemap.xml             ← SEO（全16URLマップ）
├── favicon.svg             ← ブラウザアイコン
├── og-image.jpg            ← SNS共有時の画像
└── images/                 ← 画像フォルダ（25枚）
    ├── img_xxxx.jpg
    └── ...
```

---

## トラブルシューティング

### 画像が表示されない場合
1. GitHub上で `images/` フォルダが存在することを確認
2. `images/img_xxxx.jpg` のように画像ファイルが揃っているか確認
3. ブラウザキャッシュをクリア（Ctrl+Shift+R / Cmd+Shift+R）

### ページが見つからない場合
すべての .html ファイルがリポジトリの**ルート直下**（フォルダの中ではない）にあることを確認

### 反映が遅い場合
GitHub Pagesは最大10分かかることがあります。
