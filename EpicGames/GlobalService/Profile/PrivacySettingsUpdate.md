## プロフィールの公開設定の更新

URL: https://global-profile-service.game-social.epicgames.com/profile/privacy_settings \
メソッド: POST \
認証の有無 : はい </br?
   トークンに必要な権限 : 指定なし

```json
{
  "namespace": "Fortnite",
  "privacy_settings": {
    "playRegion": "PUBLIC",
    "languages": "FRIENDS_ONLY",
    "badges": "PRIVATE"
  }
}
```

## パラメータ

`namespace`: 更新するゲームID。例:. `Fortnite` \
`playRegion` / `languages` / `badges`:これらのパラメータの値は以下のいずれかです。

- PUBLIC
- FRIENDS_ONLY
- PRIVATE

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
