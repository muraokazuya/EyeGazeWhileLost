# EyeGazeWhileLost
このフォルダには実験のデータを置いています．

subject1からsubject4のフォルダ
視線データ　例:reco13del.csv
加速度データ　例:reco13delAccelerometerData.csv
角速度データ　例:reco13delGyroscopeData.csv
ラベルデータ　例:reco13label.csv

JsonToTxtConverter1_2.jarによって変換されたものです．
JsonToTxtConverter1_2.jarについては↓
https://github.com/anwul4/Tobii_JsonToTxtConversionTool
Tobiiで保存されるlivedata.json.gzを解凍してlivedata.jsonにして，JsonToTxtConverter1_2.jarを起動して、livedata.jsonを読み込ませると加速度，ジャイロ，視線がでてくる．Tobii labを使わないでデータを抽出する方法．時間は秒．

Project6 Recording0XX.xlsxはTobii labを使って抽出したファイル．
加速度，ジャイロ，視線が1つに入っている．時間はミリ秒．

実験者ごとに実験のデータを分けています．
実験者1はreco13～reco15（男、22、矯正なし）
実験者2はreco16～reco18（女、22、裸眼視力悪い）
実験者3はreco19～reco21（女、22、コンタクト）
実験者4はreco22～reco24（男、22、裸眼視力悪い）眼鏡つけてできないので眼鏡なしでやった。

各実験者の実験順はすべてコース1，コース2，コース3です．
例:reco13はコース1，reco14はコース2，reco15はコース3，reco16はコース1, reco17はコース2．．．

実験者3については録画ミス(存在しないreco20)があり，実験者4は目が悪かったので視線データがあまり表れませんでした．
