## アップロード完了

URL: https://emerald-service-live.ecosec.on.epicgames.com/emerald/v1/upload/complete \
メソッド: POST \
認証の有無: はい </br>
   トークンに必要な権限:`emerald:upload`:`CREATE`
```json
{
  "token": "VjF7ImMiOiJt...NvcmRpbmcuYmluIn1dfQ=="
}
```

## パラメータ

`token`:  [こちら](./Init.md)によって初期化されたアクセストークン

---

__レスポンス例(成功)__
</br>

ステータス:204
</br>
__レスポンス例(アップロード済み)__

```json
{
  "errorCode": "errors.com.epicgames.server_error",
  "errorMessage": "An unexpected server error has occurred.",
  "numericErrorCode": 1000,
  "messageVars": ["invalid item state: UploadFinished"],
  "originatingService": "com.epicgames.emerald-service",
  "intent": "live"
}
```
