# EyeGazeWhileLost
このフォルダには実験のデータを置いています．
これらのデータはJsonToTxtConverter1_2.jarによって変換されたものです．

JsonToTxtConverter1_2.jarについては↓
https://github.com/anwul4/Tobii_JsonToTxtConversionTool

livedata.json.gzを解凍してlivedata.jsonにする
JsonToTxtConverter1_2.jarを起動して、livedata.jsonを読み込ませると
加速度、ジャイロ、視線がでてくる。


実験者ごとに実験のデータを分けています．
実験者1はreco13～reco15（男、22、矯正なし）
実験者2はreco16～reco18（女、22、裸眼視力悪い）
実験者3はreco19～reco21（女、22、コンタクト）
実験者4はreco22～reco24（男、22、裸眼視力悪い）眼鏡つけてできないので眼鏡なしでやった。
という実験データのナンバーになります．

各実験者の実験順はすべてコース1，コース2，コース3です．
例:reco13はコース1，reco14はコース2，reco15はコース3，
   reco16はコース1, reco17はコース2……

また，実験者3については録画ミス(存在しないreco20)があり，
実験者4は目が悪かったので視線データがあまり表れませんでした．

実験者フォルダの中では各コースのデータに四つの種類があります．

一つは視線データです．
例:reco13del.csv

一つは加速度データです．
例:reco13delAccelerometerData.csv

一つは角速度データです．
例:reco13delGyroscopeData.csv

一つは各データをソートしてラベルを付けて分散まで出したものです．
例:reco13bunsan.csv
