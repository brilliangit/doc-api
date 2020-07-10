## Register Submit

> Request Register Submit

```json
{
	"msisdn": "628122937891",
	"otpCode": "432010",
	"otpRequestId": "at6a5p",
	"name": "Bajirut",
	"email": "bajirut@mail.com",
	"dob":"1995-07-11",
	"gender": "1",
	"password":"Xcode734"
}
```

URL: `POST https://api.dev.pointkita.com/completeregister`

**Parameter Register Submit**

Parameter | Nilai | Deskripsi
----------|-------|-----------
msisdn | string | 
otpCode | string | 
otpRequestId | string | 
name | string | 
email | string | 
dob | string | 
gender | string | 
password | string | 

> Response Register Submit

```json
{
    "responseCode": 200,
    "status": "ok",
    "message": "validate otp successfully"
}
{
    "responseCode": "201",
    "status": "error",
    "message": "Account already exist"
}
```

**Parameter Response Register Submit**

Parameter | Nilai | Deskripsi
----------|-------|-----------
responseCode| string |
status| string |
message| string | 
data| Object | 