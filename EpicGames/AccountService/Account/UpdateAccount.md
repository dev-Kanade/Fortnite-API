## アカウント更新

APIエンドポイントURL: https://account-public-service-prod.ol.epicgames.com/account/api/public/account/:accountId \
メソッド: PUT \
認証が必要？: はい (`account:public:account UPDATE`, 一部必要`account:public:account:sensitive UPDATE`)

```json
{
  "name": "_",
  "lastName": "_",
  "preferredLanguage": "de",
  "displayName": "lele stw moment",
  "phoneNumber": "0123456789",
  "company": "Lele Exploits",
  "email": "lele@example.com",
  "username": "lele",
  "password": "hey123!"
}
```

## パスパラメータ
`accountId`: アカウントID

## パラメータ

`name`: 変更後の名前 <br/>
`lastName`:変更後の性<br/>
`preferredLanguage`: 変更後の優先言語 <br/>
`displayName`:変更後のEpicID <br/>
`phoneNumber`: 変更後の電話番号<br/>
`company`: 変更後の会社<br/>
`email`: 変更後のメールアドレス <br/>
`username`: 変更後のユーザー名<br/>
`password`: 変更後のパスワード <br/>


---

_レスポンス例_

```json
{
  "accountInfo": {
    "id": "94b1569506b04f9f8557af611e8c5e47",
    "displayName": "lele stw moment",
    "email": "lele@example.com",
    "failedLoginAttempts": 0,
    "lastLogin": "2023-05-02T16:51:59.221Z",
    "numberOfDisplayNameChanges": 1,
    "dateOfBirth": "2000-01-03",
    "ageGroup": "ADULT",
    "headless": false,
    "country": "DE",
    "phoneNumber": "12345667890",
    "company": "Lele Exploits",
    "preferredLanguage": "de",
    "lastDisplayNameChange": "2022-09-10T08:07:47.361Z",
    "canUpdateDisplayName": true,
    "tfaEnabled": true,
    "emailVerified": true,
    "minorVerified": false,
    "minorExpected": false,
    "minorStatus": "NOT_MINOR",
    "cabinedMode": false,
    "hasHashedEmail": false
  }
}
```
