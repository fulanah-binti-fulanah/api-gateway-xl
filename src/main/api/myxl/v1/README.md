

### Balance Share Fee Include Axis
GET http://localhost:3000/api/myxl/v1/postSharingsApiV1BalanceShareFeeIncludeAxis?

### Balance Share Inquiry
GET http://localhost:3000/api/myxl/v1/postSharingsApiV2BalanceShareInquiry?amount=100000&receiver=6281938064470&pin={{pin}}






### Stores Families
GET http://localhost:3000/api/myxl/v1/postApiV3XlStoresFamilies?

### Stores Options List
GET http://localhost:3000/api/myxl/v1/postApiV1XlStoresOptionsList?package_family_code=e3c4aedb-88c8-436a-af01-d773b2533907

### Stores Options Detail
GET http://localhost:3000/api/myxl/v1/postApiV1XlStoresOptionsDetail?package_option_code=U0NfXwwOc3qZxuNZkeHx5PbG57XPD9_hztsA6MSJTzVWON4gLK3zxLcAIycm5Lbznt_Jn89_wN-j03xTD275VIY

### Stores Options Addons
GET http://localhost:3000/api/myxl/v1/postApiV1XlStoresOptionsAddons?package_option_code=U0NfXyNBd9fySLiFz_MGO-phNyvVXRxyzq7SUkEYv9mUmurBdBSNyJdBNDhl8sYyjBAGf6SGazyU4yDSeHcq3fv0-w

### Payments Sync Purchase
GET http://localhost:3000/api/myxl/v1/postPaymentsApiV1SyncPurchase?item_code=U0NfXyNBd9fySLiFz_MGO-phNyvVXRxyzq7SUkEYv9mUmurBdBSNyJdBNDhl8sYyjBAGf6SGazyU4yDSeHcq3fv0-w&item_name=Xtra+Combo+Mini+%28Gift%29+9GB&item_price=22250&topup_number=6281938064470&pin={{pin}}






### Payments Pending
GET http://localhost:3000/api/myxl/v1/postPaymentsApiV1Pending?

### Payments Sync Pending
GET http://localhost:3000/api/myxl/v1/postPaymentsApiV1SyncPending?

### Payments All History
GET http://localhost:3000/api/myxl/v1/postPaymentsApiV2AllHistory?






### Packages Balance And Credit
GET http://localhost:3000/api/myxl/v1/postApiV1PackagesBalanceAndCredit?

### Profile
GET http://localhost:3000/api/myxl/v1/postApiV1Profile?






### Login
GET http://localhost:3000/api/myxl/v1/postApiV1AuthLogin?msisdn={{msisdn}}

### Login
GET http://localhost:3000/api/myxl/v1/postApiV1AuthLogin?otp={{otp}}

### Token Revoke
GET http://localhost:3000/api/myxl/v1/postAmOauth2RealmsXlTokenRevoke?

### Access Toke
GET http://localhost:3000/api/myxl/v1/postAmOauth2RealmsXlAccessToken?grant_type=refresh_token