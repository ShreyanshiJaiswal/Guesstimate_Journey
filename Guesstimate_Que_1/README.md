# 🧮 Guesstimate: Monthly Residential Electricity Consumption of India

## 1. ❓ Problem Statement
**Estimate the electricity consumption of India (residential only) for one month, in electricity units.**

---

## 2. ❗ Clarifying Questions
To narrow down the scope, the following clarifications were made:

- Is the estimate for India or global? → **India**
- Time period? → **One month**
- Consumption in money or electricity units? → **Units (kWh)**
- Any specific state? → **No**
- Residential or commercial? → **Residential only**
- Any specific energy source? (solar/renewable) → **Not required**

**Final refined question:**  
➡️ *Estimate the monthly residential electricity consumption of India, in units.*

---

## 3. 🧩 Approach Overview
1. Use **population of India = 140 crore (1.4 billion)**
2. Split into **Urban (30%)** and **Rural (70%)**
3. Convert population into number of households:  
   - Urban household size = **4 people**  
   - Rural household size = **5 people**
4. Segment both Urban & Rural households into:  
   - **High income**  
   - **Middle income**  
   - **Low income**
5. Assign **monthly electricity consumption per household** to each segment
6. Compute total consumption for all groups
7. Add Urban + Rural totals to get India’s final residential consumption

---

## 4. 👥 Population Segmentation

### 4.1 Population Split
| Category | Percentage | Population (approx.) |
|---------|------------|----------------------|
| Urban   | 30%        | 420 million → taken as **400 million** for easier calculation |
| Rural   | 70%        | 980 million → taken as **1000 million** for easier calculation |

---

## 5. 🏠 Household Calculation

### 5.1 Household Size Assumptions
- Urban household size = **4 people**
- Rural household size = **5 people**

### 5.2 Number of Households
| Region | Population Used | Household Size | No. of Households |
|--------|------------------|----------------|--------------------|
| Urban | 400 million | 4 | **100 million** |
| Rural | 1000 million | 5 | **200 million** |

---

## 6. 🧱 Income Segmentation of Households

### 6.1 Urban Household Split
| Segment | Percentage | Households |
|---------|------------|------------|
| High    | 10%        | 10 million |
| Middle  | 40%        | 40 million |
| Low     | 50%        | 50 million |

### 6.2 Rural Household Split
| Segment | Percentage | Households |
|---------|------------|------------|
| High    | 10%        | 20 million |
| Middle  | 30%        | 60 million |
| Low     | 60%        | 120 million |

---

## 7. ⚡ Monthly Electricity Consumption Assumptions

### Urban
- High: **2000 units/month**
- Middle: **1000 units/month**
- Low: **500 units/month**

### Rural
- High: **1000 units/month**
- Middle: **500 units/month**
- Low: **200 units/month**

---

## 8. 🔢 Calculations

### 8.1 Urban Consumption
| Segment | Households | Units per Month | Total Units (in million) |
|---------|------------|-----------------|----------------------------|
| High    | 10 million | 2000            | **20,000 million** |
| Middle  | 40 million | 1000            | **40,000 million** |
| Low     | 50 million | 500             | **25,000 million** |

➡️ **Total Urban Consumption = 75,000 million units**

---

### 8.2 Rural Consumption
| Segment | Households | Units per Month | Total Units (in million) |
|---------|------------|-----------------|----------------------------|
| High    | 20 million | 1000            | **20,000 million** |
| Middle  | 60 million | 500             | **30,000 million** |
| Low     | 120 million | 200            | **24,000 million** |

➡️ **Total Rural Consumption = 74,000 million units**

---

## 9. 🏁 Final Answer

### **Total Monthly Residential Electricity Consumption of India**

\[
\text{Urban (75,000 million)} + \text{Rural (74,000 million)} = 149,000 \text{ million units}
\]

### ✅ **Final Result: 149 billion electricity units per month (residential).**

