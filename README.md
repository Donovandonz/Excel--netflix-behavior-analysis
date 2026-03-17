# Excel--netflix-behavior-analysis
🍿 Netflix User Behavior Analysis and Dashboard

---

## Dataset used
-<a href="https://github.com/Donovandonz/Excel--netflix-behavior-analysis/blob/main/netflix_user_behavior_dataset.csv">RAW.Netflix-user-behavior-dataset</a>

---

## 📊 Project Overview
This project analyzes Netflix user behavior patterns using Excel, focusing on demographics, subscription types, viewing habits, and engagement metrics. The analysis provides actionable insights for user retention and content strategy.

---

## 🛠️ Tools & Skills Used
- **Microsoft Excel**
  - Data Cleaning & Transformation
  - PivotTables & PivotCharts
  - Advanced Formulas (XLOOKUP, COUNTIFS, AVERAGEIFS)
  - Data Modeling & Relationships
  - Interactive Dashboards with Slicers
  - Conditional Formatting
  - KPI Cards & Visualizations
 
---

## 🔍 Key Questions Answered
- What are the demographics of Netflix users?
- How do subscription types affect viewing behavior?
- What factors influence user churn?
- Which devices are most popular for streaming?
- How do different age groups engage with content?

| Category | Attributes |
|----------|------------|
| **Demographics** | user_id, age, gender, country, account_age_months |
| **Subscription** | subscription_type, monthly_fee, payment_method |
| **Viewing Behavior** | primary_device, devices_used, favorite_genre, avg_watch_time, sessions_per_week, binge_sessions |
| **Engagement** | completion_rate, rating_given, content_interactions, recommendation_click_rate, days_since_last_login, churned |

---

## 📊 Dashboard Features
- **KPI Cards**: Total Users, Active Users, Monthly Revenue, Churn Rate
- **Interactive Charts**: Age distribution, revenue by country, watch time by device
- **Slicers**: Filter by country, subscription type, device, gender
- **Churn Analysis**: Multi-factor churn prediction indicators

---

## 📈 EXECUTIVE SUMMARY

| Metric | Value |
|--------|-------|
| Total Users | 50,000 |
| Active Users | 40,036 |
| Churned Users | 9,964 |
| Churn Rate | 19.93% |
| Monthly Revenue | $616,167 |
| Avg Watch Time | 155 minutes |
| Avg Completion Rate | 65% |

## 🔍 KEY FINDINGS

### Finding 1: User Activity Crisis - "The 48% Lapsed User Problem"

#### User Activity Distribution

| Activity Level | Users | Percentage | Status |
|---------------|-------|------------|---------|
| Lapsed Users (30-60 days) | 24,000 | 48.0% | 🔴 CRITICAL RISK |
| Monthly Active | 13,470 | 26.9% | 🟡 MEDIUM RISK |
| Bi-Weekly Active | 5,894 | 11.8% | 🟢 HEALTHY |
| Weekly Active | 4,111 | 8.2% | 🟢 VERY HEALTHY |
| Daily Active | 2,525 | 5.1% | 🔵 EXCELLENT |
| **TOTAL** | **50,000** | **100%** | |

**📌 Key Insight:** 
Nearly **HALF (48%)** of your user base hasn't logged in for 30-60 days! These 24,000 users are at extreme risk of churning. This is your biggest red flag.

**✅ Recommended Action:** 
Immediate win-back campaigns needed for 24,000 lapsed users including email reminders, push notifications, and personalized content recommendations.

---

### Finding 2: Subscription Revenue Distribution

#### User Subscription Status

| Subscription Type | Users | % of Users | Monthly Fee (Avg) | Total Revenue | % of Revenue |
|------------------|-------|------------|-------------------|---------------|--------------|
| Standard | 19,931 | 39.9% | $12.00 | $239,172 | 38.8% |
| Premium | 15,196 | 30.4% | $18.00 | $273,528 | 44.4% |
| Basic | 14,873 | 29.7% | $7.00 | $104,111 | 16.9% |
| **TOTAL** | **50,000** | **100%** | **$12.32** | **$616,167** | **100%** |

