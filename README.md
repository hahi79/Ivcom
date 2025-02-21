# Ivcom : IVコンパイラ

RPGのマップ・インベント類を記述できるように設計されたIVスクリプトのコンパイラです。

IVスクリプトを読み込んで、アセンブラソースを出力します。
アセンブラソースは、マクロで中間コードを記述しています。
$0番地でアセンブル。リンクして、リロケータブルなバイナリーファイルを生成します。

IVスクリプトの構文解析に Yacc を利用しています。
また、プリプロ機能がありますが、これも Yaccで記述しています。
語句解析は、lexではなく独自(lex.cとplex.c)です

### ソースファイル
- lex.c :
- main.c
- exp.c
- heap.c
- misc.c
- genexp.c
- gencode.c
- stmt.x
- object.c
- message.c
- string.c
- seg.c
- label.c
- symbol.c
- var.c
- kanji.c
- define.c
- func.c
- mescom.c
- lzss.c
- datalist.c
- export.c
- pp.c
- plex.c
- asm.c
- code.c
- proc.c
- hdrout.c
- iv.y


# IVスクリプトの仕様

