# 💳 Credit Risk Dashboard (Power BI)

## 📊 Objective
This project visualizes and analyzes credit risk using two datasets:
- `users_data`: contains user-level financial details
- `cards_data`: contains card-level information linked to each user

## 🛠️ Tools Used
- Power BI Desktop
- DAX for custom calculations

## 🔗 Data Model
A one-to-many relationship was created:
- `users_data.id` → `cards_data.client_id`

## 📈 Dashboard Features
- Risk profiling based on credit score and card exposure
- Card usage and distribution across brands
- Filters by gender, card brand, and type
- Scatter plot for credit score vs. total debt

## 🔐 Business Outcome
- Identifies financially vulnerable customers
- Enables data-driven decisions to improve credit health
- Supports risk mitigation strategy through monitoring flagged cards

## 📄 Author
Biswarup Das
