# DTV-Built
TS抜き (DTV) 関連ソフトウェアのビルド済みアーカイブです。

## 概要
32bit 版・64bit 版を両方同梱しています。  
必須・よく使われるプラグイン等を一式まとめ、BonDriver 関連ファイルをセットアップするだけで利用できる状態にしてあります。  
基本的に一番上の最新版をダウンロードするようにしてください。  
過去のアーカイブは念のため残しているだけなので、利用は推奨しません。

## 注意
- BonDriver 関連ファイルは同梱していません。各自でセットアップしてください。  
- フォントは全て Meiryo UI に統一しています。
  - MS ゴシックだと見づらいので…  
- 前述の通り、設定しやすいよう設定ファイルを変更したり、必要/よく使われるプラグインを同梱したりと  
  いくつか変更を加えている箇所があるため、本家のソースコードをそのままビルドしたアーカイブではないことに注意してください。
  - 信頼できないようであれば自ビルドすることを推奨します。
- VS2019 (TVTest-0.10.0-200202・EDCB-200209 より、それ以前は VS2017) にてビルドしています。別途ランタイムが必要かもしれません。
  - ビルド毎に同梱するファイルを更新したり構成を変更したりしているため、古いバージョンには現在のバージョンでは同梱しているファイルが入っていない事があります。  
  - できるだけ新しいものを使用してください（特に TVTest-0.10.0-200202・EDCB-200209 以前の TVTest・EDCB は諸都合でおすすめしません）。   
  - EDCB-200419 以前に同梱していた局ロゴは EMWUI で読み込まれないことが判明したため、EDCB-200712 以降の EDCB では差し替えた局ロゴを同梱しています（申し訳ありません）。
- 万全は期しているつもりですが、基本的に動くかどうかの保証はありません。利用は自己責任にてお願いします。  

## 内容について
各 .txt ファイルはいずれも最新のアーカイブについての内容になっています。使い始める前に一読しておくことをおすすめします。

[TVTest](https://github.com/tsukumijima/TVTest) はよく使われるプラグイン一式を同梱しています。  
ビルドの詳細は [TVTest_Build.txt](https://github.com/tsukumijima/DTV-Built/blob/master/TVTest_Build.txt) に記載しています。

[EDCB](https://github.com/tsukumijima/EDCB) は現在主流の xtne6f 版 に EpgTimer 関連のパッチを適用した tkntrec 版をビルドしています。  
（ EDCB_Material_WebUI も同梱していますが、使用する場合は別途設定が必要です）  
ビルドの詳細は [EDCB_Build.txt](https://github.com/tsukumijima/DTV-Built/blob/master/EDCB_Build.txt) に記載しています。

[TSTask](https://github.com/tsukumijima/TSTask) は RecTask 相当にするパッチを適用しスクランブル解除できるようにしたものをビルドしています。  
ビルドの詳細は [TSTask_Build.txt](https://github.com/tsukumijima/DTV-Built/blob/master/TSTask_Build.txt) に記載しています。

[TSTask-SPHD](https://github.com/tsukumijima/TSTask/tree/SPHD) は先ほどの TSTask にさらにスカパー！プレミアムサービス対応にするパッチを適用したものをビルドしています。  
ビルドの詳細は [TSTask-SPHD_Build.txt](https://github.com/tsukumijima/DTV-Built/blob/master/TSTask-SPHD_Build.txt) に記載しています。

BonDriverProxyEx はスクランブル解除が可能な [epgdatacapbon 氏のフォーク](https://github.com/epgdatacapbon/BonDriverProxyEx/tree/decode)をビルドしています。  
BonDriver_Proxy や BonDriver_Splitter も一緒に同梱しています。    
BonDriver_Proxy と BonDriver_Splitter の内容は BonDriverProxy と BonDriverProxyEx で共通ですが、設定ファイル等を分かりやすいよう変更している部分があります。  
ビルドの詳細は [BonDriverProxyEx_Build.txt](https://github.com/tsukumijima/DTV-Built/blob/master/BonDriverProxyEx_Build.txt) に記載しています。  
BonDriverProxy のビルドの詳細は [BonDriverProxy_Build.txt](https://github.com/tsukumijima/DTV-Built/blob/master/BonDriverProxy_Build.txt) に記載しています。

ffmpeg は pthread などのライブラリ全部入りでビルドしています。  
Static とつく方はライブラリをそれぞれの exe にまとめたバージョン、  
Shared とつく方はライブラリを dll にまとめてファイルサイズを抑えたバージョンです。 

## ダウンロード
 - **TVTest**
   - TVTest-0.10.0-200629 … [TVTest-0.10.0-200629.zip](https://github.com/tsukumijima/DTV-Built/raw/master/TVTest-0.10.0-200629.zip)
   - TVTest-0.10.0-200508 … [TVTest-0.10.0-200508.zip](https://github.com/tsukumijima/DTV-Built/raw/master/TVTest-0.10.0-200508.zip)
   - TVTest-0.10.0-200202 … [TVTest-0.10.0-200202.zip](https://github.com/tsukumijima/DTV-Built/raw/master/TVTest-0.10.0-200202.zip)
   - TVTest-0.10.0-200103 … [TVTest-0.10.0-200103.zip](https://github.com/tsukumijima/DTV-Built/raw/master/TVTest-0.10.0-200103.zip)
   - TVTest-0.10.0-191129 … [TVTest-0.10.0-191129.zip](https://github.com/tsukumijima/DTV-Built/raw/master/TVTest-0.10.0-191129.zip)
   - TVTest-0.10.0-190808 … [TVTest-0.10.0-190808.zip](https://github.com/tsukumijima/DTV-Built/raw/master/TVTest-0.10.0-190808.zip)
   - TVTest-0.10.0-190203 … [TVTest-0.10.0-190203.zip](https://github.com/tsukumijima/DTV-Built/raw/master/TVTest-0.10.0-190203.zip)
 - **EDCB**
   - EDCB-200712 … [EDCB-200712.zip](https://github.com/tsukumijima/DTV-Built/raw/master/EDCB-200712.zip)
   - EDCB-200419 … [EDCB-200419.zip](https://github.com/tsukumijima/DTV-Built/raw/master/EDCB-200419.zip)
   - EDCB-200209 … [EDCB-200209.zip](https://github.com/tsukumijima/DTV-Built/raw/master/EDCB-200209.zip)
   - EDCB-191222 … [EDCB-191222.zip](https://github.com/tsukumijima/DTV-Built/raw/master/EDCB-191222.zip)
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
