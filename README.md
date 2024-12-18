# 地理院地図Vectorで読み込めるスタイルのサンプル集

## 本レポジトリについて
本レポジトリでは、[地理院地図Vector]( https://maps.gsi.go.jp/vector/)で読み込めるスタイルファイルのサンプルを提供しております。

- 以下の各地図の名前の部分を右クリックし、「名前をつけて保存」などからスタイルファイルをダウンロードすることができます。
保存したファイルは、地理院地図Vectorの「地図デザインの追加」-「地図デザインファイルを開く」から読み込んで表示することができます。
- また、地図の画像をクリックすると、その地図をシームレスに見ることができます。
- [ベクトルタイルの建物データ等を3D風に表示するサンプル](https://github.com/gsi-cyberjapan/gsivectortile-3d-like-building)も別途提供しております（こちらは地理院地図Vectorでは読み込めません）。

### [軽い標準地図](https://raw.githubusercontent.com/gsi-cyberjapan/gsimaps-vector-stylesamples/master/data/light.json)
地理院地図Vectorの「標準地図」をベースに、道路・鉄道の立体交差の表現を行わないなど、できるだけシンプルなデザインとすることで、スタイルファイルの読み込み速度を「標準地図」より速めたスタイルです。

[![軽い標準地図](image/light.png)<br>→ この地図を見る](https://gsi-cyberjapan.github.io/gsimaps-vector-stylesamples/index.html#7/36.104611/140.084556/&ls=light&disp=1&d=l) 


### [道路地図](https://raw.githubusercontent.com/gsi-cyberjapan/gsimaps-vector-stylesamples/master/data/road.json)
道路をほかの地物より目立たせて表示し、さらに道路の種類（高速道路、国道、都道府県道など）をわかりやすくしたスタイルです。

[![道路地図](image/road.png)<br>→ この地図を見る](https://gsi-cyberjapan.github.io/gsimaps-vector-stylesamples/index.html#7/36.104611/140.084556/&ls=road&disp=1&d=l) 


### [鉄道路線図](https://raw.githubusercontent.com/gsi-cyberjapan/gsimaps-vector-stylesamples/master/data/railway.json)
鉄道に関する情報だけを表示したスタイルです（ZL8～17では、参考として河川も表示しています）。

[![鉄道路線図](image/railway.png)<br>→ この地図を見る](https://gsi-cyberjapan.github.io/gsimaps-vector-stylesamples/index.html#7/36.104611/140.084556/&ls=railway&disp=1&d=l) 


### [地形だけ地図](https://raw.githubusercontent.com/gsi-cyberjapan/gsimaps-vector-stylesamples/master/data/land.json)
道路や建物などを表示せず、山と山名、川と川名など、自然の地形の情報のみを表示したスタイルです。地形の学習の素材にオススメです。

[![地形だけ地図](image/land.png)<br>→ この地図を見る](https://gsi-cyberjapan.github.io/gsimaps-vector-stylesamples/index.html#7/36.104611/140.084556/&ls=land&disp=1&d=l) 


### [川だけ地図](https://raw.githubusercontent.com/gsi-cyberjapan/gsimaps-vector-stylesamples/master/data/river.json)
地形だけ地図からさらに表示する地物を減らし、河川や湖などに関する情報のみを表示したスタイルです。

[![川だけ地図](image/river.png)<br>→ この地図を見る](https://gsi-cyberjapan.github.io/gsimaps-vector-stylesamples/index.html#7/36.104611/140.084556/&ls=river&disp=1&d=l) 


### [ひらがなちず](https://raw.githubusercontent.com/gsi-cyberjapan/gsimaps-vector-stylesamples/master/data/kana.json)
文字をひらがなで表示したスタイルです。ZL8～17にて文字がひらがなで表示されます。

[![ひらがなちず](image/kana.png)<br>→ この地図を見る](https://gsi-cyberjapan.github.io/gsimaps-vector-stylesamples/index.html#8/36.104611/140.084556/&ls=kana&disp=1&d=l) 

- なお、地理院地図Vectorの「おすすめの地図」で選択できるスタイルファイルは、[地理院地図Vector提供実験のレポジトリ](https://github.com/gsi-cyberjapan/gsimaps-vector-experiment/)をご覧ください。


## 注意事項
本レポジトリのスタイルファイルは実験的に提供しているものです。予告なく削除する可能性があります。

本レポジトリのスタイルファイルの利用により生じた損失及び損害等について、国土地理院はいかなる責任も負わないものとします。


## 履歴
- 2020-04-28 レポジトリ公開開始

