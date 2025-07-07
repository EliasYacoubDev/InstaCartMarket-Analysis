Research Questions

1️. Which aisles and departments are most visited?
    Why:

        Helps category managers optimize inventory

        Guides promotional planning

        Reveals customer preferences

    Approach:

        Count orders by aisle and department

        Rank by frequency

2️. Most frequently commanded (popular) products?
    Why:

        Identify best sellers

        Supports marketing and promotions

        Ensures stock levels match demand

    Approach:

        Count product-level purchases

        Rank by frequency

3️. Most frequent order days?
    Why:

        Guides staffing and logistics

        Understand shopping cycle patterns

    Approach:

        Count orders by day of the week (order_dow)

        Visualize order distribution

4️. Most frequent order time?
    Why:

        Optimize delivery windows

        Identify peak demand hours

    Approach:

        Analyze order_hour_of_day

        Visualize hourly demand

    | Bin   | Meaning                  |
    | ----- | ------------------------ |
    | 0–3   | late night / overnight   |
    | 3–6   | very early morning       |
    | 6–9   | morning (breakfast time) |
    | 9–12  | late morning             |
    | 12–15 | early afternoon / lunch  |
    | 15–18 | afternoon / after school |
    | 18–21 | evening / dinner time    |
    | 21–24 | night                    |


5️. Top ordering users?
    Why:

        Identify VIP customers

        Tailor loyalty programs

        Prioritize high-value shoppers

    Approach:

        Rank users by total number of orders (order_number)

6. Grouping Per User
    For each user, we will explore:

        1. Top 10 products ordered
        2. Reordered products
        3. Product placement in cart (add-to-cart order)
        4. Weekly ordering patterns (preferred days)
        5. Preferred ordering time ranges (binned in 3-hour intervals)
        6. Average reorder cycle (days_since_prior_order)

    Why:

        Enables personalized recommendations

        Provides customer segmentation

        Optimizes replenishment strategies

7. Reorder Ratio per Department

    Which departments have the highest repeat rates?

    Insightful for retention campaigns

8. Cart Size Distribution

    Understand average basket size

    Plan logistics and packaging

9. Time Between Orders Distribution

    Reveal customer ordering cycles

    Plan push notifications and reminders

10. User Churn Risk

    Identify users with no activity in the past 30 days

    Develop win-back marketing strategies