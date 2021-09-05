# 自分向け React Typescript ESlint Prettier vscode の設定サンプルプロジェクト

- React
- Typescript
- eslint
- prettier
- vscode

## やりたいこと

- vscode の保存時に自動保存
- インデントのスペースは 2 つ
- ダブルクォートを使う
- セミコロンを強制的に入れる

## やったこと

1. create-react-app でプロジェクト作成
1. npm i -D eslint prettier eslint-config-prettier
1. npm i -D @typescript-eslint/parser
1. npm i -D @typescript-eslint/eslint-plugin
1. npm i -D eslint-plugin-react eslint-plugin-react-hooks
1. .eslintrc.json 追加
1. .prettierrc.json 追加
1. vscode の ESLint プラグインと Prettier プラグインインストール（ローカル環境の話なので github 上には何も影響なし）
1. .vscode/settings.json 追加

## 参考サイト

https://zenn.dev/sprout2000/articles/9f20902d394aa2
