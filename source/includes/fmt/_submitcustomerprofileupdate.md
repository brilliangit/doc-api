## Update Customer Profile Data

> Request Update Customer Profile Data

```json 
{
    "clientId": "rm885j",
    "gender": "0",
    "name": "Junior As",
    "dob" : "19900101"    
}
```

URL: `PUT https://api.dev.pointkita.com/customer`

**Parameter Update Customer Profile Data**

Parameter | Nilai | Deskripsi
----------|-------|-----------
clientId | string | rm885j
gender | int | 0: male, 1: female
name | string | 
dob | string | 

> Response Update Customer Profile Data

```json
{
  "responseCode": 200,
  "status": "ok",
  "message": "Update profile data successfully"
}
```

**Parameter Response Update Customer Profile Data**

Parameter | Nilai | Deskripsi
----------|-------|-----------
responseCode| string |
status| string |
message| string | 