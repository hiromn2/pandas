# Schema
## customers
Rows: 1,220
| Column | Dtype |
|---|---|
| customer_id | int64 |
| first_name | object |
| last_name | object |
| age | float64 |
| gender | object |
| city | object |
| state | object |
| signup_date | object |
| segment | object |
| membership_tier | object |
| preferred_channel | object |
| is_active | int64 |
| lifetime_value | float64 |

## products
Rows: 180
| Column | Dtype |
|---|---|
| product_id | int64 |
| product_name | object |
| category | object |
| subcategory | object |
| brand | object |
| price | float64 |
| cost | float64 |
| rating | float64 |
| launch_date | object |
| tags | object |
| is_discontinued | int64 |

## orders
Rows: 4,200
| Column | Dtype |
|---|---|
| order_id | int64 |
| customer_id | int64 |
| order_date | object |
| status | object |
| payment_method | object |
| shipping_fee | float64 |
| discount_amount | float64 |
| coupon_code | object |
| ship_city | object |
| delivery_days | float64 |

## order_items
Rows: 9,472
| Column | Dtype |
|---|---|
| order_item_id | int64 |
| order_id | int64 |
| product_id | int64 |
| quantity | int64 |
| unit_price | float64 |
| item_discount | float64 |

## payments
Rows: 4,200
| Column | Dtype |
|---|---|
| payment_id | int64 |
| order_id | int64 |
| amount_paid | float64 |
| currency | object |
| paid_at | object |
| payment_status | object |

## support_tickets
Rows: 1,800
| Column | Dtype |
|---|---|
| ticket_id | int64 |
| customer_id | int64 |
| order_id | float64 |
| created_at | object |
| issue_type | object |
| priority | object |
| status | object |
| channel | object |
| satisfaction_score | float64 |
| resolved_in_hours | float64 |

## marketing_touches
Rows: 2,400
| Column | Dtype |
|---|---|
| touch_id | int64 |
| customer_id | int64 |
| campaign_name | object |
| channel | object |
| sent_at | object |
| opened | int64 |
| clicked | int64 |
| converted | int64 |
| device_type | object |

## inventory
Rows: 180
| Column | Dtype |
|---|---|
| product_id | int64 |
| product_name | object |
| category | object |
| brand | object |
| warehouse | object |
| stock_on_hand | float64 |
| reorder_point | int64 |

## monthly_wide_sales
Rows: 3
| Column | Dtype |
|---|---|
| metric | object |
| 2025-03 | float64 |
| 2025-04 | float64 |
| 2025-05 | float64 |
| 2025-06 | float64 |
| 2025-07 | float64 |
| 2025-08 | float64 |
| 2025-09 | float64 |
| 2025-10 | float64 |
| 2025-11 | float64 |
| 2025-12 | float64 |
| 2026-01 | float64 |
| 2026-02 | float64 |

