# 🏠 Warsaw Apartment Hunter
*An Intelligent Multi-Objective Optimization System for Urban Housing Selection*

[![GitHub Pages](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue)](https://frknklcsln.github.io/Warsaw_Apartment_Hunter)
[![Optimization](https://img.shields.io/badge/Problem%20Type-Multi--Objective%20Optimization-green)](https://github.com/frknklcsln/Warsaw_Apartment_Hunter)
[![Data Size](https://img.shields.io/badge/Dataset-1.09GB-orange)](https://github.com/frknklcsln/Warsaw_Apartment_Hunter)

## 🗺️ [View the Interactive Map](https://frknklcsln.github.io/Warsaw_Apartment_Hunter)

---

## 🎯 Project Overview

**Warsaw Apartment Hunter** frames apartment search as a multi-objective optimization problem, combining listings, public transport data, and advanced algorithms to recommend apartments that minimize commute time and cost while maximizing value.

- **Objective:** Minimize total commute cost and time, maximize apartment quality
- **Constraints:** Budget, area, transport accessibility, private ownership
- **Decision Variables:** Apartment selection, optimal routes

---

## Mathematical Formulation

**Objective Function**

$$
\min f(x) = \alpha \cdot \text{Rent}(x) + \beta \cdot \text{CommuteTime}(x) + \gamma \cdot \text{TransportCost}(x)
$$

**Subject to Constraints**

$$
\text{Rent}(x) \leq \text{Budget}_{\max}
$$

$$
\text{Area}(x) \geq \text{Area}_{\min}
$$

$$
\text{CommuteTime}(x) \leq \text{Time}_{\max}
$$

$$
\text{OwnerType}(x) = \text{"Private"}
$$

$$
\text{AccessibilityScore}(x) \geq \text{Threshold}
$$

Where $x$ represents the selected apartment from the feasible set $X$.

---

## 🚀 Features & Optimizations

- **Pareto-Optimal Recommendations:** Balances price, commute, and apartment quality
- **Interactive Map:** Visualizes optimal apartments and routes with dynamic filtering
- **GPU Acceleration:** 🚀 Up to 40% faster route/network computations (CUDA/Numba)
- **Smart Caching:** 600MB+ of precomputed routes and scores for instant re-optimization
- **Real-Time Analysis:** Daily data refresh and rapid re-optimization
- **Advanced Analytics:** 1.09GB Warsaw dataset, 1000+ apartments, GTFS transport

---

## ⚡ Technical Stack

- **Python** (Pandas, GeoPandas, NetworkX, Numba)
- **GTFS** (Warsaw public transport)
- **Folium/HTML** (interactive map)
- **GitHub Pages** (hosting)

---

## 🏆 Impact

- **Reduces search time** from weeks to minutes
- **Quantifies trade-offs** for informed decisions
- **Mathematically proven best choices** for renters

---

## 📄 License

MIT License — free for research and educational use.

---

*Optimizing urban living, one apartment at a time.* 🏙️  
**Last updated:** June 2025
