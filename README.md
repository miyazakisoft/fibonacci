[![Build Status](https://travis-ci.org/miyazakisoft/dot_comparison.svg?branch=master)](https://travis-ci.org/miyazakisoft/dot_comparison)

# はじめに
内積の計算を行うプログラムがどのくらいの時間がかかるのかを算出するプログラムである．
なお，内積の計算は，ライブラリを用いている．
ライブラリは，次の4つである．
1. ND4J 0.6.0
2. Commons Math 3.6.1
3. la4j 0.6.0
4. UJMP 0.3.0

# 実行方法
* `$ gradle build`
* `$ gradle run -Pargs="X"`

X は，実行するライブラリの番号である.
ライブラリの番号は，上記の番号と一致している．