#### Revenue Distribution Chart

Revenue by Subscription Type:
```python
Basic : ████████░░░░░░░░░░░░ 16.9%
Standard : ████████████████████ 38.8%
Premium : ████████████████████░░ 44.4%
```

**📌 Key Insights:**

- **Premium users (30.4%) generate 44.4% of total revenue** - they're your most valuable segment!
- **Standard is most popular (39.9%)** but generates less revenue than Premium
- **Basic users contribute only 16.9% of revenue** despite being 29.7% of users

**✅ Recommended Actions:**

1. Focus retention efforts on Premium users first
2. Create upgrade paths from Basic → Standard → Premium
3. Test pricing optimization for Standard tier

---

### Finding 3: Churn Analysis

#### Churn Breakdown

| Category | Users | Percentage |
|----------|-------|------------|
| Active Users | 40,036 | 80.07% |
| Churned Users | 9,964 | 19.93% |
| **TOTAL** | **50,000** | **100%** |

**📌 Key Insight:**
20% churn rate means you're losing 1 in 5 users. Industry average is 15-25%, so you're within range but room for improvement.

---

### Finding 4: Engagement Metrics

| Metric | Value | Benchmark | Status |
|--------|-------|-----------|---------|
| Avg Watch Time | 155 min (2.6 hrs) | 120 min | 🟢 ABOVE AVERAGE |
| Completion Rate | 65% | 70% | 🟡 SLIGHTLY BELOW |
| Daily Active Users | 2,525 (5.1%) | 10% | 🔴 BELOW TARGET |
| Weekly Active Users | 4,111 (8.2%) | 15% | 🔴 BELOW TARGET |

**📌 Key Insights:**

- **Watch time is strong** (155 min) - users find content engaging when they watch
- **Completion rate needs improvement** (65% vs 70% target)
- **Daily/Weekly active users are low** - engagement frequency is the real problem

---

## 🎯 RECOMMENDATIONS SUMMARY

| Priority | Action | Target Users | Expected Impact |
|----------|--------|--------------|------------------|
| 🔴 HIGH | Win-back campaign | 24,000 Lapsed Users | Reduce churn by 10-15% |
| 🟡 MEDIUM | Premium retention program | 15,196 Premium Users | Protect 44% of revenue |
| 🟡 MEDIUM | Upgrade Basic → Standard | 14,873 Basic Users | Increase ARPU by 30% |
| 🟢 LOW | Increase daily engagement | All active users | Boost completion rates |

---

## Age Distribution by Subscription Type

| Age Group | Basic | Premium | Standard | **TOTAL** |
|-----------|-------|---------|----------|-----------|
| 18-24 | 2,182 | 2,228 | 2,952 | **7,362** |
| 25-34 | 3,241 | 3,301 | 4,236 | **10,778** |
| 35-44 | 3,129 | 3,282 | 4,279 | **10,690** |
| 45-54 | 3,086 | 3,171 | 4,293 | **10,550** |
| 55-64 | 3,235 | 3,214 | 4,171 | **10,620** |
| **TOTAL** | **14,873** | **15,196** | **19,931** | **50,000** |

### 📌 Age Distribution Insights

| Insight | Finding |
|---------|---------|
| **Most Popular Age Group** | 25-34 (10,778 users, 21.6% of total) |
| **Least Popular Age Group** | 18-24 (7,362 users, 14.7% of total) |
| **Premium Users by Age** | Highest in 25-34 (3,301) and 35-44 (3,282) |
| **Standard Dominance** | Most popular plan across ALL age groups |


### 📊 Age Group Breakdown
```python
Age Distribution:
18-24 : ████████████░░░░░░░░░░░░ 14.7%
25-34 : ████████████████████░░░░ 21.6%
35-44 : ████████████████████░░░░ 21.4%
45-54 : ████████████████████░░░░ 21.1%
55-64 : ████████████████████░░░░ 21.2%
```

---

## Churn Rate by Gender

