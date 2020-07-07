## Submit Change Password

> Request Submit Change Password

```json 
{   
    "clientId": "rm885j",
    "oldPassword": "xcode734",
    "newPassword": "xcode1234"
}
```

URL: `PUT https://api.dev.pointkita.com/changepassword`

**Parameter Submit Change Password**

Parameter | Nilai | Deskripsi
----------|-------|-----------
clientId | string | rm885j
oldPassword | string | 
newPassword | string | 

> Response Submit Change Password

```json
{
  "responseCode": 200,
  "status": "ok",
  "message": "Change Password successfully"
}

{
  "responseCode": "202",
  "status": "error",
  "message": "Format password a minimum 8 characters password contains a combination of uppercase and alphanumeric"
}

{
  "responseCode": "203",
  "status": "error",
  "message": "New password cannot be the same as old password"
}


```

**Parameter Response Submit Change Password**

Parameter | Nilai | Deskripsi
----------|-------|-----------
responseCode| string |
status| string |
message| string | 