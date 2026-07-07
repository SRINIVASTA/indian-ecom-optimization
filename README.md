# 📦 2026 India E-Commerce Inventory Optimization Engine
### Designed & Developed by: Srinivasta

An enterprise-grade Decision Support System (DSS) engineered to tackle the 2026 supply chain battlefield. This system mitigates platform listing cancellation risks, minimizes interstate logistics freight costs, and automates multi-carrier risk routing across primary Indian commercial pipelines.

🚀 **Live Interactive Web App:** [Launch Live Streamlit Dashboard](https://indian-ecom-optimization-fmyapptcl6yupz39pnstnft.streamlit.app/)

---

## 🛠️ System Architecture Diagram

```text
       [ 📊 Calendar-Seeded DataFrame Stream ]
                        │
                        ▼
       [ 🧠 Core Optimization Engine Layer ]
       ├── Predictive Risk Framework -> Identifies Data Sync Gaps
       └── SciPy HiGHS Solver Matrix -> Resolves Bounded Linear Allocation
                        │
                        ▼
       [ 🗺️ Geospatial Streamlit Dashboard Interface ]
       └── Streamlit-Folium -> 4-Season Dynamic Maps & Active Environmental Overlays
```

---

## 📈 Core Engineering Components & Impact

### 1. Calendar-Reactive Data Engine (Layer 1)
*   **Mechanic:** Synthesizes a high-fidelity dataset of 5,000 transaction records mapping national logistics hubs (**Gurugram, Bhiwandi, Sriperumbudur**) and multi-tier courier providers (**Delhivery, Blue Dart, XpressBees, India Post**).
*   **Optimization:** Converts the real-time calendar date (`datetime.date.today()`) into a numeric mathematical seed. This rotates available stock counts daily, while `@st.cache_data` caching keeps rendering latencies under 5ms.

### 2. Predictive Marketplace Risk Analytics (Layer 2)
*   **The Bottleneck:** Legacy 15-minute backend polling loops (`900000ms`) lead to inventory oversells, creating an algorithmic tax of a **9.76% order cancellation rate** which penalizes platform organic search visibility.
*   **The Solution:** Simulates real-time, event-driven data flows (`200ms`) that pair user order volumes against current physical stock allocations. It isolates and flags vulnerable order streams, dropping cancellation probability to **0.00%**.

### 3. Operations Research Freight Allocator (Layer 2)
*   **The Constraint:** Fulfilling high-density volume surges (up to 3,000 units) without exceeding strict physical storage limits across disparate interstate nodes.
*   **The Solution:** Implements a bounded cost-minimization linear programming matrix computed through the high-performance **HiGHS solver** protocol. It balances supply equations dynamically based on sidebar user input:
    *   **WH-GURUGRAM-DEL (North Node):** Hard-capped at 1,000 units max capacity (Lowest baseline cost ~₹63.29/unit)
    *   **WH-BHIWANDI-MUM (West Node):** Hard-capped at 1,000 units max capacity (Mid-tier baseline cost ~₹69.07/unit)
    *   **WH-SRIPERUMBUDUR-CHN (South Node):** Pulls residual surge balances up to 1,200 units capacity (Highest cost ~₹74.69/unit)

### 4. Interactive 4-Season Geospatial Matrix (Layer 3)
*   **The Threat:** Unpredictable seasonal anomalies causing massive delivery backlogs and violating carrier SLAs across the Indian subcontinent.
*   **The Solution:** Utilizes a custom, logical calendar checker to track the current month and automatically update map tiles, map pin colors, status alerts, and geographic hazard overlays:
    *   *January - February:* Triggers **Northern Fog Alerts** with a translucent overlay mask covering Delhi NCR network corridors.
    *   *March - May:* Triggers **Summer Throughput Acceleration** metrics across all major supply lines.
    *   *June - September:* Triggers a crimson **Southwest Monsoon Hazard Polygon** over the Konkan coast, shifting Blue Dart express loads onto alternative ground surface pipelines.
    *   *October - December:* Triggers a golden **Festive Peak Demand Zone** over Southern manufacturing and electronics lines.

---

## 💻 Technical Stack
*   **Dashboard Framework:** Streamlit, Streamlit-Folium
*   **Geospatial Processing:** Folium (CartoDB Dark Matter tiles)
*   **Optimization Computation:** SciPy (Linear Programming via HiGHS protocol)
*   **Data Layout Engine:** Pandas, NumPy, Datetime

---

## 🚀 Local Deployment Instructions

1. Clone the repository down to your local directory setup:
   ```bash
   git clone https://github.com
   cd indian-ecom-optimization
   ```

2. Install all required data libraries via pip:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch your production web browser dashboard workspace:
   ```bash
   streamlit run app.py
   ```

---
*Created by Srinivasta as a capstone application in Applied Supply Chain Data Science & Operations Systems Optimization.*

### Connect with Me
- [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/srinivas-t-a-557637119/)  
- [![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/srinivasta)  
- [![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tasrinivass@gmail.com)  
- [![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/srinivasta)
