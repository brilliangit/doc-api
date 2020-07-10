---
title: POKU API Documentation

language_tabs: # must be one of https://git.io/vQNgJ
  - JSON

toc_footers:
  - Poku Documentation
  - <a href='https://github.com/slatedocs/slate'>Documentation Powered by Slate</a>

includes:
  - fmt/login
  - fmt/checkmsisdn
  - fmt/checkemail
  - fmt/registerreqotp
  - fmt/registervalidateotp
  # - fmt/register
  - fmt/customerdataprofile
  - fmt/feedback
  - fmt/ticket
  - fmt/customerfaq
  - fmt/customerfaqdetail
  - fmt/preferenceinterest
  - fmt/customerinterestoption
  - fmt/submitcustomerinterest
  - fmt/submitcustomerprofileupdate
  - fmt/customersettingnotif
  - fmt/submitcustomersettingnotif
  - fmt/changepassword
  - fmt/categoryvoucher
  - fmt/favoritevoucher
  - fmt/recommendationvoucher
  - fmt/recommendationdetail
  - fmt/earnpartnerpoku
  - fmt/earnpartnerdetail
  - fmt/tier
  - fmt/customerpoint
  - errors
search: true

code_clipboard: true
---

# Beranda

Selamat datang di Dokumentasi API POKU!

Di sini Anda akan mendapatkan informasi cara integrasi Poku Backend.
### Target URL API

Environment | Target URL
-------| ----------
Development | `https://api.dev.pointkita.com`  
Production  | 

ketentuan untuk melakukan request ke Backend Poku :

1. menyertahan header `Content-Type: application/json`
2. menyertahan header `Authorization: 45r43ijuiyueyhfudiu`
  , cara generate `Authorization` [Referensi API > Login > Generate Token](#login)

# Referensi Api

