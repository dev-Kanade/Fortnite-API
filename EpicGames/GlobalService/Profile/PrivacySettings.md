## プロフィールの公開設定

URL: https://global-profile-service.game-social.epicgames.com/profile/privacy_settings \
芽おっど: PUT \
認証の有無 : はい </br>
   トークンに必要な権限: 指定なし
   
```json
{
  "namespace": "Fortnite"
}
```

## パラメータ

`namespace`: 取得するゲームID。例： `Fortnite`

---

__レスポンス例__

```json
{
  "privacySettings": {
    "playRegion": "PRIVATE",
    "badges": "FRIENDS_ONLY",
    "languages": "PUBLIC"
  }
}
```
