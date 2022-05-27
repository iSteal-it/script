var obj = JSON.parse($response.body);

obj={
  "status": "success",
  "response": [
    {
      "status": "SUBSCRIPTION_PURCHASED",
      "is_trial": true,
      "order_id": "450001131447088",
      "plan_meta": {
        "id": "com.picsart.studio.subscription_plus_monthly",
        "frequency": "monthly",
        "type": "renewable",
        "scope_id": "full",
        "product_id": "subscription_plus_monthly",
        "description": "plus"
      },
      "limitation": {
        "max_count": 10,
        "limits_exceeded": false
      },
      "expire_date": 1753929830000,
      "purchase_date": 1653670630000,
      "subscription_id": "com.picsart.studio.subscription_plus_monthly",
      "original_order_id": "450001131447088",
      "is_eligible_for_grant": false,
      "is_eligible_for_introductory": false,
      "reason": "ok"
    }
  ]
}
$done({body: JSON.stringify(obj)});
