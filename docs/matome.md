# 1 有限体
* 楕円曲線暗合(ECC)を学ぶ→トランザクションの根本
  * 署名アルゴリズム
  * 鑑賞アルゴリズム
* トランザクション
  * ビットコインで価値移転

## 1. 2　有限体の定義
* 有限個の数からなる集合
* 加算と乗算が以下を満たす
  * 1. 閉じている
    * 独自の加算の定義をしている
  * 2. 加法単位元→0がある
  * 3. 乗算単位元→1がある
  * 4. 加法逆元→-aがある
  * 5. 乗算逆元→a-1がある

## 1.3 有限集合の定義
* 有限体の数学の表記
  * Fp = {0, 1, 2,...p-1}
* 位数をpとする
  * 勝訴は0,1,2,3の一人は限らない
  * 体の位数は最大要素より1多い数になる
  * 体の位数は素数の冪になる

## 1.4 モジュロ演算
* 四則演算について、閉じている有限体を作るために利用できる
  * モジュロ演算
    * 1つのかずを別の数で割った時のあまりを求めること

## 1.5 有限体の加算と減算
* 加算
  * a, b \in F_19
  * a +_f b \in F_19
    * 定義: a +_f b = (a + b) % p 
  * 例
    * (7 + 8) % 19 = 15
    * (17 + 18) % 19 = 16
* 減算
  * a -f_b = (a - b) % p

## 1.6 有限体の乗算とべき算
* なんかそのまんま

## 1.7 有限体の除算
* 難しい
* 有限体において、a/b = a *_f (1/b) = a *_f b^(-1)

# まとめ
なんとなく理解出来た
