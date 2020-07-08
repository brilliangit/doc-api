## Tier and Points

> Request Tier and Points

```json
headers = {
    "Content-Type": "application/json",
    "Authorization": "token.user.accessToken"
}
```

URL: `GET https://api.dev.pointkita.com/tier/rm885j`

**Parameter Tier and Points**

Parameter | Nilai | Deskripsi
----------|-------|-----------
clientId | string | rm885j

> Response Tier and Points

```json
{
  "response_code": 200,
  "status": "ok",
  "message": "Success Get Tier Data",
  "data": [
    {
      "tierId": 1,
      "tierName": "BRONZE",
      "tierMinimumPoint": 0,
      "tierMaximumPoint": 1000,
      "tierBenefit": [
        {
          "benefit": "KUOTA",
          "description": "Gratis 100 MB kuota Telkomsel pada bulan pertama."
        }
      ]
    },
    {
      "tierId": 2,
      "tierName": "SILVER",
      "tierMinimumPoint": 1001,
      "tierMaximumPoint": 2000,
      "tierBenefit": [
        {
          "benefit": "KUOTA",
          "description": "Gratis 500 MB kuota Telkomsel pada bulan pertama."
        }
      ]
    },
    {
      "tierId": 3,
      "tierName": "GOLD",
      "tierMinimumPoint": 2001,
      "tierMaximumPoint": 3000,
      "tierBenefit": [
        {
          "benefit": "KUOTA",
          "description": "Gratis 1,5 GB kuota Telkomsel pada bulan pertama."
        },
        {
          "benefit": "FREE OF CHARGE",
          "description": "Bebas akses aplikasi POKU tanpa kuota menggunakan Telkomsel."
        }
      ]
    },
    {
      "tierId": 4,
      "tierName": "PLATINUM",
      "tierMinimumPoint": 3001,
      "tierMaximumPoint": 4000,
      "tierBenefit": [
        {
          "benefit": "KUOTA",
          "description": "Gratis 10 GB kuota Telkomsel pada bulan pertama."
        },
        {
          "benefit": "FREE OF CHARGE",
          "description": "Bebas akses aplikasi POKU tanpa kuota menggunakan Telkomsel."
        },
        {
          "benefit": "FREE DRINKS",
          "description": "Gratis 1 cup minuman di Talktime setiap minggu."
        }
      ]
    }
  ]
}
```

**Parameter Response Tier and Points**

Parameter | Nilai | Deskripsi
----------|-------|-----------
response_code| string |
status| string |
message| string | 
data| Object | 