---
name: Home
assetId: 3a3f56f7-dbd3-4b75-868b-614d637edd64
type: page
---

# Welcome

This is your new project's homepage. Edit this file to get started.

{% dropdown
    id="demo_dropdown"
    data="demo_daily_orders"
    value_column="category"
/%}

asdadsadsasdasd


{% area_chart
    data="demo_daily_orders"
    x="date"
    y="sum(total_sales)"
    filters=["demo_dropdown"]
/%}


{% logo
    domain="www.stripe.com"
/%}