# ブロックをバウンドさせる方法

1. Cubeの作成 
Hieraruchyタブで右クリック ➡ 3D object ➡ Cube

1. CubeにBoxColliderとRigidBodyのコンポーネントを追加
写真のようにするがMaterialの部分は今はなくてよい。<br>
![](../images/バウンド1.PNG)

1. Assetsのタブ上で物理スクリプトを作成
![](../images/%E3%83%90%E3%82%A6%E3%83%B3%E3%83%892.PNG)
写真のような設定だとほぼ一定感覚でバウンドする。

## 物理スクリプトの説明
* Dynamic Friction 動摩擦力
* Static Friction 静止摩擦力
* Bounciness 跳ね返り係数
* Friction Combine 摩擦力の範囲
* Bounciness Combine 跳ね返り係数の範囲