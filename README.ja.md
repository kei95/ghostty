# Ghostty 設定ファイル

[Ghostty](https://ghostty.org/) ターミナルエミュレータの個人設定です。

## セットアップ

**[IMPORTANT]** macOSの場合、デフォルトのパスは `~/Library/Application Support/com.mitchellh.ghostty/config` です。このレポジトリが生成するパスである`~/.config/ghostty/config` を使用するには、デフォルトの設定ファイルを削除してください：

```bash
rm ~/Library/Application\ Support/com.mitchellh.ghostty/config
```

設定が正しく読み込まれているか確認するには：

```bash
ghostty +show-config
```

## 機能

### 外観
- フォントサイズ: 18
- テーマ: Tomorrow Night
- カーソルスタイル: ブロック
- 入力中はマウスを非表示
- Display P3 カラースペース

### キーバインド

| キーバインド | 動作 |
|---------|--------|
| `Shift+Enter` | 改行を挿入 |
| `Alt+Backspace` / `Shift+Backspace` | 単語削除 |
| `Shift+Delete` | 全テキスト削除 |
| `Ctrl+H/J/K/L` | ペイン移動（vim風） |
| `Ctrl+Shift+V` | 右にペイン分割 |
| `Ctrl+Shift+H` | 下にペイン分割 |
| `Ctrl+X` | ペインを閉じる |
| `Ctrl+,` / `Ctrl+.` | ペインを左右にリサイズ |
| `Ctrl+;` / `Ctrl+'` | ペインを上下にリサイズ |
| `Ctrl+Shift+K/J` | 上下にスクロール|
