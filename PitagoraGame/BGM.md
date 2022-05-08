# ゲーム中にBGMを流す方法

1. BGMに使う音声ファイルをUnityに取り込む<br>

！[](../images/BGM1.PNG)

1. BGMをアタッチするためのゲームオブジェクトを準備する

Hierarchyで右クリックタブ内で、右クリック ➡ CreateEmpty ➡ 名前をBGMにしたからオブジェクトを作成<br>

1. Add ComponentからAudio > Audio Sourceを選択

1. AudioClipに流したい曲のファイルをドラッグ＆ドロップ

(Mute Audioがオン(白っぽく)になってると以上の動作をしても聞こえないよ)
！[](../images/BGM2.PNG)

[参考サイト](https://xr-hub.com/archives/18550)