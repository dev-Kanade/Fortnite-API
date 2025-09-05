## プロフィール - リージョンの設定

URL: https://global-profile-service.game-social.epicgames.com/profile/play_region \
メソッド: PUT \
認証の有無 : はい</br>
   トークンに必要な権限 : 指定なし

```json
{
  "namespace": "Fortnite",
  "play_region": "EUROPE"
}
```

## パラメータ

`namespace`: 変更するゲームID。例： `Fortnite` \
`play_region`:　このパラメータの値は以下のいずれかを指定してください。

- UNDEFINED_REGION
- NA_CENTRAL
- NA_EAST
- NA_WEST
- EUROPE
- OCEANIA
- BRAZIL
- ASIA
- MIDDLE_EAST

---

__レスポンス例__

```json
{}
```
