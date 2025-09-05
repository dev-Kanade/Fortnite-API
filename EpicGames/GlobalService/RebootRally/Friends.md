## リブートラリー - アカウントステータスの確認

URL: https://global-profile-service.game-social.epicgames.com/v1/rebootrally/eligibility/friends \
メソッド: PUT (bodyの指定なし) \
認証の有無 : はい </br>
   トークンに必要な権限:指定なし

---

__レスポンス例__

```json
{
  "eligibility": [
    {
      "accountId": "38df865effdd4c54a17ef8722cb2dc3b",
      "isEligible": true,
      "isRallied": false
    },
    {
      "accountId": "081825b3693b43579cdcd10c1ed1c2d3",
      "isEligible": false,
      "isRallied": false
    },
    {
      "accountId": "4f617d1f94a244f2a8f1f20d5e338fd1",
      "isEligible": true,
      "isRallied": true
    }
  ]
}
```
