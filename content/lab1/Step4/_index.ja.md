+++
title = "ファイル処理の実行"
weight = 14
pre = "<b>1-4. </b>"
+++

この章では、MetaDefender Coreへファイルを送信し8エンジンによるマルチスキャンやDeep CDR(ファイル無害化)を行います。


### 1-4-1. ファイル処理の実行

1. ファイルエクスプローラで「C:\OPSWAT_Training\demo files」フォルダを開きます。
    ![](/images/lab1/1-1-4_mdc01.png)
1. 「demo.pdf」をMetaDefender CoreのProcess a fileへドラッグ&ドロップします。その後、「Process」をクリックします。
    ![](/images/lab1/1-1-4_mdc02-2.png)
1. レポート内の「MetaScan™」をクリックします。
    ![](/images/lab1/1-1-4_mdc03-2.png)
1. これは8つのエンジンでスキャンした結果、マルウェアやウィルスに感染してないことを示しています。「Deep CDR」をクリックします。
    ![](/images/lab1/1-1-4_mdc04-2.png)
1. [1]hyperlinkを展開します。これは無害化処理の一つとしてハイパーリンクを1個削除したことを示しています。その後、「View content」をクリックします。
    ![](/images/lab1/1-1-4_mdc05-3.png)
1. ハイパーリンク「http://malware-click.in/」を削除したことを示しています。確認後、右上の「Download processed file」クリックします。
    ![](/images/lab1/1-1-4_mdc05-4.png)
1. 無害化処理等が行われたファイルをダウンロードし、開きます。
    ![](/images/lab1/1-1-4_mdc06.png)
1. 無害化処理(Deep CDR)によりハイパーリンクが削除されたため「www.opswatdemo.com」をクリックしても「http://malware-click.in/」へリダイレクトされません。
    ![](/images/lab1/1-1-4_mdc07-2.png)
1. Chromeブラウザでオリジナルファイル「file:///C:/OPSWAT_Training/demo%20files/demo.pdf」を開き「www.opswatdemo.com」をクリックすると「http://malware-click.in/」へリダイレクトされてしまいます。
    ![](/images/lab1/1-1-4_mdc08-2.png)
    ![](/images/lab1/1-1-4_mdc09.png)

以上で「1-4-1. ファイル処理の実行」を完了します。
