# Practice Prompts

## 1) Inspection / profiling
1. Show the number of rows and columns in each table.
2. Which columns have missing values, and how many?
3. Which columns look like keys? Verify uniqueness with `nunique`.

## 2) Filtering / selection
4. Find active gold or platinum customers from Sao Paulo older than 30.
5. Show orders placed in 2025 that were cancelled or returned.
6. Select products in Electronics and Beauty with rating >= 4.5.

## 3) Sorting / top-k
7. Top 10 customers by lifetime_value.
8. Top 10 products by average rating within each category.

## 4) Groupby / agg
9. Compute revenue by month.
10. Compute average age, customer count, and average lifetime_value by membership_tier.
11. Count orders by status and payment_method.

## 5) Merge / join
12. Join orders with customers and compute order count by city.
13. Join order_items with products and find revenue by category.
14. Join support_tickets with orders to compare ticket volume by order status.

## 6) Assign / transform
15. Add a net_item_revenue column = quantity * unit_price - item_discount.
16. Within each order, compute each item's share of order revenue using `transform`.
17. Compute customer-level total spend and merge it back to customers.

## 7) Pivot / reshape
18. Create a pivot table of revenue by category and order month.
19. Use `monthly_wide_sales` and `melt` to convert wide months into a tidy long table.
20. Build a pivot of ticket count by issue_type and status.

## 8) Missing values / cleaning
21. Fill missing ages with the median age.
22. Fill missing product prices with category-level median prices.
23. Detect duplicate-like customer records with the same name and signup_date.

## 9) Text / list-like columns
24. Split `products.tags` into lists and `explode` them.
25. Count how often each tag appears overall and by category.
26. Standardize customer first names to title case.

## 10) Dates
27. Convert all date columns to datetime.
28. Extract year, month, weekday from orders.
29. Compute days since signup for each customer relative to the latest order date.

## 11) Intermediate case drills
30. Which marketing channel has the highest conversion rate?
31. Do support tickets correlate with lower satisfaction by issue type?
32. Which cities have the highest average order value?
33. Which membership tier generates the most revenue per active customer?

## 12) Harder interview-style drills
34. Find the top 3 products by revenue within each category.
35. Compute 30-day repeat purchase rate by signup cohort month.
36. Build a customer summary table with:
   - total orders
   - total spend
   - average order value
   - days since signup
   - most recent order date
   - whether they ever opened a marketing message
