# membership-program
Tasked with designing the backend system for a Membership Program. The platform aims to offer users subscription-based memberships with tiered benefits, and a smooth experience integrated with the shopping and checkout journey.


# 🧾 Membership Management System

## 💡 Key Requirements:

### 1. Membership Plans
Users can choose from:
- Monthly
- Quarterly
- Yearly

Each plan comes with specific pricing.

---

### 2. Membership Benefits *(Optional)*
- ✅ Free delivery on eligible orders
- ✅ Extra X% discount on selected items or categories
- ✅ Access to exclusive deals and early access to sales
- ✅ Optional: Priority support for premium members
- ✅ Each tier unlocks additional perks (e.g., higher discounts, faster delivery, exclusive coupons)

---

### 3. User Actions
- 🔄 Subscribe to a plan
- 🔼 Upgrade / 🔽 Downgrade Membership Tier
- ❌ Cancel subscription
- 📊 Track current membership tier and expiry
- 📌 Mix-match Membership Tier and Subscription Period as per user selection and see the dynamic pricing

---

### 4. Membership Tiers
Users can move through tiers like:
- 🥈 Silver
- 🥇 Gold
- 💎 Platinum

Tier advancement can be based on:
- Membership Type
- Tenure
- Total Spend
- Admin Criteria

---

### 🔍 Dynamic Pricing API
Use the API `/api/memberships/price?tierId=1&periodId=2`  
to fetch the price for a specific `Tier` and `SubscriptionPeriod` combination.

---

### 🛠 Built With
- Spring Boot
- MySQL
- RESTful API
- JPA / Hibernate

---

### 📦 Future Enhancements
- Role-based authentication (Admin/User)
- Payment integration
- Auto-renewals
- Notifications for expiry and offers

---

### 💬 Want to contribute?
Feel free to fork and create a PR! Contributions are welcome.
