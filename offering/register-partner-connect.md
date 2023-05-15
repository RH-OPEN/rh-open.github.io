---
sort: 2
---

# Red Hat Partner Connect アカウント作成手順

Red Hat Partner Connectは、Red Hatアカウントをご作成頂き、アカウントに対し「貴社パートナー企業アカウント」を紐付けして頂くことでアクセスが可能となります。

本書ではRed Hatアカウントを作成し、パートナー企業アカウントへの紐付けを行うための手順を示します。

## 前提条件

* Red Hatパートナー登録済み企業ドメインのメールアドレスが必要です。
  * フリーメールなど、パートナー企業様のドメインではないメールアドレスでは登録できません。
* Red Hatとのパートナー契約におけるパートナータイプ（リセラー、システムインテグレーターなど）を把握していること。
  * ご不明な場合、ご所属企業におけるRed Hat担当者様、またはRed Hatの担当営業までお問い合わせください。

## 手順

1. [パートナーコネクトログインページ](https://sso.redhat.com/auth/realms/redhat-external/protocol/saml/clients/redhat?RelayState=%2FDashboard_page)へアクセスを行います。

1. 表示されたメニューより、[Register for a Red Hat account]を選択します

   ![picture](https://github.com/RH-OPEN/rh-open.github.io/blob/main/offering/images/partner-connect/001.png?raw=true)

3. アカウント作成画面が表示されるため、必須項目（*表示）を全て入力頂きましたら画面下の[CREATE　MY ACCOUNT]をクリックして下さい。
下記の注意事項に従いご入力ください。

   ![picture](https://github.com/RH-OPEN/rh-open.github.io/blob/main/offering/images/partner-connect/002.png?raw=true)

      - Account typeは必ず「Corporate」（企業）をご選択下さい。登録後に変更はできません。「Personal」（個人）を選択されますと、パートナー企業への紐付けができません。
         ※ 誤ってPersonal (個人)で作成した場合には、別のIDを指定し新規作成をお願いします。

      - Choose a Red Hat login(Red Hat ログインID)は、5文字以上で設定して下さい。他のユーザーで使用済みのログインIDは登録することができません。

      - ログインIDは登録後、変更不可です。誤って作成された場合は別の文字列を指定し、新規作成をお願いいたします

      - “Personal infomation”のEmail addressには必ず所属企業のドメインのアドレスをご登録下さい。所属企業のドメインのメールアドレス以外をご使用頂いた場合、以降のパートナー企業との紐付けが実施できません

      - “Company infomation”の『Country/Region』はプルダウンよりJapanをご選択下さい。

1. 住所の検証の画面がポップアップ表示されます。[Keep entered address]をクリックして下さい。クリック後ポップアップが閉じ前画面に戻り、数秒の後に次画面へ遷移します。

   ![picture](https://github.com/RH-OPEN/rh-open.github.io/blob/main/offering/images/partner-connect/003.png?raw=true)

2. 登録したログインIDを既存の『貴社パートナー企業アカウント』へ追加紐付けして頂きます。以下の画面で[既存のパートナ企業に参加する]をクリックして下さい。

   ![picture](https://github.com/RH-OPEN/rh-open.github.io/blob/main/offering/images/partner-connect/004.png?raw=true)

3. メールアドレスと国を確認し、『パートナータイプ』を選択します。パートナータイプをご選択のうえ、画面下の[次のステップ]を選択ください。貴社のパートナータイプがご不明な場合、お手数おかけしますがRed Hatの担当営業までお問い合わせください。

   ![picture](https://github.com/RH-OPEN/rh-open.github.io/blob/main/offering/images/partner-connect/005.png?raw=true)


   英語表記にて申請を実施されている場合、下記の対応表をもとにパートナータイプを特定ください。

   |英語表記|日本語表記|
   | ---- | ---- |
   |Independent Software Vendor|独立系ソフトウェアベンダー|
   |Solution Provider|リセラー|
   |Training|Training|
   |System Integrator|システムインテグレーター|
   |Alliance Partners/OEM|アライアンスパートナー/OEM|
   |Embedded|Embedded|
   |Service/Cloud Provider|サービス/クラウドプロバイダー|


1. 表示された会社名から貴社名称にチェックし、[申請]ボタンをクリックして下さい。

     ![picture](https://github.com/RH-OPEN/rh-open.github.io/blob/main/offering/images/partner-connect/006.png?raw=true)

1. 正常に申請が完了しますと、こちらの画面が表示されます。画面下[プログラム]をクリックしホーム画面に戻って下さい。もしくはそのままタブを閉じて画面終了して下さい。

     ![picture](https://github.com/RH-OPEN/rh-open.github.io/blob/main/offering/images/partner-connect/007.png?raw=true)

1. ご登録頂いたメールアドレス宛てにシステムから以下のメールが配信されます。メール本文内のURLをクリックします。

      ```
      ​From: no-reply-partners@redhat.com <no-reply-partners@redhat.com>
      Subject: Red Hat Connect for Business Access Confirmation

      Thank you for your interest in our Red Hat Connect for Business partner portal.
      Please click the link below to verify access to the system. 
      Once you have clicked the link you will be directed to the partner portal login screen for access.
      If you have forgotten your username and/or password you may also request help from the login page.

      https://redhat.secure.force.com/partner/apex/PartnerEmailConfirmation?token=​*​****************

      Sincerely,
      Red Hat Partner Team
      ```
      
      ※ メール受信まで5〜15分程度お待ち下さい。メールが届かない場合は[こちら](https://www.redhat.com/wapps/sfconnector)からログインして下さい。
      

1. 遷移した画面にて[パートナーセンターにログイン]をクリックします。

     ![picture](https://github.com/RH-OPEN/rh-open.github.io/blob/main/offering/images/partner-connect/008.png?raw=true)

1. [REDHAT.COMアカウントへのログイン]をクリックして下さい。

     ![picture](https://github.com/RH-OPEN/rh-open.github.io/blob/main/offering/images/partner-connect/009.png?raw=true)

1. 下記のPARTNER DASHBOARD画面が表示されれば、本手順は終了です。

     ![picture](https://github.com/RH-OPEN/rh-open.github.io/blob/main/offering/images/partner-connect/010.png?raw=true)