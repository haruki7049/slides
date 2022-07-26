---
theme: uncover
---

## Nimでエレガンニャスなコードを書こう

発表者: こまもか

---

## Nimとは?

---

2008年から開発されているシステムプログラミング言語
C、C++、Adaなどの反省を活かして作られた
言語レベルでメタプログラミングがサポートされているため、柔軟にプログラムが書ける

---

## Nimのここがすごい

速い。とにかく速い。Rust/Goと同レベル
バイナリサイズが小さい。
Pythonのような文法でサクッと書ける

<img style="display: block; margin: auto;" src="./imgs/benches.png" width=40%/>


<p style="font-size: 20px;">
参照: Nimを知ってほしい2022<br/>
https://zenn.dev/dumblepy/articles/b475b3b4f7d0da
</p>

---

## なんでNimは速いの？

Nimコンパイラはバイナリではなく、最適化されたCプログラムを出力する
更にCコンパイラで更に最適化されるため速く実行できる

---

## 使われている分野

Web
サーバー、フロントエンド
Jsにも変換出来る！

CLI

TUIライブラリ illwill(日本語未対応)
cligen(CUIツール作成ライブラリ)

---

マルチメディア

blackvas(Vue likeなキャンバスライブラリ)

他言語連携

Nimpy(Nim&Python)

---

## 開発に役立つツール

choosenim
Nimの環境構築ツール

nimlsp
NimのLanguage Server

nimble
Nimのパッケージマネージャ兼ビルドツール

---
