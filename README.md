# Kirishitan Ligatures Font
![Kirishitan Ligatures top](https://user-images.githubusercontent.com/5482424/225489680-0e14042f-05cb-4441-9ffe-16979bcba7f3.png)

## Description 概要
Kirishitan Ligatures is an open source Latin font that contains abbreviated letter ligatures used in Kirishitan Ban print books. It is intended to type the ligatures easily in academic documents and publications. The design is based on Adobe’s Source Han Sans Regular’s Latin, and intended to be used in regular weights of Mincho fonts such as Hiragino Mincho W3, Yu Mincho Medium, and Ryumin R.

Kirishitan Ligaturesはオープンソースの欧文フォントで、キリシタン版に頻出する略字の合字をサポートしています。学術文書や出版物において、これらの合字を簡単に印字できるようにするために作られました。デザインはAdobeの源ノ明朝Regularをベースにしており、類似の太さの明朝体とも合わせやすいような太さにしています（ヒラギノ明朝W3、游明朝Medium、リュウミンRなど）。

## How to use 利用方法
Install the font in your system and choose it in your application of choice. The font will accept the input strings and display the corresponding ligatures automatically (see below image). They are all case-agnostic; [apo] can be [APO], [Apo], [aPo] and so on. Square brackets before and after the letter string are mandatory. This will make searching the text easier, as well as spotting ligature failures (e.g. fonts not applied).

フォントをお使いの機器にインストールし、アプリケーションの文書からフォントを選択します。フォントで以下の画像のようなテキストを入力すると、それに対応する合字記号が表示されます。大文字小文字の区別はありません。[apo]は[APO]、[Apo]、[aPo]など、いずれも受け付けられます。前後の角括弧は必須です。これがあることで検索が楽になりますし、合字が表示されていない場合に発見しやすくなります。

[apo] [apto] [bta] [bto] [de1] [de2] [dpo] [ds] [ds2] [ds3] [ds4] [fo] [jao] [jo] [jo2] [js] [jxo] [ma] [pa] [pe] [po] [pp] [pt] [pta] [pu] [sm] [sma] [xao] [xo] [x1] [x2] [x3]

![Kirishitan Ligatures Input Strings](https://user-images.githubusercontent.com/5482424/225482458-908dfde1-a734-449a-96f3-5be234917042.png)

## Notes on the use 使用上の留意点
- MS Word does not activate the ligatures by default to keep compatibility with old versions. The image below shows the easiest way to access the ligature options. Anything other than *None* works.
- MS Wordでは古いバージョンのOfficeとの互換性を保つため、合字が標準状態では適用されません。合字を有効化させる楽な方法は以下の画像の通りです。「なし」以外のいずれかのオプションを選ぶと使用できます。
![Word Ligature Access](https://user-images.githubusercontent.com/5482424/226122862-99cfb427-3a24-4a3a-b8cb-4f8c1bd1a28a.png)

- If you want to make them upright in vertical text in office documents (called 縦中横 *tate chu yoko* in Japan), select the corresponding menu item in the application (images below)
- Office系のアプリケーションで縦書きで正立表示させたい場合（縦中横）、アプリケーション内で当該のメニュー項目を選択します。

Microsoft Word
![縦中横 Word](https://user-images.githubusercontent.com/5482424/225483554-adfdb744-3ae0-49a1-9553-bfe32035d7e6.png)

In Apple Pages, the rotation option is in the context menu or Edit menu.

Apple Pagesでは、回転したいテキストを選択し、コンテキストメニューまたは編集メニューから選択します。

![縦中横 Pages 1](https://user-images.githubusercontent.com/5482424/225484133-5794d9ef-4ba9-4f25-80dd-2664f5eae811.png)![縦中横 Pages 2](https://user-images.githubusercontent.com/5482424/225484143-742bdf8c-5dd7-43a1-96a1-21c714cdd740.png)


## Credit クレジット
The basic Latin portion uses Source Han Serif which was designed by Frank Grießhammer of Adobe. The ligatures were designed by Toshi Omagari. The ligatures were created for “Kirishitan-ban in the Digital Age: A Study of the Opportunities and Limitations of Applying Digital Methods to Kirishitan-ban” a research project headed by James Harry Morris and partially funded by a DNP Foundation for Cultural Promotion Graphic Culture Research Grant.

源ノ明朝から流用した欧文はAdobeのFrank Grießhammerの作です。Kirishitan Ligaturesの合字は大曲都市の作です。Kirishitan Ligaturesは、モリス・ジェームズ・ハリーを代表とする『デジタル時代におけるキリシタン版: デジタル手法による「キリシタン版」探索の可能性と限界に関する考察』という研究プロジェクトのために作成されたものです。そのプロジェクトの一部はDNP文化振興財団のグラフィック文化に関する学術研究助成により実施されたものです。

## Technical Notes 技術

The source file was created using GlyphsApp version 3, a mac-only font editor. The final OTF font contains ccmp, rlig, and liga OpenType features containing the same ligature code, intended to be activated as automatically possible.

ソースファイルはMac用のフォントエディタであるGlyphsAppバージョン3で作られました。出力されたOTFフォントは合字機能をなるべく自動的に発動させるため、ccmp、rlig、ligaフィーチャーに同じ合字機能のコードを繰り返しています。

## License ライセンス
This font is distributed under the SIL Open Font License version 1.1.

このフォントはSIL Open Font Licenseバージョン1.1ライセンスで配布されています。
