## プロフィール情報の取得

URL: https://global-profile-service.game-social.epicgames.com/profiles \
メソッド: PUT \
認証の有無 : はい</br>
   トークンに必要な権限 : 指定なし

```json
{
  "namespace": "Fortnite",
  "accountIds": [
    "94b1569506b04f9f8557af611e8c5e47",
    "d1d7a59146f14b4b9f76a5cb00a38f41"
  ]
}
```

## パラメータ

`namespace`: ゲームID。例: `Fortnite` \
`accountIds`: アカウントID(最大100個)

---

__レスポンス例__

```json
{
  "profiles": [
    {
      "accountId": "94b1569506b04f9f8557af611e8c5e47",
      "hasBattlePass": false,
      "playRegion": "EUROPE",
      "hasCrewMembership": false,
      "languages": ["en"],
      "seasonLevel": 10
    },
    {
      "accountId": "d1d7a59146f14b4b9f76a5cb00a38f41",
      "playRegion": "UNDEFINED_REGION",
      "languages": []
    }
  ]
}
```
