## Favourite Voucher List

> Request Favourite Voucher List

```json
headers = 
{
    "Content-Type": "application/json",
    "Authorization": "token.user.accessToken"
}
```

URL: `GET https://api.dev.pointkita.com/favoritvoucher`

**Parameter Favourite Voucher List**

Parameter | Nilai | Deskripsi
----------|-------|-----------

> Response Favourite Voucher List

```json
{
  "responseCode": 200,
  "status": "ok",
  "message": "Success get favourite voucher",
  "data": [
    {
      "vourcherId": 1,
      "voucherName": "Sour Sally - Large White Skim",
      "voucherImages": "https://storage.googleapis.com/www.dev.pointkita.com/voucher/sour-sally.jpg",
      "voucherPrice": 50,
      "categoryId": 1,
      "type": 2,
      "descriptions": "Beli 1 gratis 1 Large White Skim yoghurt spesial dari Sour Sally"
    },
    {
      "vourcherId": 2,
      "voucherName": "Sour Sally - Special Discount 63 % For Second Item",
      "voucherImages": "https://storage.googleapis.com/www.dev.pointkita.com/voucher/sour-sally.jpg",
      "voucherPrice": 70,
      "categoryId": 1,
      "type": 2,
      "descriptions": "Dapatkan diskon 63 % untuk item kedua dengan limit Rp 30.000,00"
    },
    {
      "vourcherId": 3,
      "voucherName": "KFC - Free Fish Burger",
      "voucherImages": "https://storage.googleapis.com/www.dev.pointkita.com/voucher/kfc.jpg",
      "voucherPrice": 30,
      "categoryId": 1,
      "type": 2,
      "descriptions": "Dapatkan 1 porsi Fish Burger dengan voucher ini"
    },
    {
      "vourcherId": 4,
      "voucherName": "KFC - Diskon 50 %",
      "voucherImages": "https://storage.googleapis.com/www.dev.pointkita.com/voucher/kfc.jpg",
      "voucherPrice": 100,
      "categoryId": 1,
      "type": 2,
      "descriptions": "Dapatkan diskon 50 % hingga Rp 50.000,00 untuk pembelian apapun"
    }
  ]
}
```

**Parameter Response Favourite Voucher List**

Parameter | Nilai | Deskripsi
----------|-------|-----------
response_code| string |
status| string |
message| string | 
data| Object | 