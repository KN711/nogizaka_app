# nogizaka_app
アイドル関係深層学習ファイル置き場。
基本的にgoogle colaboratoryでの実行を想定しています。

## NOGIZAKAGAN.ipynb
作成時点で最新のモデルに近い「Stylegan2-Ada」を使用して、乃木坂っぽいアイドルを生成します。
nogizaka_20210510.pklを使うことで、途中からスタートできます。

## yamashita_miduki_detector.ipynb

乃木坂46 山下美月と山本美月を見分けるディテクターです。  
使い方：全コードを実行し、出てくるuploadボタンを押し、山下美月か山本美月の画像をアップロード。その後、Classifyボタンを押すと、ディープラーニングにて作成したディテクターが山下美月か山本美月か見分けます。  
