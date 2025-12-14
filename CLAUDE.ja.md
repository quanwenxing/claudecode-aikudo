# CLAUDE.md

[English](CLAUDE.md)

このファイルは、Claude Code (claude.ai/code) がこのリポジトリのコードを操作する際のガイダンスを提供します。

## プロジェクト概要

これは、バニラHTML、CSS、JavaScriptで構築されたスタンドアロンTODOアプリケーションです。ビルドツールやパッケージマネージャーは必要ありません。

## アプリケーションの実行

`todo.html`をブラウザで直接開いてください：
```bash
open todo.html
```

## アーキテクチャ

- **シングルファイルアーキテクチャ**: すべてのHTML、CSS、JavaScriptが`todo.html`に含まれています
- **データ永続化**: localStorageを使用（キー: `kokoroecho-todos`）
- **デザインテーマ**: Zen AntiqueとZen Kaku Gothic Newフォントを使用した和風モダン（Wa-fu Modern）の美学
