---
sort: 2
---

<style>
img {
    border: 1px red solid;
}
</style>

# Red Hat Partner Connect アカウント作成手順

Red Hat Partner Connectは、Red Hatアカウントをご作成頂き、アカウントに対し「貴社パートナー企業アカウント」を紐付けして頂くことでアクセスが可能となります。

本書ではRed Hatアカウントを作成し、パートナー企業アカウントへの紐付けを行うための手順を示します。

## 前提条件

* Red Hatパートナー登録済み企業ドメインのメールアドレスが必要です。
  * フリーメールなど、パートナー企業様のドメインではないメールアドレスでは登録できません。
* Red Hatとのパートナー契約におけるパートナータイプ（リセラー、システムインテグレーターなど）を把握していること。
  * ご不明な場合、ご所属企業におけるRed Hat担当者様、またはRed Hatの担当営業までお問い合わせください。

## 手順

1. [Red Hat Partner Connect](https://connect.redhat.com)へアクセスし、画面右上の `Log in` を選択します
   
   ![picture](images/partner-connect/n000.png?raw=true)

2. 表示されたメニューより、`Register for a Red Hat account` を選択します

   ![picture](images/partner-connect/n001.png?raw=true)

3. アカウント作成画面が表示されるため、下記の捕捉事項を参考に必須項目（*表示）を全て入力ください。

      * <b>Login infomationフィールド</b>
        * `Choose a Red Hat login` には任意のログインIDをご入力ください
  
      * <b>Personal infomationフィールド</b>
        * `Phone number` は国識別番号（81）からご入力ください
        * `Email address` には必ず所属企業のドメインのアドレスをご登録下さい。所属企業のドメインのメールアドレス以外をご使用頂いた場合、以降のパートナー企業との紐付けが実施できません
  
      * <b>Account typeフィールド</b>
        * 必ず `Corporate` をご選択ください。
        * 選択後、Contact infomationの入力欄が表示されますので、英語表記で会社の住所情報をご入力ください。

   ![picture](images/partner-connect/n002.png?raw=true)

4. 必要情報を全て入力後 `Create my account` をクリックして下さい。

   ![picture](images/partner-connect/n003.png?raw=true)

5. Address validationの画面が表示された場合、 <b>Suggested address</b> にリストされる企業情報をご確認頂き、正しいご所属企業情報が記載されている場合は選択のうえ `Accept change`を、正しいご所属企業の情報がない場合・または不明な場合は `Keep entered address` をクリックください。

   ![picture](images/partner-connect/n004.png?raw=true)

   選択後下記の画面が表示される場合がございますが、そのまま次のステップにお進みください。本画面は閉じても問題ございません。
   
   ![picture](images/partner-connect/n005.png?raw=true)

6. 作成したアカウントとご所属企業の紐付けを行います。[紐付け用のサイト](https://redhat.my.salesforce-sites.com/partner/PartnerAccess?action=join)へアクセスし、`REDHAT.COM アカウントへのログイン` をクリックして下さい。<br>
    ログインが要求された場合は、作成したIDとパスワードでログインを行なってください。

   ![picture](images/partner-connect/n006.png?raw=true)

7.  メールアドレスと国を確認し、『パートナータイプ』を選択します。パートナータイプをご選択のうえ、画面下の `次のステップ` を選択ください。貴社のパートナータイプがご不明な場合、お手数おかけしますがRed Hatの担当営業までお問い合わせください。

      ![picture](images/partner-connect/n007.png?raw=true)

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

8.  表示された会社名から貴社名称にチェックし、`申請` ボタンをクリックして下さい。

      ![picture](images/partner-connect/n008.png?raw=true)

9.  申請後、下記の画面が表示されたら次のステップに進みます。この画面は閉じても問題ございません。
    
      ![picture](images/partner-connect/n009.png?raw=true)

10. ご登録頂いたメールアドレス宛てにシステムから以下のメールが配信されます。メール本文内のURLをクリックします。
    
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
      
   ```tip
   メールにはハイパーリンクが含まれることから、お使いのメールシステムによっては迷惑メールへと振り分けられる場合がございます。メールが受信できない場合には迷惑メールボックスも合わせてご確認ください。
   ```

11. 遷移した画面にて `パートナーセンターにログイン` をクリックします。
    
      ![picture](images/partner-connect/n010.png?raw=true)
   
12. `REDHAT.COMアカウントへのログイン` をクリックして下さい。
    
      ![picture](images/partner-connect/n011.png?raw=true)

13. 下記のPARTNER DASHBOARD画面が表示されれば、本手順は終了です。

     ![picture](images/partner-connect/n012.png?raw=true)

```tip
アカウント作成に問題が発生した場合、お手数をおかけしますが弊社の[APAC Partner Helpdesk(apac-partner-helpdesk@redhat.com)](mailto:apac-partner-helpdesk@redhat.com)までメールで症状をご連絡ください。ご記載内容は日本語で問題ございません。
```