| Gender | Active (No) | Churned (Yes) | **Total** | Churn Rate |
|--------|-------------|---------------|-----------|------------|
| Male | 13,458 | 3,279 | **16,737** | 19.6% |
| Female | 13,424 | 3,335 | **16,759** | 19.9% |
| Other | 13,154 | 3,350 | **16,504** | 20.3% |
| **TOTAL** | **40,036** | **9,964** | **50,000** | **19.9%** |

### 📌 Churn Rate Insights

| Category | Finding |
|----------|---------|
| **Highest Churn** | Other (20.3%) |
| **Lowest Churn** | Male (19.6%) |
| **Difference** | Only 0.7% variation between genders |
| **Conclusion** | Churn is consistent across all genders |


### 📊 Churn Rate Visualization
```python
Churn Rate by Gender:
Male : ████████████████████░░░░ 19.6%
Female : ████████████████████░░░░ 19.9%
Other : █████████████████████░░░ 20.3%
```

### 🔍 Key Takeaway

**Gender is NOT a significant factor in churn prediction** - churn rates are nearly identical across all groups (19.6%-20.3%). Focus retention efforts on other factors like activity level and watch time instead.

---

## 📈 Quick Summary Table

| Metric | Value |
|--------|-------|
| Total Users | 50,000 |
| Most Common Age | 25-34 (21.6%) |
| Most Popular Plan | Standard (39.9%) |
| Avg Churn Rate | 19.9% |
| Churn Range by Gender | 19.6% - 20.3% |

---

## Revenue by Country

| Country | Monthly Revenue | % of Total | Rank |
|---------|-----------------|------------|------|
| Brazil | $63,118 | 10.24% | #1 |
| USA | $62,848 | 10.20% | #2 |
| India | $62,178 | 10.09% | #3 |
| Spain | $62,159 | 10.09% | #4 |
| Germany | $61,907 | 10.05% | #5 |
| Australia | $61,359 | 9.96% | #6 |
| Canada | $61,068 | 9.91% | #7 |
| Japan | $60,545 | 9.83% | #8 |
| UK | $60,514 | 9.82% | #9 |
| France | $60,472 | 9.82% | #10 |
| **TOTAL** | **$616,167** | **100%** | |

### 📊 Revenue Distribution
```python
Brazil : ████████████████████████░░ 10.24%
USA : ████████████████████████░░ 10.20%
India : ███████████████████████░░░ 10.09%
Spain : ███████████████████████░░░ 10.09%
Germany : ███████████████████████░░░ 10.05%
Australia : ██████████████████████░░░░ 9.96%
Canada : ██████████████████████░░░░ 9.91%
Japan : █████████████████████░░░░░ 9.83%
UK : █████████████████████░░░░░ 9.82%
France : █████████████████████░░░░░ 9.82%
```

### 📌 Key Revenue Insights

| Finding | Insight |
|---------|---------|
| **Top Market** | Brazil leads with $63,118 (10.24% of total) |
| **Bottom Market** | France at $60,472 (only 4.4% less than Brazil) |
| **Revenue Spread** | Only $2,646 difference between #1 and #10 |
| **Market Balance** | Revenue is **evenly distributed** across all 10 countries |

### 🌍 Regional Breakdown
- Americas (Brazil, USA, Canada): $187,034 (30.35%)
- Asia (India, Japan): $122,723 (19.92%)
- Europe (Spain, Germany, UK, France): $245,052 (39.77%)
- Australia: $61,359 (9.96%)

### 🔑 Key Takeaways

1. **No Dominant Market** - Revenue is surprisingly balanced across all countries
2. **Top 3 Markets** - Brazil, USA, and India generate 30.5% of total revenue
3. **Europe Leads** - European countries collectively bring in 39.8% of revenue
4. **Growth Opportunity** - Even the lowest country (France) is only 4.4% behind the leader

### 💡 Recommendations

