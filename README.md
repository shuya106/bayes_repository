# ベイズ推定<br>
----------------------------<br>
pyMC3を用いてベイズ推定を試みる。<br>
<br>
## コイントスを題材にした実験<br>
■コイントスを10回行った際の事後分布の変化
![coin_toss](https://user-images.githubusercontent.com/50583880/69395438-4e2f6700-0d22-11ea-95e7-938548ae3b20.png)<br>

■コイントスを20000回行い、途中でイカサマコインに変えた時の前半と後半の事後分布
![coin_toss_changepoint](https://user-images.githubusercontent.com/50583880/69395603-e4638d00-0d22-11ea-9093-37c6cd1471d1.png)<br>


## とあるライブのチケットの取得確率を分布で算出<br>
■事前分布として事前情報を用いた場合<br>
![ticket_beta](https://user-images.githubusercontent.com/50583880/68908365-620d2300-078e-11ea-9412-694b36188e7c.png)<br>
■事前分布として一様分布を用いた場合<br>
![ticket_uniform](https://user-images.githubusercontent.com/50583880/68908475-c4662380-078e-11ea-80a6-4e69c2f49c50.png)

## 日経平均株価の上昇トレンドの確率を分布で算出<br>
![kabuka_trend](https://user-images.githubusercontent.com/50583880/68908504-e495e280-078e-11ea-9df0-b44140e5de2a.png)
