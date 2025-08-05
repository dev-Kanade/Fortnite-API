## 資格情報の検証

APIエンドポイントURL: https://account-public-service-prod.ol.epicgames.com/account/api/public/account/:accountId/validateCreds \
メソッド: POST \
認証が必要？: はい (`account:public:account:validateCreds READ`)

## HTTPヘッダー

`Content-Type`: `application/x-www-form-urlencoded`

<br/>

```
usernameOrEmail=XXX&password=YYY
```

## パスパラメータ

`accountId`: アカウントID

## パラメータ

`usernameOrEmail`: アカウントの `email` か `username`  <br/>
`password`: パスワード (in plain text)

---

_レスポンス例（有効時）_

Status 204

<br/>

_レスポンス例(無効)_

Status 401

```json
{
  "errorCode": "errors.com.epicgames.account.invalid_account_credentials",
  "errorMessage": "Sorry the credentials you are using are invalid",
  "messageVars": [],
  "numericErrorCode": 18031,
  "originatingService": "com.epicgames.account.public",
  "intent": "prod"
}
```
