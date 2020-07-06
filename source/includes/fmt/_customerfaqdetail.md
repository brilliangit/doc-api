## Customer FAQ Detail

> Request Customer FAQ Detail

```json
{
    "faqId" : 2
}
```

URL: `GET https://api.dev.pointkita.com/faqdetail/rm885j?faqId=2`

**Parameter Customer FAQ Detail**

Parameter | Nilai | Deskripsi
----------|-------|-----------
faqId | int

> Response Customer FAQ Detail

```json
{
    "response_code": 200,
    "status": "ok",
    "data": {
        "faqId": 2,
        "parentId": 0,
        "category": 1,
        "topicName": "Akun dan Profil",
        "description": "",
        "status": 1,
        "effectiveDate": "2020-06-15T12:20:37.000Z",
        "listChild": [
            {
                "faqId": 14,
                "parentId": 2,
                "category": 1,
                "topicName": "Kenapa saya tidak bisa registrasi?",
                "description": "POKU saat ini dijalankan dengan kapasitas terbatas, sehingga tidak semua orang bisa mendaftar di program ini.\r\nTunggu POKU untuk semua ya!",
                "status": 1,
                "type": 1,
                "effectiveDate": "2020-06-15T12:37:57.000Z"
            },
            {
                "faqId": 15,
                "parentId": 2,
                "category": 1,
                "topicName": "Kenapa saya tidak menerima OTP?",
                "description": "test message",
                "status": 1,
                "type": 1,
                "effectiveDate": "2020-06-15T12:37:57.000Z"
            },
            {
                "faqId": 16,
                "parentId": 2,
                "category": 1,
                "topicName": "Apakah saya bisa mengganti nomor HP yang didaftarkan di POKU?",
                "description": "test message",
                "status": 1,
                "type": 1,
                "effectiveDate": "2020-06-15T12:37:57.000Z"
            },
            {
                "faqId": 17,
                "parentId": 2,
                "category": 1,
                "topicName": "Bagaimana cara saya untuk naik tier?",
                "description": "test message",
                "status": 1,
                "type": 1,
                "effectiveDate": "2020-06-15T12:37:57.000Z"
            },
            {
                "faqId": 18,
                "parentId": 2,
                "category": 1,
                "topicName": "Bagaimana jika program loyalitas yang saya inginkan tidak ada?",
                "description": "test message",
                "status": 1,
                "type": 1,
                "effectiveDate": "2020-06-15T12:37:57.000Z"
            },
            {
                "faqId": 19,
                "parentId": 2,
                "category": 1,
                "topicName": "Bagaimana jika e-wallet yang saya inginkan tidak ada?",
                "description": "test message",
                "status": 1,
                "type": 1,
                "effectiveDate": "2020-06-15T12:37:57.000Z"
            },
            {
                "faqId": 20,
                "parentId": 2,
                "category": 1,
                "topicName": "bagaimana cara saya mengatur notifikasi SMS yang saya terima?",
                "description": "test message",
                "status": 1,
                "type": 1,
                "effectiveDate": "2020-06-15T12:37:57.000Z"
            },
            {
                "faqId": 21,
                "parentId": 2,
                "category": 1,
                "topicName": "Apa keuntungan dari menghubungkan partner?",
                "description": "test message",
                "status": 1,
                "type": 1,
                "effectiveDate": "2020-06-15T12:37:57.000Z"
            },
            {
                "faqId": 22,
                "parentId": 2,
                "category": 1,
                "topicName": "Bagaimana jika sya lupa kata sandi?",
                "description": "test message",
                "status": 1,
                "type": 1,
                "effectiveDate": "2020-06-15T12:37:57.000Z"
            }
        ]
    }
}
```

**Parameter Response Customer FAQ Detail**

Parameter | Nilai | Deskripsi
----------|-------|-----------
response_code| string |
status| string |
message| string | 
data| Object | 