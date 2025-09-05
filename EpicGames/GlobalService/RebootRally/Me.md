## リブートラリー - 自分のアカウントのステータス確認
URL: https://global-profile-service.game-social.epicgames.com/v1/rebootrally/eligibility \
メソッド: PUT (bodyの指定なし) \
認証の有無 : はい</br>
トークンに必要な権限 :指定なし

---

__レスポンス例__

```json
{
  "eligibility": [
    {
      "accountId": "94b1569506b04f9f8557af611e8c5e47",
      "isEligible": true,
      "isRallied": false
    }
  ]
}
```
