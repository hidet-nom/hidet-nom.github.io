+++
title = "MetaDefender Managed File Transfer (MFT) の初期設定"
weight = 43
pre = "<b>4-3. </b>"
+++

この章では、MetaDefender Managed File Transfer (MFT) 初期設定を行います。

### 4-3-1. MetaDefender Managed File Transfer (MFT) の初期設定

1. デスクトップショートカットの「MetaDefender Managed File Transfer」をクリックします。
    ![](/images/lab4/Kiosk15.PNG)
1. MetaDefender Managed File Transfer管理コンソールに以下の表に従って入力し、「Sign In」をクリックします。
    ![](/images/lab4/Kiosk16.PNG)
    
    | 項目 | 入力内容 | 備考 |
    | ---- | ---- | ---- |
    | Username | opswat | |
    | Password | Opswat1234567! | |
    
1. 左ペインの「Settings」「Security」「License」を選択し「Activate」をクリックします。
    ![](/images/lab4/Kiosk12.PNG)
1. 「sAyk-gNXp-YmnY-Esxt-bMYi-9bdF-7PXw-eEhd」を入力し「Activate online」をクリックします。
    ![](/images/lab4/Kiosk13.PNG)
1. このような画面になるのを確認します。
    ![](/images/lab4/Kiosk17.PNG)
1. 左ペインの「Settings」「Integration」「Core integration」を選択し「Add MetaDefender Core」をクリックします。
    ![](/images/lab4/Kiosk07-02.PNG)
1. 下の表の項目を入力し、MetaDefender CoreのMFTユーザーのAPI Key「24e256a006e869beb35a2bf94a9bd491a1e4」をコピーし「API Key」へ入力後、「Update」をクリックします。
    ![](/images/lab4/Kiosk005.PNG)
    
    | 項目 | 入力内容 | 備考 |
    | ---- | ---- | ---- |
    | Address | http://demo01.opswatjapan.com:10240/metascan_rest | |
    | API Key | 24e256a006e869beb35a2bf94a9bd491a1e4 | |
    | User agent | mft | |
    | Default workflow | MetaDefender Vault | |    

1. 「File Processing」が「Enabled」になったのを確認します。
    ![](/images/lab4/Kiosk11.PNG)
1. 左ペインの「Settings」「Global Settings」「Language」を選択し「Japanese」を選択「Update」をクリックします。
    ![](/images/lab4/Kiosk006.PNG)

「4-3-1. MetaDefender Managed File Transfer (MFT) 初期設定」はこれで完了です。

