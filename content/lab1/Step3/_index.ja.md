+++
title = "MetaDefender Coreの管理"
weight = 13
pre = "<b>1-3. </b>"
+++

この章では、前章でインストールしたMetaDefender Coreの設定変更や管理を行います。


### 1-3-1. MetaDefender Coreの管理

1. Webブラウザ上のMetaDefender Core管理コンソールで「Get Started」をクリックします。
    ![](/images/lab1/1-1-3_mdc01.png)
1. 右上「Sign in」をクリックします。
    ![](/images/lab1/1-1-3_mdc02.png)
1.「ユーザ」「パスワード」を入力し、「Signin」をクリックします。
    ![](/images/lab1/1-1-3_mdc03.png)
    | ログインに必要な情報 | 内容 |
    | ---- | ---- |
    | ユーザ | opswat |
    | パスワード | Opswat!23 |
    
1.「Product Management Enrollment」が表示される場合は「Do not show this message at startup」チェック後、画面右上の「X」をクリックします。
    ![](/images/lab1/1-1-3_mdc04.png)
    
1. 左ペイン「Settings」「License」タブをクリックします。
例として下図ではライセンス有効期限が2023年12月31日まで。
MetaDefender Core for Windows 評価版、Metascan(マルチスキャン)8エンジン、Deep CDR(ファイル無害化)が有効であることが確認できます。
    ![](/images/lab1/1-1-3_mdc05.png)

1. 左ペイン「Inventory」を展開し「Modules」をクリックします。
各エンジンが最新版にアップデートされていること(インジケーターが緑)が確認できます。
    ![](/images/lab1/1-1-3_mdc06.png)

### 1-3-2. ファイル無害化機能(Deep CDR)の有効化
1. 左ペイン「Inventory」を展開し「Modules」をクリックします。
Deep CDRが最新版にアップデートされていること(インジケーターが緑)を確認します。
    ![](/images/lab1/1-1-3_mdc07.png)
    
1. 左ペイン「Workflow Management」を展開し「Workflows」をクリックします。その後、「File process」をクリックします。
    ![](/images/lab1/1-1-3_mdc08-2.png)

1. 「Deep CDR」タブをクリックします。その後、「Enable」をクリックします。
    ![](/images/lab1/1-1-3_mdc09-2.png)

1. 「Deep CDR is enabled」と表示されていることを確認し、下へスクロールし、「Enable for filetypes」の「Edit」をクリックします。
    ![](/images/lab1/1-1-3_mdc10-2.png)

1. 「Enable for all file types」をチェックし、「OK」をクリックします。
    ![](/images/lab1/1-1-3_mdc11-2.png)

1. 画面右上の、「Save changes」をクリックします。
    ![](/images/lab1/1-1-3_mdc12-2.png)

