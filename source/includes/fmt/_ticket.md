## Kirim Laporan (Ticket)

> Request Ticket

```json
{   
    "clientId": "rm885j",
    "message": "test laporan"
}
```
URL: `POST https://api.dev.pointkita.com/ticket`

**Parameter Ticket**

Parameter | Nilai | Deskripsi
----------|-------|-----------
clientId| string |
message| No Hp | 

> Response Ticket

```json
{
    "response_code": 200,
    "status": "ok",
    "message": "Success Insert Data",
    "data": {}
}
```

**Parameter Response Ticket**

Parameter | Nilai | Deskripsi
----------|-------|-----------
response_code| string |
status| string |
message| string | 
data| Object | 