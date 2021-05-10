# nogizaka_app
アイドル関係深層学習ファイル置き場。
基本的にgoogle colaboratoryでの実行を想定しています。

## NOGIZAKAGAN.ipynb
[Open with Colab](https://colab.research.google.com/github/KN711/nogizaka_app/blob/master/NOGIZAKAGAN.ipynb)

作成時点で最新のモデルに近い「Stylegan2-Ada」を使用して、乃木坂っぽいアイドルを生成することを目的としたコードです。
最初に作成する nogizakaGAN/Image フォルダに好みのアイドル画像（サンプルコードは512*512以上想定、１０００枚程度）を置くことで学習ができます。
２４時間程度の学習で、最終行の画像が生成できました。

## yamashita_miduki_detector.ipynb
[Open with Colab](https://colab.research.google.com/github/KN711/nogizaka_app/blob/master/yamashita_miduki_detector.ipynb)

乃木坂46 山下美月と山本美月を見分けるディテクターです。  
使い方：google上の適当な場所にmiduki.pklを配置し、読み込めるようにしたのち、全コードを実行し、出てくるuploadボタンを押し、山下美月か山本美月の画像をアップロード。
その後、Classifyボタンを押すと、ディープラーニングにて作成したディテクターが山下美月か山本美月か見分けます。  
