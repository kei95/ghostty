```text
___  ____       _                 _   _____              __ _
|  \/  (_)     (_)               | | /  __ \            / _(_)
| .  . |_ _ __  _ _ __ ___   __ _| | | /  \/ ___  _ __ | |_ _  __ _
| |\/| | | '_ \| | '_ ` _ \ / _` | | | |    / _ \| '_ \|  _| |/ _` |
| |  | | | | | | | | | | | | (_| | | | \__/\ (_) | | | | | | | (_| |
\_|  |_/_|_| |_|_|_| |_| |_|\__,_|_|  \____/\___/|_| |_|_| |_|\__, |
                                                               __/ |
                                                              |___/
```

# Ghostty 設定ファイル

[Ghostty](https://ghostty.org/) ターミナルエミュレータの個人的設定です。Ghosttyチームの掲げる"Zero Configuration Philosophy (設定不要哲学)"に従い、必要最低限のカスタマイズのみを行った設定ファイルです。

カラーテーマとフォントサイズの変更、及び入力とPane(ターミナル内の分割された枠)周りのキーバインドを追加しています。

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

| キーバインド                        | 動作                   |
| ----------------------------------- | ---------------------- |
| `Shift+Enter`                       | 改行を挿入             |
| `Alt+Backspace` / `Shift+Backspace` | 単語削除               |
| `Ctrl+H/J/K/L`                      | ペイン移動（vim風）    |
| `Ctrl+Shift+V`                      | 右にペイン分割         |
| `Ctrl+Shift+H`                      | 下にペイン分割         |
| `Ctrl+X`                            | ペインを閉じる         |
| `Ctrl+,` / `Ctrl+.`                 | ペインを左右にリサイズ |
| `Ctrl+;` / `Ctrl+'`                 | ペインを上下にリサイズ |
| `Ctrl+Shift+K/J`                    | 上下にスクロール       |
