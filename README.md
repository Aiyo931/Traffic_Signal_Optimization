# 🚦 Traffic Signal Optimization

This project uses **linear programming** to optimize traffic signal timings for different vehicle types to **maximize traffic throughput** within a fixed signal cycle duration.

---

## 📁 Project Structure

```
Traffic_Signal_Optimization/
├── notebooks/
│   └── traffic_signal_optimization.ipynb      # Main notebook for signal timing optimization
├── data/
│   └── traffic_data_2months.csv               # Original two-month traffic volume data
└── README.md
```

---

## 🧠 Method

- **Model**: Linear Programming using `scipy.optimize.linprog`
- **Goal**: Maximize number of vehicles passing during green light
- **Constraints**:
  - Total signal duration (e.g., 60 seconds)
  - Vehicle-type-specific passing time per vehicle
- **Output**:
  - Optimal green light time allocation for cars, buses, trucks, bicycles

---

## ▶️ How to Use

1. Open the notebook `notebooks/traffic_signal_optimization.ipynb`
2. Modify vehicle data or total green light time if needed
3. Run all cells to view the optimal time allocation and visualizations