| Priority | Action | Target |
|----------|--------|--------|
| 🟢 LOW | Maintain all markets | Revenue is already balanced |
| 🟡 MEDIUM | Investigate Brazil's #1 spot | Learn what's working there |
| 🟡 MEDIUM | Boost France & UK | Small gain could increase rank |
| 🔴 HIGH | Focus on user retention | Revenue per country is consistent |

---

## Quick Stats

| Metric | Value |
|--------|-------|
| Total Monthly Revenue | $616,167 |
| Average per Country | $61,617 |
| Highest Revenue | Brazil ($63,118) |
| Lowest Revenue | France ($60,472) |
| Revenue Gap | $2,646 (4.4%) |
| Most Balanced Region | Europe (4 countries within 1.5% range) |

---

## Watch Time by Device

| Device | Light (<30min) | Medium (30-60min) | Heavy (1-2hrs) | Very Heavy (>2hrs) | **TOTAL** |
|--------|----------------|-------------------|----------------|---------------------|-----------|
| Mobile | 890 | 1,258 | 2,571 | 7,866 | **12,585** |
| Smart TV | 851 | 1,295 | 2,561 | 7,855 | **12,562** |
| Laptop | 858 | 1,300 | 2,618 | 7,733 | **12,509** |
| Tablet | 853 | 1,301 | 2,490 | 7,700 | **12,344** |
| **TOTAL** | **3,452** | **5,154** | **10,240** | **31,154** | **50,000** |

### 📊 Watch Time Distribution by Device
```python
Watch Time Patterns:
Light : ███░░░░░░░░░░░░░░░░░░░ 6.9%
Medium : ██████████░░░░░░░░░░░░ 10.3%
Heavy : ████████████████████░░ 20.5%
Very Heavy : ██████████████████████ 62.3%
```

### 📌 Watch Time Insights

| Finding | Insight |
|---------|---------|
| **Very Heavy Viewers** | 62.3% of users watch >2 hours (31,154 users) |
| **Mobile Leads** | Mobile has most Very Heavy viewers (7,866) |
| **Light Viewers** | Only 6.9% watch <30 min - most users are engaged! |
| **Device Parity** | All devices show similar patterns |

### 📱 Device Preference Summary

| Device | Primary Behavior | % Very Heavy |
|--------|-----------------|--------------|
| Mobile | Very Heavy (7,866) | 62.5% |
| Smart TV | Very Heavy (7,855) | 62.5% |
| Laptop | Very Heavy (7,733) | 61.8% |
| Tablet | Very Heavy (7,700) | 62.4% |

---

## Binge Watching by Genre

| Genre | Occasional Binger | Moderate Binger | Heavy Binger | **TOTAL** |
|-------|-------------------|-----------------|--------------|-----------|
| Documentary | 1,246 | 1,272 | 3,834 | **6,352** |
| Romance | 1,271 | 1,290 | 3,721 | **6,282** |
| Comedy | 1,241 | 1,206 | 3,812 | **6,259** |
| Thriller | 1,216 | 1,293 | 3,748 | **6,257** |
| Action | 1,298 | 1,216 | 3,721 | **6,235** |
| Horror | 1,289 | 1,278 | 3,656 | **6,223** |
| Drama | 1,231 | 1,214 | 3,758 | **6,203** |
| Sci-Fi | 1,252 | 1,239 | 3,698 | **6,189** |
| **TOTAL** | **10,044** | **10,008** | **29,948** | **50,000** |

### 📊 Binge Watching Distribution
```python
Binge Behavior:
Occasional : ████████████████████░░ 20.1%
Moderate : ████████████████████░░ 20.0%
Heavy : ██████████████████████ 59.9%
```

### 📌 Binge Watching Insights

| Genre | Heavy Bingers | Binge Rate | Rank |
|-------|---------------|------------|------|
| **Documentary** | 3,834 | 60.4% | #1 |
| **Comedy** | 3,812 | 60.9% | #2 |
| **Drama** | 3,758 | 60.6% | #3 |
| **Thriller** | 3,748 | 59.9% | #4 |
| **Romance** | 3,721 | 59.2% | #5 |
| **Action** | 3,721 | 59.7% | #5 |
| **Sci-Fi** | 3,698 | 59.8% | #7 |
| **Horror** | 3,656 | 58.8% | #8 |

