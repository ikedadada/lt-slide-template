# YAGNI の原則 - LT スライド

Marp を使用した YAGNI 原則についてのライトニングトーク

## ディレクトリ構成

```
├── themes/                    # カスタムテーマ
│   └── default.css           # デフォルトテーマ
├── slide.md                  # メインスライド
├── output/                   # 生成されたファイル
├── images/                   # 画像素材
├── package.json              # npm設定
└── README.md
```

## 使用方法

### 1. 依存関係のインストール

```bash
npm install
```

### 2. スライドの操作

#### スライドのプレビュー

```bash
npm run preview
```

#### PDF と HTML の生成

```bash
npm run build
```

#### ローカルサーバーで確認

```bash
npm run serve
```

## マルチリポ構成について

1. 新しいリポジトリを作成
2. この構成をテンプレートとして使用
3. `slide.md` の内容を新しいトピック用に変更

**例：新しいリポジトリ「ddd-principles-lt」**

```bash
# 新しいリポジトリを作成
git clone this-repo ddd-principles-lt
cd ddd-principles-lt
# slide.md を DDD原則の内容に変更
npm run preview
```

## テーマのカスタマイズ

`themes/` ディレクトリで CSS テーマを管理

- 再利用可能なコンポーネント
- ブランドカラーの統一
- レスポンシブ対応
