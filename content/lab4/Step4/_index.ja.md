+++
title = "MetaDefender Managed File Transfer (MFT) へのファイルアップロード"
weight = 44
pre = "<b>4-4. </b>"
+++

この章では、MetaDefender Managed File Transfer (MFT) へのファイルアップロードを行います。

### 4-3-1. MetaDefender Managed File Transfer (MFT) へのファイルアップロード

1. デスクトップショートカットの「MetaDefender Managed File Transfer」をクリックします。
    ![](/images/lab4/Kiosk15.PNG)
1. MetaDefender Managed File Transfer管理コンソールに以下の表に従って入力し、「Sign In」をクリックします。
    ![](/images/lab4/Kiosk16.PNG)
    
    | 項目 | 入力内容 | 備考 |
    | ---- | ---- | ---- |
    | Username | opswat | |
    | Password | Opswat1234567! | |
    
1. 左ペインの「概要」「個人ファイル」を選択し「ファイルをアップロード」をクリックします。
    ![](/images/lab4/Kiosk007.PNG)
1. 「ファイルを追加」をクリックします。
    ![](/images/lab4/Kiosk008.PNG)
1. アドレスバーに「C:\OPSWAT_Training\demo」と入力し「demo.pdf」選択後「開く」をクリックします。
    ![](/images/lab4/Kiosk009.PNG)
1. 「アップロード」をクリックします。
    ![](/images/lab4/Kiosk010.PNG)
1. 状態が「スキャン中」から「無害化済み」になるまでしばらく待ちます。
    ![](/images/lab4/Kiosk011.PNG)
    ![](/images/lab4/Kiosk012.PNG)
1. ファイル名をクリックし詳細なレポートを確認します。
    ![](/images/lab4/Kiosk013-2.PNG)
    ![](/images/lab4/Kiosk013.PNG)
1. MetaDefender Core管理コンソールにログインし、左ペインの「History」「Processing」を選択しmftユーザーから送られてきた処理を確認します。
    ![](/images/lab4/Kiosk013-3.PNG)


「4-4-1. MetaDefender Managed File Transfer (MFT) へのファイルアップロード」はこれで完了です。

