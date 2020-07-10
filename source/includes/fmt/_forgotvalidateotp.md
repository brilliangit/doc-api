## Forgot Password Validate OTP

> Request Validate Request  OTP Forgot Password

```json
{
	"otpCode": "463261",
	"otpRequestId": "v33y3y",
	"msisdn" : "081357965616"
}
```

URL: `POST https://api.dev.pointkita.com/validateotpforgotpassword`

**Parameter Validate Request  OTP Forgot Password**

Parameter | Nilai | Deskripsi
----------|-------|-----------
otpCode | string | user phone number
otpRequestId | string | user phone number
msisdn | string | user phone number

> Response Validate Request  OTP Forgot Password

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

**Parameter Response Validate Request  OTP Forgot Password**

Parameter | Nilai | Deskripsi
----------|-------|-----------
responseCode| string |
status| string |
message| string | 
data| Object | 