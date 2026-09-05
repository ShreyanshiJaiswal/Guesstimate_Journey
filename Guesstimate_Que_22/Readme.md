# Guesstimate 22: Estimate Liters of Petrol Sold at a Petrol Pump

## Question

Estimate the **liters of petrol sold at a petrol pump per day**.

---

## Clarifying Questions

1. Are we estimating petrol sold **daily, weekly, monthly, or yearly**?
2. Are we considering **peak and non-peak hours**?
3. Are we considering **all vehicle types**?
4. What is the **location** of the petrol pump?
5. What is the **size of the petrol pump** — small, medium, or high-volume?
6. Is there a **nearby petrol pump** that could divert customers?

---

## Final Question

Estimate the **daily liters of petrol sold throughout the day at a medium-sized petrol pump in a Tier-1 city**, considering all relevant vehicle types and assuming **no nearby competing petrol pump**.

---

# Solution

## Key Logic

The estimation can be broken down into:

**Total vehicles served per day**  
→ **Vehicle segmentation**  
→ **Average petrol purchased per vehicle per visit**  
→ **Petrol sold by each vehicle category**  
→ **Total petrol sold per day**

---

# Step 1: Estimate Total Vehicles Served Per Day

Assume the medium-sized petrol pump operates for approximately **18 hours per day**.

A medium-sized station is assumed to have around **4–6 petrol dispensers**. Each vehicle takes approximately **2–5 minutes** to refuel.

Therefore, the theoretical capacity per hour can be estimated as:

- One dispenser at 5 minutes/vehicle:

\[
60/5 = 12 \text{ vehicles/hour}
\]

- One dispenser at 2 minutes/vehicle:

\[
60/2 = 30 \text{ vehicles/hour}
\]

For 4–6 dispensers, this gives a theoretical capacity of approximately **48–180 vehicles/hour**.

However, the pump will not operate at maximum capacity continuously because of idle time, vehicle positioning, payment time, and variations in customer demand.

Therefore, we use **~100 vehicles/hour during peak hours** as a practical assumption.

We divide the operating day into peak, normal, and non-peak periods.

| Period | Hours | Vehicles/Hour | Vehicles Served |
|---|---:|---:|---:|
| Peak | 6 | 100 | 600 |
| Normal | 8 | 70 | 560 |
| Non-peak | 4 | 30 | 120 |
| **Total** | **18** | — | **1,280** |

Therefore:

\[
600 + 560 + 120 = 1,280
\]

We round this to:

### **~1,300 vehicles/day**

---

# Step 2: Segment Vehicles

For a Tier-1 city, assume the vehicles visiting the petrol pump are distributed as follows:

| Vehicle Type | Assumed Share | Vehicles/Day |
|---|---:|---:|
| Two-wheelers | 50% | 650 |
| Four-wheelers | 40% | 520 |
| Petrol-powered commercial/other vehicles | 10% | 130 |
| **Total** | **100%** | **1,300** |

### Why 50% Two-Wheelers?

Two-wheelers are assumed to form the largest segment because they are widely used for urban commuting and are convenient in congested Tier-1 city traffic.

### Why 40% Four-Wheelers?

Cars form another major portion of urban traffic and generally purchase more petrol per visit than two-wheelers.

### Why 10% Commercial/Other Vehicles?

Many buses and heavy trucks typically use diesel rather than petrol. Therefore, this category represents **petrol-powered commercial and other vehicles**, rather than assuming that all buses and trucks use petrol.

---

# Step 3: Estimate Petrol Purchased Per Visit

Tank capacity does not mean that the vehicle fills its entire tank during every visit.

Therefore, we estimate the **average quantity of petrol purchased per visit**.

| Vehicle Type | Typical Tank Capacity | Refueling Pattern | Assumed Petrol per Visit |
|---|---:|---|---:|
| Two-wheelers | 8–15 L | Every 3–4 days | 3 L |
| Four-wheelers | 40–60 L | Approximately weekly | 10 L |
| Petrol-powered commercial/other vehicles | Higher capacity | More frequent refueling | 30 L |

The assumed values represent **petrol purchased per visit**, rather than the total tank capacity.

---

# Step 4: Calculate Petrol Sold by Vehicle Type

### Two-Wheelers

\[
650 \times 3 = 1,950 \text{ L/day}
\]

### Four-Wheelers

\[
520 \times 10 = 5,200 \text{ L/day}
\]

### Petrol-Powered Commercial/Other Vehicles

\[
130 \times 30 = 3,900 \text{ L/day}
\]

---

# Step 5: Calculate Total Petrol Sold

| Vehicle Type | Vehicles/Day | Petrol/Vehicle/Visit | Petrol Sold/Day |
|---|---:|---:|---:|
| Two-wheelers | 650 | 3 L | 1,950 L |
| Four-wheelers | 520 | 10 L | 5,200 L |
| Petrol-powered commercial/other vehicles | 130 | 30 L | 3,900 L |
| **Total** | **1,300** | — | **11,050 L** |

Therefore:

\[
1,950 + 5,200 + 3,900 = 11,050 \text{ L/day}
\]

---

# Final Estimate

### **≈ 11,050 liters of petrol sold per day**

Therefore, a reasonable guesstimate for a **medium-sized petrol pump in a Tier-1 city** is:

## **~11,000 liters of petrol per day**
