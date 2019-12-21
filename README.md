# DTV-Built
TS抜き (DTV) 関連ソフトウェアのビルド済みアーカイブです。

## 概要
32bit 版・64bit 版を両方同梱しています。
必須・よく使われるプラグイン等を一式、  
BonDriver 関連ファイルをセットアップするだけで利用できる状態にしてあります。  
基本的に一番上の最新版をダウンロードするようにしてください。  

## 注意
BonDriver 関連ファイルは同梱していません。各自でセットアップしてください。  
また、フォントは全て Meiryo UI に統一しています。  
基本的に動くかどうかの保証はありません。自己責任にてお願いします。

[TVTest](https://github.com/tsukumijima/TVTest) はよく使われるプラグイン一式も同梱しています。  
[EDCB](https://github.com/tsukumijima/EDCB) は現在主流の xtne6f 版 に EpgTimer 関連のパッチを当てた tkntrec 版をビルドしています。  
BonDriverProxyEx は B25 Decode 版をビルドしています。  
BonDriver_Proxy や BonDriver_Splitter も同梱しています。  
BonDriver_Proxy と BonDriver_Splitter は BonDriverProxy と BonDriverProxyEx で共通です。

ffmpeg は pthread などのライブラリ全部入りでビルドしています。  
Static とつく方はライブラリをそれぞれの exe にまとめたバージョン、  
Shared とつく方はライブラリを dll にまとめてファイルサイズを抑えたバージョンです。 

## ダウンロード
 - **TVTest**
   - TVTest-0.10.0-191129 … [TVTest-0.10.0-191129.zip](https://github.com/tsukumijima/DTV-Built/raw/master/TVTest-0.10.0-191129.zip)
   - TVTest-0.10.0-190808 … [TVTest-0.10.0-190808.zip](https://github.com/tsukumijima/DTV-Built/raw/master/TVTest-0.10.0-190808.zip)
   - TVTest-0.10.0-190203 … [TVTest-0.10.0-190203.zip](https://github.com/tsukumijima/DTV-Built/raw/master/TVTest-0.10.0-190203.zip)
 - **EDCB**
   - EDCB-191129 … [EDCB-191129.zip](https://github.com/tsukumijima/DTV-Built/raw/master/EDCB-191129.zip)
   - EDCB-190814 … [EDCB-190814.zip](https://github.com/tsukumijima/DTV-Built/raw/master/EDCB-190814.zip)
   - EDCB-190721 … [EDCB-190721.zip](https://github.com/tsukumijima/DTV-Built/raw/master/EDCB-190721.zip)
   - EDCB-190709 … [EDCB-190709.zip](https://github.com/tsukumijima/DTV-Built/raw/master/EDCB-190709.zip)
   - EDCB-190623 … [EDCB-190623.zip](https://github.com/tsukumijima/DTV-Built/raw/master/EDCB-190623.zip)
 - **TSTask**
   - TSTask-0.2.0 … [TSTask-0.2.0.zip](https://github.com/tsukumijima/DTV-Built/raw/master/TSTask-0.2.0.zip)
   - TSTask-SPHD-0.2.0 … [TSTask-SPHD-0.2.0.zip](https://github.com/tsukumijima/DTV-Built/raw/master/TSTask-SPHD-0.2.0.zip)
 - **BonDriverProxyEx**
   - BonDriverProxyEx-1.1.6.6 … [BonDriverProxyEx-1.1.6.6.zip](https://github.com/tsukumijima/DTV-Built/raw/master/BonDriverProxyEx-1.1.6.6.zip)
 - **BonDriverProxy**
   - BonDriverProxy-1.1.6.5 … [BonDriverProxy-1.1.6.5.zip](https://github.com/tsukumijima/DTV-Built/raw/master/BonDriverProxy-1.1.6.5.zip)
 - **ffmpeg**
   - ffmpeg-4.2.1-static … [ffmpeg-4.2.1-static.7z](https://github.com/tsukumijima/DTV-Built/raw/master/ffmpeg-4.2.1-static.7z)
   - ffmpeg-4.2.1-shared … [ffmpeg-4.2.1-shared.7z](https://github.com/tsukumijima/DTV-Built/raw/master/ffmpeg-4.2.1-shared.7z)
   - ffmpeg-4.2-static … [ffmpeg-4.2-static.7z](https://github.com/tsukumijima/DTV-Built/raw/master/ffmpeg-4.2-static.7z)
   - ffmpeg-4.2-shared … [ffmpeg-4.2-shared.7z](https://github.com/tsukumijima/DTV-Built/raw/master/ffmpeg-4.2-shared.7z)
   - ffmpeg-4.1.4-static … [ffmpeg-4.1.4-static.7z](https://github.com/tsukumijima/DTV-Built/raw/master/ffmpeg-4.1.4-static.7z)
   - ffmpeg-4.1.4-shared … [ffmpeg-4.1.4-shared.7z](https://github.com/tsukumijima/DTV-Built/raw/master/ffmpeg-4.1.4-shared.7z)
   - ffmpeg-4.1.1-static … [ffmpeg-4.1.1-static.7z](https://github.com/tsukumijima/DTV-Built/raw/master/ffmpeg-4.1.1-static.7z)
   - ffmpeg-4.1.1-shared … [ffmpeg-4.1.1-shared.7z](https://github.com/tsukumijima/DTV-Built/raw/master/ffmpeg-4.1.1-shared.7z)
