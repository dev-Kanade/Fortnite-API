## IPデータサービス-リージョンの確認

URL: https://ip-data-service-prod.ecbc.live.use1a.on.epicgames.com/region/check \
メソッド: POST \
認証の有無: はい (`ipdata:region READ`)

```json
{
  "allow_on_error": false,
  "type": "continent",
  "limits": {
    "EU": "Res=656"
  },
  "content_id": "AF9yLAAsklQALFTy"
}
```

## パラメータ

`allow_on_error`: bool値 <br/>
`type`: 型 <br/>
`limits`: 不明 <br/>
`content_id`:Base64  (次を参照):

- `continent.geoname_id`
- `country.geoname_id`
- `subdivisions.geoname_id` (すべての要素)

__ 検索データの例（短縮版）_

```json
{
  "continent": {
    "geoname_id": 6255148
  },
  "country": {
    "geoname_id": 2921044
  },
  "subdivisions": [
    {
      "geoname_id": 2905330
    }
  ]
}
```

すべての数値は、ビッグエンディアンを使用したバイナリのInt32数値として記述する必要があります。
その場合、以下の値（ここでは16進数で表示）が得られます。Base64`00 5F72 2C 00 2C 92 54 00 2C 54 F2`の場合`AF9yLAAsklQALFTy`

---

_レスポンス例_

```json
{
  "content_id": "AF9yLAAsklQALFTy",
  "allowed": true,
  "resolved": true,
  "limit": "Res=656"
}
```
