## Register Request OTP

> Request Register Request OTP

```json
{
	"otpCode": "870898",
	"otpRequestId": "qlk8n2",
	"msisdn" : "081226001002"
}
```

URL: `POST https://api.dev.pointkita.com/registerotp`

**Parameter Register Request OTP**

Parameter | Nilai | Deskripsi
----------|-------|-----------
otpCode | string | user phone number
otpRequestId | string | user phone number
msisdn | string | user phone number

> Response Register Request OTP

```json
{
    "responseCode": 200,
    "status": "ok",
    "message": "validate otp successfully"
}
{
    "responseCode": "203",
    "status": "error",
    "message": "otp_code is failed"
}
```

**Parameter Response Register Request OTP**

Parameter | Nilai | Deskripsi
----------|-------|-----------
responseCode| string |
status| string |
message| string | 
data| Object | 