## イベントリスト（データ）

APIエンドポイントURL: https://events-public-service-live.ol.epicgames.com/api/v1/events/:gameId/data/:accountId \
APIメソッド: GET \
認証は必要?: Yes (`{gameId}:profile:{accountId}:commands READ`)

## パスパラメータ

`gameId`: ゲームID(例:Fortnite) <br/>
`accountId`: アカウントID

## クエリパラメータ

`region`: 地域(デフォルトはEU) <br/>
`showPastEvents`: ブール値<br/>
`showPrivateEvents`: オプション、ブール値、アクセス権がない場合は例外をスローします (通常のユーザーはアクセス権がありません)

---

_レスポンス例_



```json
{
  "player": {
    "gameId": "Fortnite",
    "accountId": "94b1569506b04f9f8557af611e8c5e47",
    "tokens": [
      "Arena_S24_Division1",
      "GroupIdentity_GeoIdentity_Germany",
      "GroupIdentity_Lele_is_Cool"
    ],
    "teams": {},
    "pendingPayouts": [],
    "pendingPenalties": {},
    "persistentScores": {
      "Hype_S24_P": 0
    },
    "groupIdentity": {
      "GeoIdentity": "Germany"
    }
  },
  "events": [],
  "templates": [],
  "leaderboardDefs": [],
  "scoringRuleSets": {},
  "payoutTables": {},
  "scores": [],
  "resolvedWindowLocations": {}
}
```
