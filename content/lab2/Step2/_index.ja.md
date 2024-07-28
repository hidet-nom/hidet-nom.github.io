+++
title = "MFT接続用アカウントの作成"
weight = 22
pre = "<b>2-2. </b>"
+++

この章では、MetaDefender Core 管理コンソール上でMFT接続用アカウントの作成を行います。

### 2-2-1. MetaDefender Core 管理コンソールへのログオン、MFT接続用アカウントの作成

1. MetaDefender Core 管理コンソールへのログオンします。Webブラウザから「http://localhost:8008」へ接続します。
またはデスクトップショートカットの「MetaDefender Core」をダブルクリックします。
    ![](/images/lab2/Kiosk000-01.PNG)
1. 「Sign in」をクリックします。
    ![](/images/lab2/Kiosk000-02.PNG)
1. MetaDefender Core 管理コンソールに以下の表に従って入力し、「Sign In」をクリックします。
    ![](/images/lab2/Kiosk000-03.PNG)
    
    | 項目 | 入力内容 | 備考 |
    | ---- | ---- | ---- |
    | Username | opswat | |
    | Password | Opswat!23 | |
    
1. 左ペインの「User Management」を選択し「+ Add User」をクリックします。
    ![](/images/lab2/Kiosk000-04.PNG)
1. 以下の表に従って入力し、すべて入力後「Generate」をクリック、最後に「Add」をクリックします。
    ![](/images/lab2/Kiosk002.PNG)
    ![](/images/lab2/Kiosk003.PNG)
    | 項目 | 入力内容 | 備考 |
    | ---- | ---- | ---- |
    | User directory | LOCAL | |
    | User name | mft | |
    | Display name | MFT | |
    | Password | Opswat!23 | |
    | Confirm password | Opswat!23 | |
    | Email | training@opswat.local | |
    | API key | Generate をクリックすると固有キーが作成される | |
    | Assign to roles | Administrators | |
    

1. 「mft」ユーザーが作成されたことを確認します。
    ![](/images/lab2/Kiosk004.PNG)

1. 「mft」ユーザーの「Edit」をクリックします。
    ![](/images/lab2/Kiosk000-05.PNG)

1. 「mft」ユーザーのAPIキーをコピーしておきます。この画面は開いたままにしておきます。
    ![](/images/lab2/Kiosk000-06.PNG)

「2-2-1. MFT接続用アカウントの作成」はこれで完了です。

