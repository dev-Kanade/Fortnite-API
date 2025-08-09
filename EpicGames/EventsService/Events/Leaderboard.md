## イベントウィンドウリーダーボード

APIエンドポイントURL: https://events-public-service-live.ol.epicgames.com/api/v1/leaderboards/:gameId/:eventId/:eventWindowId/:accountId \
APIメソッド: GET \
認証は必要？: Yes (`{gameId}:profile:{accountId}:commands READ`)

## パスパラメータ

`gameId`: 例:Fortnite <br/>
`eventId`: EventIDを指定 <br/>
`eventWindowId`: イベントプロパティを指定 <br/>
`accountId`: アカウントID

## クエリパラメータ

`page`: 0 (0 - 100) <br/>
`rank`: 1 (ページとランクが指定されている場合はランクが使用されます (例: 54 でもページ 1 に移動し、ランク 1 から開始されます)) <br/>
`showLiveSessions`: ブール値 <br/>
`teamAccountIds`: アカウントID（コンマ`,`で区切る) <br/>
`appId`: アプリID（例:Fortnite)
---

_レスポンス例_

```json
{
  "gameId": "Fortnite",
  "eventId": "epicgames_S24_DuosCashCup_EU",
  "eventWindowId": "S24_DuosCashCup_EU_Event1_Round1",
  "page": 0,
  "totalPages": 0,
  "updatedTime": "2023-05-30T19:13:27.317Z",
  "entries": [],
  "liveSessions": {}
}
```
