# jis-barcode-lualatex
HOW TO Use JIS-Barcode(ja) with LuaTeX-ja.

### 【注意】内容には未整備の部分があり順次更新されます。

# 概要
- **pst-barcode**(PSTricks)を用いたJIS制定各種バーコード（一次元・二次元シンボル）の作成手順を解説しています。  
- ISO国際標準であり日本で主に使用されるインタリーブド2オブ5、コード39、EAN/UPC、コード128、GS1データバー等、及び書籍JAN コード(ISBN)や雑誌バーコードを作成します。
- **pst-barcode**をLuaLatex(LuaTeX-ja)で使用する上での問題点をまとめています。  
- 二次元シンボルについては、一部 **再現性に疑いのあるもの** が含まれる為に検証中です。

# 作業環境
- GNU/Linux Debian
- LuaTeX(LuaHBTeX), Version 1.18.0 (TeX Live 2025)
- Gedit：**Gedit** と **Debian** との作業環境手順の解説を添付しています。  

| Filename | Description |
| --- | --- |
| gedit-plugins.pdf | gedit-plugins 使用に関する解説 |
| lualatex-build | ビルド用スクリプト(sh) |
| lualatex-build-snippet.txt | snippet用ビルドスクリプト |
| lualatex-with-debian.pdf | debianにおけるlatex使用に関する解説 |
 
# USAGE
- 書籍JANコードと雑誌バーコード、及びOCRフォントについては、以下の旧版を別解として参照して下さい。  
　⇒ [isbn-barcode-ja-latex](https://github.com/ru-museum/isbn-barcode-ja-latex)　//github.com/ru-museum/isbn-barcode-ja-latex

# TODO
- 二次元シンボル  
PDF417、マイクロPDF417、GS1合成シンボル、データマトリックス、マキシコード、  
QRコード、マイクロQRコード、アズテックコード




