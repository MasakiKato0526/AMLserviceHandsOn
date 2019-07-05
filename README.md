# Azure Machine Lerning サービス ハンズオン

本ハンズオンでは、以下のシナリオを提供しています。

- ニューヨーク州タクシー運賃予測
    - ニューヨーク市のタクシーの乗車と降車に関するデータセット (日時、乗降車の座標、距離等) から、データのクレンジングを行った後にタクシー運賃の予測モデルを作成します。
    - 予測モデルは、Automatic MLを利用して作成します。
    - 訓練環境は、ローカル環境を使用します。
    - ハンズオンコンテンツは、NYCTaxi-Forecastフォルダにある以下のファイルになります。
        - Part1_Prepare_TaxiForecast_TrainingData.ipynb
        - Part2_Build_Model_TaxiForecast.ipynb
    - オリジナルのコンテンツは以下のサイトで公開しておりますが、本ハンズオンではコードの一部を変更しています。
        - https://docs.microsoft.com/ja-jp/azure/machine-learning/service/tutorial-data-prep
        - https://docs.microsoft.com/ja-jp/azure/machine-learning/service/tutorial-auto-train-models

- MNIST画像分類
    - MNISTデータセット (手書き数字画像) に対する画像の分類モデルを作成します。また、作成したモデルをWebサービスとしてデプロイし、推論を実行します。
    - 分類モデルは、scikit-learnを使用して作成します。
    - 訓練環境は、Azure上の仮想マシンクラスタを使用します。
    - 推論環境は、Azure Container Instancesを使用します。
    - ハンズオンコンテンツは、MNISTフォルダにある以下のファイルになります。
        - Part1_Train_MNISTClassificationModel.ipynb
        - Part2_Deploy_MNISTClassificationModel.ipynb
    - オリジナルのコンテンツは以下のサイトで公開しておりますが、本ハンズオンではコードの一部を変更しています。
        - https://docs.microsoft.com/ja-jp/azure/machine-learning/service/tutorial-train-models-with-aml
        - https://docs.microsoft.com/ja-jp/azure/machine-learning/service/tutorial-deploy-models-with-aml

※本デモコンテンツを実行する前に、初期設定.ipynbを実行して必要な設置を行ってください。