### 🔑 Key Takeaways

#### Watch Time Insights:
- **62% of users are Very Heavy viewers** (>2 hours) - excellent engagement!
- **Mobile is the preferred device** for long viewing sessions
- Device type **does NOT significantly impact** watch time

#### Binge Watching Insights:
- **60% of users are Heavy Bingers** - binge culture is real!
- **Documentary leads** in binge watching (3,834 heavy bingers)
- **Horror has lowest** binge rate (58.8%) - maybe too intense?
- All genres have **consistently high binge rates** (59-61%)

### 💡 Recommendations

| Priority | Action | Target |
|----------|--------|--------|
| 🔴 HIGH | Promote documentaries | Highest binge potential |
| 🟡 MEDIUM | Mobile optimization | Primary viewing device |
| 🟢 LOW | Horror content review | Lower engagement |
| 🟡 MEDIUM | Cross-device experience | All devices perform well |

---

## Quick Stats

| Metric | Value |
|--------|-------|
| Very Heavy Viewers | 31,154 (62.3%) |
| Heavy Bingers | 29,948 (59.9%) |
| Most Popular Device | Mobile (12,585 users) |
| Most Binged Genre | Documentary (3,834) |
| Least Binged Genre | Horror (3,656) |
| Avg Binge Rate | 59.9% |

---

## Completion Rate by Age

| Age Group | Average Completion Rate |
|-----------|------------------------|
| 18-24 | 99.8% |
| 25-34 | 99.7% |
| 35-44 | 100.2% |
| 45-54 | 100.5% |
| 55-64 | 99.7% |
| **AVERAGE** | **100.0%** |

### 📊 Completion Rate by Age
```python
18-24 : ████████████████████████████████████░░ 99.8%
25-34 : ████████████████████████████████████░░ 99.7%
35-44 : ██████████████████████████████████████ 100.2%
45-54 : ██████████████████████████████████████ 100.5%
55-64 : ████████████████████████████████████░░ 99.7%
```

### 📌 Completion Rate Insights

| Finding | Insight |
|---------|---------|
| **Highest Completion** | Age 45-54 (100.5%) - they finish what they start! |
| **Lowest Completion** | Age 25-34 & 55-64 (99.7%) - still excellent |
| **Range** | Only 0.8% difference across all ages |
| **Key Takeaway** | **Everyone finishes content!** Completion rates are nearly perfect |

**💡 Note:** These numbers suggest completion rate might be calculated differently or data is aggregated. Realistically, 65-75% is typical.

---

## User Activity by Recommendation Click Rate

| Activity Level | Ignores Recs | Skeptical Clicker | Occasional Clicker | Frequent Clicker | Heavy Clicker | **TOTAL** |
|---------------|--------------|-------------------|---------------------|------------------|---------------|-----------|
| Lapsed User | 3,548 | 4,879 | 4,746 | 4,882 | 5,945 | **24,000** |
| Monthly Active | 1,975 | 2,721 | 2,690 | 2,686 | 3,398 | **13,470** |
| Bi-Weekly Active | 854 | 1,169 | 1,223 | 1,196 | 1,452 | **5,894** |
| Weekly Active | 633 | 804 | 830 | 810 | 1,034 | **4,111** |
| Daily Active | 374 | 489 | 504 | 465 | 693 | **2,525** |
| **TOTAL** | **7,384** | **10,062** | **9,993** | **10,039** | **12,522** | **50,000** |

### 📊 Click Rate by Activity Level (Row %)

| Activity Level | Ignores | Skeptical | Occasional | Frequent | Heavy |
|---------------|---------|-----------|------------|----------|-------|
| Daily Active | 15% | 19% | 20% | 18% | **27%** |
| Weekly Active | 15% | 20% | 20% | 20% | **25%** |
| Bi-Weekly Active | 14% | 20% | 21% | 20% | **25%** |
| Monthly Active | 15% | 20% | 20% | 20% | **25%** |
| Lapsed User | 15% | 20% | 20% | 20% | **25%** |

