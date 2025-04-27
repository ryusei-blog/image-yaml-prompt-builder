# 🖼️ 画像生成 YAML プロンプトビルダー
[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Last Commit](https://img.shields.io/github/last-commit/ryusei-blog/image-yaml-prompt-builder.svg)](../../commits/main)
[![Stars](https://img.shields.io/github/stars/ryusei-blog/image-yaml-prompt-builder?style=social)](../../stargazers)

**画像生成 AI 向け YAML プロンプトを手軽に作れる Web ツール** — **HTML 版がメイン**、*WordPress 用 PHP テンプレート* はオプションで同梱。

---

## ✨ 主な特徴
- **YAML 特化**: 階層構造で AI が解釈しやすいプロンプトを生成  
- **動的セクション追加**: ボタンで項目を追加・並べ替え  
- **2 カラム UI**: 左入力・右プレビューで直感的  
- **モバイル最適化**: スマホでも快適に操作  
- **広告枠**: 右下にウィジェット用スペースを用意  

---

## 🚀 クイックスタート（HTML）

**`index.html` を開くだけ** で動きます。サーバーやビルドは不要です。

```bash
git clone https://github.com/ryusei-blog/image-yaml-prompt-builder.git
cd image-yaml-prompt-builder
open index.html
```

ほぼ全てのモダンブラウザで動作します。  
GitHub Pages や Netlify、Vercel へアップロードすればオンライン公開も簡単です。

### 🌐 ライブデモ  
https://ryusei-blog.github.io/image-yaml-prompt-builder/

---

## 🖥️ WordPress 連携（任意）

WordPress テーマに組み込みたい場合はこちら。

```bash
# テーマディレクトリ（例: /wp-content/themes/affinger/）で実行
mkdir template
cp wp-template/image-yaml-prompt-builder.php template/

# WP 管理画面で固定ページを作成し、テンプレートにこの PHP を指定
```

PHP 版は同じ HTML/JS をラッピングしているだけなので、ヘッダー・フッター・SEO プラグインとの併用が可能です。

---

## 📸 画面イメージ
| UI 全体 | YAML プレビュー | モバイル表示 |
|---------|----------------|--------------|
| ![full-ui](https://ryusei-komada.com/wp-content/uploads/2025/04/4959873bc5667520cb27ac817a33504a.webp) | ![yaml](https://ryusei-komada.com/wp-content/uploads/2025/04/0b8d9f2c0f5369e0ff8a982deec41103.webp) | ![mobile](https://ryusei-komada.com/wp-content/uploads/2025/04/c98615228f9320929b3c62bbd084b909.webp) |

追加スクリーンショット  
- セクション追加ボタン  
  ![section-buttons](https://ryusei-komada.com/wp-content/uploads/2025/04/92213c79f33afe093d58edbe2610667a.webp)  
- 2 カラム構造  
  ![ui-structure](https://ryusei-komada.com/wp-content/uploads/2025/04/98836661ee3b79a65964aba13c977d93.webp)  
- チュートリアルオーバーレイ  
  ![tutorial](https://ryusei-komada.com/wp-content/uploads/2025/04/adc9c585b6087881f0ce79af7cd8b4f9.webp)  
- 見出しの追従表示  
  ![sticky-title](https://ryusei-komada.com/wp-content/uploads/2025/04/120db295a75477a874093ea921208575.webp)

---

## 🤖 対応モデル
- **メイン**: ChatGPT-4o Image Generation  
- **互換**: YAML を受け付ける任意の画像生成 AI（例: SDXL など）

---

## 🗺️ 今後のロードマップ
- [ ] **リアルタイム YAML 生成** – 入力と同時にプレビュー更新  
- [ ] **アートスタイル／構図の追加**  
- [ ] **ネガティブプロンプト入力欄**  
- [ ] **論理フラグ**（実験的ディレクティブ）

要望は Issues へお気軽にどうぞ！

---

## 🤝 コントリビュート方法
1. `git clone` 後、お好みのエディタで編集  
2. HTML 版はそのまま、PHP 版は `php -S localhost:8080` でテスト可能  
3. PR のコミットメッセージは **Conventional Commits** 準拠でお願いします (`feat:`, `fix:`, `docs:` など)

---

## 📄 ライセンス
本リポジトリは **MIT License** で配布しています。詳細は [`LICENSE`](LICENSE) を参照してください。

---

## 🔗 運営者リンク
- ブログ: <https://ryusei-komada.com>  
- 事業サイト: <https://freedom-build.com>  
- X (Twitter): <https://x.com/ryuseikomada>  
- LinkedIn: <https://www.linkedin.com/in/%E9%9A%86%E6%88%90-%E9%A7%92%E7%94%B0-9857282b9/>  
- Lancers: <https://www.lancers.jp/profile/Jonni>  
- Coconala: <https://coconala.com/users/4464494>

> *Made with ChatGPT 4o & lots of ☕ by Ryusei Komada*
