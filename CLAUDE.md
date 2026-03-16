# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

もりあーてぃ のポートフォリオサイト。GitHub Pages でホスティング予定の静的サイト。

## Architecture

- **単一HTML構成**: `index.html` のみで構成（CSS/JSはインライン）
- **Tailwind CSS**: CDN経由（`cdn.tailwindcss.com`）で利用
- **フォント**: Google Fonts（M PLUS Rounded 1c, Quicksand）
- **背景アニメーション**: Canvas APIによるプロシージャルドットアニメーション（波紋エフェクト付き）
- **デザインテーマ**: グラスモーフィズム（`.glass-panel`クラス）、明るくポップな雰囲気

## Development

ビルドツール不要。ブラウザで `index.html` を直接開くか、ローカルサーバーで確認。

```bash
# ローカルサーバー例
npx serve .
# または
python -m http.server
```

## Design Guidelines

- 明るい雰囲気でポップなデザイン
- インタラクティブな楽しさ（ホバー・クリックアニメーション）を重視
- グラスモーフィズムパネルで統一感を保つ
