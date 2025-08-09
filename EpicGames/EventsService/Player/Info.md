## プレイヤー情報

APIエンドポイントURL: https://events-public-service-live.ol.epicgames.com/api/v1/players/:gameId/:accountId \
APIメソッド: GET \
認証は必要?: Yes (`{gameId}:profile:{accountId}:commands READ`)

## パスパラメータ

`gameId`: ゲームID(例:Fortnite) <br/>
`accountId`: アカウントID

---

_レスポンス例_

```json
{
  "gameId": "Fortnite",
  "accountId": "94b1569506b04f9f8557af611e8c5e47",
  "tokens": [
    "Arena_S24_Division1",
    "GroupIdentity_GeoIdentity_Germany",
    "GroupIdentity_Lele_is_Cool"
  ],
  "teams": {
    "epicgames_Arena_S24_Solo:Arena_S24_Division1_Solo": [
      "94b1569506b04f9f8557af611e8c5e47"
    ],
    "floating:Hype_S24": ["94b1569506b04f9f8557af611e8c5e47"]
  },
  "pendingPayouts": [],
  "pendingPenalties": {},
  "persistentScores": {
    "Hype_S24_P": 0
  },
  "groupIdentity": {
    "GeoIdentity": "Germany"
  }
}
```
