## プレイヤートークン

APIエンドポイントURL: https://events-public-service-live.ol.epicgames.com/api/v1/players/:gameId/tokens \
APIメソッド: GET \
認証は必要?: Yes

## パスパラメータ

`gameId`: ゲームID(例:Fortnite)

## クエリパラメータ

`teamAccountIds`: アカウントID

---

_レスポンス例_

```json
{
  "accounts": [
    {
      "accountId": "94b1569506b04f9f8557af611e8c5e47",
      "tokens": [
        "Arena_S24_Division1",
        "GroupIdentity_GeoIdentity_Germany",
        "GroupIdentity_Lele_is_Cool"
      ]
    }
  ]
}
```
