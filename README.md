# ライブラリを作りたい

ビルドするべきものについて、こちらを参考にさせていただきました。

[ライブラリ開発のための環境設定 — 仕事ですぐに使えるTypeScript ドキュメント](https://future-architect.github.io/typescript-guide/libenv.html)


# このライブラリの利用方法

インストール

```
yarn add srymh/mylibtest1#master
```

Typescript

``` ts
import { hello } from "mylibtest1";
console.log(hello());
```
