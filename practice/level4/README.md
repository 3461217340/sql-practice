# SQL 第四层级综合练习

## 数据表结构

### user_info
- user_id
- register_time

### order_info
- order_id
- user_id
- order_time
- pay_amount
- order_status
- channel

### user_login
- user_id
- login_time

### product_info
- order_id
- product_id
- category
- sales_num

---

## 题目列表

1. 统计2026年1月1日的DAU、总GMV、客单价、付费率
2. 统计2026年1月每月的MAU、总订单数、退款率
3. 计算2026年1月1日新增用户的次日留存率、7日留存率
4. 找出2026年1月连续登录≥5天的用户，并统计每个用户的最长连续登录天数
5. 统计每个用户的首次下单时间、末次下单时间、下单次数、平均下单间隔天数，并标记流失用户
6. 统计2026年1月全渠道的曝光→点击→加购→下单→支付各环节转化率（假设表中含行为字段：expose曝光、click点击、cart加购，无数据视为未发生该行为）
7. 基于2026年1月订单数据，计算每个用户的R、F、M值
8. 基于上一题的R/F/M值，通过 CASE WHEN 完成 RFM 用户价值分层
9. 统计2026年1月各品类销售额Top3商品，展示品类、商品ID、销售额、排名
10. 统计2026年1月各渠道用户数、GMV、转化率
