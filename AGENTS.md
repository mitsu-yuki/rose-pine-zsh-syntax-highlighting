# AGENTS.md 

## プロジェクト概要(overview)
このリポジトリは[zsh-users/zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)のハイライトテーマを[rose-pine](https://rosepinetheme.com/)で作成しなおすリポジトリです。

## コーディング規約
コードの書き方は[zsh-syntax-highlighting/themes/catppuccin_macchiato-zsh-syntax-highlighting.zsh at main · catppuccin/zsh-syntax-highlighting](https://github.com/catppuccin/zsh-syntax-highlighting/blob/main/themes/catppuccin_macchiato-zsh-syntax-highlighting.zsh)を参考にしてください。

## カラーパレットのレイアウト方法
rose-pineには色の使い方が定められています。仕様は次のリンクを参照してください。
[rose-pine/rose-pine-palette: Color palette tool for Rosé Pine](https://github.com/rose-pine/rose-pine-palette?tab=readme-ov-file#specification)

### ユーザー指定の色
- コマンド類(alias, bulit-in, 外部コマンド謎)はfoam色にすること
- zshのビルドイン系もfoamにすること
- 予約語(typeset, exportなど)とprecommand系(sudoなど)もfoam色で統一すること（precommandはitalic指定）
- ダブルクオートで囲まれた引数はrose色に、一重クオートはgold色にすること
- ファイルパスの色存在する場合でも存在しない場合でも同じ色にすること
- 存在する場合には下線を引くこと
    - このあたりはcatppuccin/zsh-syntax-highlightingを参考にすること

 ## 文字スタイル
 文字の装飾はcatppuccin/zsh-syntax-highlightingに準拠すること

 ## プロンプト設定
 提案、実行内容、結果は全て日本語で表示してください。
