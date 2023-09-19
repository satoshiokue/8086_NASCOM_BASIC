# 8086_NASCOM_BASIC

Nascom BASICはマイクロソフトが作成し、Grant Searleさんがサブセットに改編し、鈴木哲哉さんが移植されたコードを元に、奥江聡が8080/Z80から8086にコンバートしました。  

ファイルは原作者の宣言にしたがってご利用ください。  

ターゲット SBCV20 V20/8088  
アセンブラ Macro Assembler 1.42  

BASICのMONITOR命令で割り込みを禁止して0C000hへジャンプします。