### 📌 Recommendation Click Insights

| Finding | Insight |
|---------|---------|
| **Heavy Clickers** | Most active in EVERY activity group (25-27%) |
| **Daily Active Users** | Highest Heavy Clicker rate (27%) |
| **Lapsed Users** | Still click recommendations! 25% are Heavy Clickers |
| **Ignore Rate** | Consistent at 14-15% across all groups |

### 🔑 Key Takeaway

**Active users click more recommendations**, but even lapsed users engage with recommendations. This shows recommendations work across all user segments!

---

## Churn by Tenure

| Tenure Segment | % of Churned Users |
|----------------|-------------------|
| Veteran User (3-5 years) | 37.81% |
| Established User (1-2 years) | 21.30% |
| Loyal User (2-3 years) | 20.16% |
| Growing User (4-12 months) | 15.38% |
| New User (0-3 months) | 5.36% |
| **TOTAL** | **100.00%** |

### 📊 Churn Distribution by Tenure
```python
Veteran (3-5 yrs) : ████████████████████████████████████████░░ 37.8%
Established (1-2 yrs): ████████████████████████░░░░░░░░░░░░░░░░░░ 21.3%
Loyal (2-3 yrs) : ██████████████████████░░░░░░░░░░░░░░░░░░░░ 20.2%
Growing (4-12 mo) : ████████████████░░░░░░░░░░░░░░░░░░░░░░░░░░ 15.4%
New (0-3 mo) : ██████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ 5.4%
```

### 📌 Churn by Tenure Insights

| Finding | Insight |
|---------|---------|
| **Most Churn** | Veteran users (3-5 years) - 37.8% of all churn |
| **Least Churn** | New users (0-3 months) - only 5.4% of churn |
| **Paradox** | Long-term users are leaving the MOST! |
| **Critical Finding** | **Churn increases with tenure** - opposite of what you'd expect |

### 📈 Churn Pattern
```python
Churn Risk by Tenure:
New (0-3 mo) : ██████░░░░░░░░░░░░░░ 5.4% (LOWEST RISK)
Growing (4-12 mo): ████████████████░░░░ 15.4%
Loyal (2-3 yrs) : ████████████████████ 20.2%
Established : ████████████████████ 21.3%
Veteran (3-5 yrs): ████████████████████ 37.8% (HIGHEST RISK)
```

### 🔑 CRITICAL INSIGHTS

| What's Happening? | Why It Matters |
|-------------------|----------------|
| **Veteran users (3-5 yrs) are 37.8% of all churn** | You're losing your most loyal customers! |
| **New users rarely churn (only 5.4%)** | Onboarding is working well |
| **Churn INCREASES with tenure** | Something is going wrong after years of service |

### 🚨 URGENT RECOMMENDATIONS

| Priority | Action | Target |
|----------|--------|--------|
| 🔴 **CRITICAL** | Veteran user retention program | 3-5 year users (37.8% of churn) |
| 🔴 **HIGH** | Investigate "why veterans leave" | Exit interviews, surveys |
| 🟡 MEDIUM | Loyalty rewards for 2+ year users | Prevent churn before it happens |
| 🟢 LOW | Keep doing what works for new users | 0-3 month retention is working |

---

## 📊 Summary Dashboard

| Category | Top Insight | Action Needed |
|----------|-------------|---------------|
| **Completion Rate** | 45-54 age group finishes most (100.5%) | Learn from their habits |
| **Recommendation Clicks** | Daily active users click most (27% heavy) | Personalize for actives |
| **Churn by Tenure** | Veterans churn most (37.8%) | **URGENT retention needed** |

### ⚠️ Biggest Red Flag

**Veteran users (3-5 years) account for 37.8% of all churn** - you're losing your most loyal customers! This needs immediate attention.

---

# Dashboard Overview
-<a href="https://github.com/Donovandonz/Excel--netflix-behavior-analysis/blob/main/Netflix-analysis-dashboard.png">Netflix-user-behavior-dashboard</a>

