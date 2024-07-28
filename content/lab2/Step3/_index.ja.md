+++
title = "MetaDefender Managed File Transfer (MFT) の初期設定"
weight = 23
pre = "<b>2-3. </b>"
+++

この章では、MetaDefender Managed File Transfer (MFT) 初期設定を行います。

### 2-3-1. MetaDefender Managed File Transfer (MFT) の初期設定

1. デスクトップショートカットの「MetaDefender Managed File Transfer」をクリックします。
    ![](/images/lab2/Kiosk15.PNG)
1. MetaDefender Managed File Transfer管理コンソールに以下の表に従って入力し、「Sign In」をクリックします。
    ![](/images/lab2/Kiosk16.PNG)
    
    | 項目 | 入力内容 | 備考 |
    | ---- | ---- | ---- |
    | Username | opswat | |
    | Password | Opswat!23456 | |
    
1. 左ペインの「Settings」「License」を選択し「Activate」をクリックします。
    ![](/images/lab2/Kiosk12.PNG)
1. 「sAyk-gNXp-YmnY-Esxt-bMYi-9bdF-7PXw-eEhd」を入力し「Activate online」をクリックします。
    ![](/images/lab2/Kiosk13.PNG)
1. このような画面になるのを確認します。
    ![](/images/lab2/Kiosk17.PNG)
1. 左ペインの「Settings」「Core integration」を選択し右側にある「…」「Edit MetaDefender Core Settings」をクリックします。
    ![](/images/lab2/Kiosk07-02.PNG)
1. 下の表の項目を入力し、MetaDefender CoreのMFTユーザー（「2-2-1 MFT接続用アカウントの作成」で取得した）のAPI Keyをコピーし「API Key」へ入力後、「Update」をクリックします。
    ![](/images/lab2/Kiosk005.PNG)
    
    | 項目 | 入力内容 | 備考 |
    | ---- | ---- | ---- |
    | Address | http://localhost:8008/ | |
    | API Key | 「2-2-1 MFT接続用アカウントの作成」で作成したmftユーザーのAPI キー | |
    | User agent | mft | |
    

1. 「File Processing」が「Enabled」になったのを確認します。
    ![](/images/lab2/Kiosk11.PNG)
1. 左ペインの「Settings」「Language」を選択し「Japanese」を選択「Update」をクリックします。
    ![](/images/lab2/Kiosk006.PNG)

「2-3-1. MetaDefender Managed File Transfer (MFT) 初期設定」はこれで完了です。

