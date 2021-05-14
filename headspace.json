var obj = JSON.parse($response.body);

obj={
  "links" : {
    "self" : "/subscription/user-subscriptions/{userSubscriptionId}"
  },
  "included" : [
    {
      "type" : "subscriptions",
      "id" : "HSUSER_VWFD10R5IIO0KZCMB",
      "attributes" : {
        "id" : "HSUSER_VWFD10R5IIO0KZCMB",
        "name" : "iOS Annual (14-day free trial)",
        "subscriptionId" : "HSSUBS_B2CSUBSCRIBER"
      }
    },
    {
      "type" : "vouchers",
      "id" : "9352483",
      "attributes" : {
        "planId" : 171,
        "id" : "9352483",
        "code" : "IOSIAP_FT_14D_ANNUAL",
        "numMonths" : 12,
        "voucherId" : "171",
        "platform" : "iap",
        "name" : "iOS Annual (14-day free trial)"
      }
    }
  ],
  "data" : {
    "id" : "9352483",
    "relationships" : {
      "voucher" : {
        "data" : {
          "type" : "vouchers",
          "id" : "9352483"
        }
      },
      "subscription" : {
        "data" : {
          "type" : "subscriptions",
          "id" : "HSUSER_VWFD10R5IIO0KZCMB"
        }
      }
    },
    "type" : "userSubscriptions",
    "attributes" : {
      "status" : "ACTIVE",
      "nextRenewalDate" : "2090-05-24T08:04:30.000Z",
      "endDate" : "2090-05-24T08:04:30.000Z",
      "id" : "9352483",
      "startDate" : "2021-05-10T08:04:30.000Z",
      "cancelled" : false,
      "userSubscriptionId" : "9352483",
      "subscriptionDetails" : {
        "planAffiliation" : null,
        "term" : 12,
        "membership" : "PRIMARY",
        "platform" : "APPLE",
        "planCategory" : "FREE_TRIAL",
        "version" : "V3",
        "externalId" : "6098e9520cd650000aecc456",
        "businessModel" : "B2C"
      },
      "isV3Subscription" : true
    }
  }
}
$done({body: JSON.stringify(obj)});
