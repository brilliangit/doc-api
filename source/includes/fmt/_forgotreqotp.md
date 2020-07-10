## Forgot Password Request OTP

> Request Forgot Password Request OTP

```json
{
	"msisdn": "081357965616"
}
```

URL: `POST https://api.dev.pointkita.com/requestotpforgotpassword`

**Parameter Forgot Password Request OTP**

Parameter | Nilai | Deskripsi
----------|-------|-----------
msisdn | number | user phone number

> Response Forgot Password Request OTP

```json
{
    "responseCode": 200,
    "status": "ok",
    "data": {
        "otpCode": "463261",
        "otpRequestId": "v33y3y",
        "smsResult": "4632614e6df6e8043181f4503f1da390268894ab00000Success"
    }
}
```

**Parameter Response Forgot Password Request OTP**

Parameter | Nilai | Deskripsi
----------|-------|-----------
responseCode| string |
status| string |
message| string | 
data| Object | 