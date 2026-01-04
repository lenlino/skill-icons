# Profile Icons

これを使用すると簡単にスキルアイコンをプロフィールに設定できます。

# 使用例

<p align="center"><img align="center" src="./.github/example-dark.png#gh-dark-mode-only"/></p>
<p align="center"><img align="center" src="./.github/example-light.png#gh-light-mode-only"/></p>

# アイコンの指定方法

以下のコードブロックをあなたのreadmeにコピー&ペーストしてスキルアイコンを追加しましょう!

`?i=js,html,css` の部分をカンマで区切ったスキルのリストに変更してください! アイコンの完全なリストは[こちら](#アイコン一覧)で確認できます。

```md
[![My Skills](https://icons.lenlino.com/icons?i=js,html,css,wasm)](https://icons.lenlino.com)
```

[![My Skills](https://icons.lenlino.com/icons?i=js,html,css,wasm)](https://icons.lenlino.com)

# テーマ付きアイコン

一部のアイコンには、ダークテーマとライトテーマの背景があります。URLパラメーターでテーマを指定できます。

これはオプションです。デフォルトのテーマはダークです。

`&theme=light` を `dark` または `light` に変更してください。テーマは背景色を指定するもので、ライトテーマは白いアイコン背景を持ち、ダークは黒っぽい背景になります。

**ライトテーマの例:**

```md
[![My Skills](https://icons.lenlino.com/icons?i=java,kotlin,nodejs,figma&theme=light)](https://icons.lenlino.com)
```

[![My Skills](https://icons.lenlino.com/icons?i=java,kotlin,nodejs,figma&theme=light)](https://icons.lenlino.com)

# 1行あたりのアイコン数

1行あたりに表示するアイコンの数を指定できます! これはオプションの引数で、デフォルトは15です。

`&perline=3` を1から50の間の任意の数に変更してください。

```md
[![My Skills](https://icons.lenlino.com/icons?i=aws,gcp,azure,react,vue,flutter&perline=3)](https://icons.lenlino.com)
```

[![My Skills](https://icons.lenlino.com/icons?i=aws,gcp,azure,react,vue,flutter&perline=3)](https://icons.lenlino.com)

# アイコンを中央揃えにする

readmeでアイコンを中央揃えにしたいですか? SVGは自動的にリサイズされるので、通常の画像を中央揃えにするのと同じ方法で行えます。

```html
<p align="center">
  <a href="https://icons.lenlino.com">
    <img src="https://icons.lenlino.com/icons?i=git,kubernetes,docker,c,vim" />
  </a>
</p>
```

<p align="center">
  <a href="https://icons.lenlino.com">
    <img src="https://icons.lenlino.com/icons?i=git,kubernetes,docker,c,vim" />
  </a>
</p>

## 🎨 アイコンの追加について

アイコンの追加を受け付けています! 

**アイコンのサイズは256x256で、他のアイコンの一貫性のある必要があります。**

[アイコン作成ツール](https://tools.lenlino.com/jp/icon-converter)を使用することで簡単に同様のスタイルのアイコンを作成できます。ぜひご利用ください。

お気軽にプルリクエストでアイコンを追加してください!

## クレジット

このプロジェクトは [tandpfun/skill-icons](https://github.com/tandpfun/skill-icons) からフォークしたものです。素晴らしいツールを作成してくれてありがとうございます!
