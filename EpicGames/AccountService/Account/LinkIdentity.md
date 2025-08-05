## リンクタイプの設定

APIエンドポイントURL: https://account-public-service-prod.ol.epicgames.com/account/api/public/account/:accountId/linkIdentity \
メソッド: POST \
認証が必要？: はい (`account:public:account:linkedIdentity CREATE`)

```json
{
  "type": "unknown",
  "value": "something"
}
```

## パスパラメータ

`accountId`: アカウントID

## パラメータ

`type`: 不明 <br/>
`value`: 不明

---

_レスポンス例(無効)_

```json
{
  "errorCode": "errors.com.epicgames.bad_request",
  "errorMessage": "type TYPE is not supported to link",
  "messageVars": ["TYPE"],
  "numericErrorCode": 1001,
  "originatingService": "com.epicgames.account.public",
  "intent": "prod"
}
```
