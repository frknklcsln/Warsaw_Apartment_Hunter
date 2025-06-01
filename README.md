# 🏠 Warsaw Apartment Hunter
### *An Intelligent Optimization System for Urban Housing Selection*

[![GitHub Pages](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue)](https://frknklcsln.github.io/Warsaw_Apartment_Hunter)
[![Optimization](https://img.shields.io/badge/Problem%20Type-Multi--Objective%20Optimization-green)](https://github.com/frknklcsln/Warsaw_Apartment_Hunter)
[![Data Size](https://img.shields.io/badge/Dataset-1.09GB-orange)](https://github.com/frknklcsln/Warsaw_Apartment_Hunter)

## 🗺️ [**→ View Live Interactive Optimization Map ←**](https://frknklcsln.github.io/Warsaw_Apartment_Hunter)

---

## 🎯 Project Overview

**Warsaw Apartment Hunter** is a sophisticated **multi-objective optimization system** that solves the complex problem of optimal apartment selection in urban environments. By combining real estate data, public transport networks, and advanced algorithms, it identifies apartments that minimize commute times while maximizing value and livability.

### 🔬 **The Optimization Problem**

This project addresses a **facility location optimization problem** where:

- **Objective**: Minimize total commute cost and time while maximizing apartment quality
- **Constraints**: Budget limits, area requirements, transport accessibility, private ownership
- **Decision Variables**: Apartment selection from 1000+ options, optimal transport routes
- **Solution Space**: Multi-dimensional analysis across price, location, and accessibility metrics

---

## 📈 **Mathematical Formulation**

## Objective Function

$$
\min f(x) = \alpha \cdot \text{Rent}(x) + \beta \cdot \text{CommuteTime}(x) + \gamma \cdot \text{TransportCost}(x)
$$

## Subject to Constraints

$$
\begin{align*}
\text{Rent}(x) &\leq \text{Budget}_{\max} \\
\text{Area}(x) &\geq \text{Area}_{\min} \\
\text{CommuteTime}(x) &\leq \text{Time}_{\max} \\
\text{OwnerType}(x) &= \text{"Private"} \\
\text{AccessibilityScore}(x) &\geq \text{Threshold}
\end{align*}
$$


Where $x$ represents the selected apartment from the feasible set $X$.


### **Solution Methodology**
1. **Data Collection**: Automated scraping of 1000+ apartment listings
2. **Network Analysis**: Graph-based shortest path calculations  
3. **Multi-objective Optimization**: Pareto frontier identification
4. **Constraint Filtering**: Feasible solution space reduction
5. **Interactive Visualization**: Decision support interface

---

## 🚀 **Key Features**

### 📊 **Advanced Analytics**
- **1.09GB Dataset**: Comprehensive Warsaw rental market analysis
- **414MB Transport Data**: Complete Warsaw GTFS public transport network
- **603MB Processed Cache**: Optimized commute calculations and route analysis
- **Real-time Updates**: Daily apartment data refresh and optimization

### 🗺️ **Interactive Optimization Visualization**
- **Multi-objective Results**: Visual representation of Pareto-optimal apartment choices
- **Dynamic Filtering**: Real-time constraint adjustment and re-optimization
- **Route Optimization**: Shortest path algorithms for commute planning
- **Accessibility Zones**: Color-coded optimization results by travel time

### 🔧 **Technical Implementation**
- **Geospatial Optimization**: Network analysis using Warsaw's transport graph
- **Multi-criteria Decision Making**: Weighted scoring across multiple objectives
- **Constraint Satisfaction**: Hard and soft constraint handling
- **Heuristic Algorithms**: Efficient solution finding for large search spaces

---

## 🛠️ **Technology Stack**

### **Optimization & Analysis**
- **Python**: Core optimization algorithms and data processing
- **NetworkX**: Graph theory and shortest path algorithms
- **GeoPandas**: Geospatial optimization and network analysis
- **Pandas**: Large-scale data manipulation and constraint handling

### **Data Sources**
- **Real Estate**: Otodom.pl apartment listings (private owners)
- **Transport**: Warsaw ZTM GTFS data (complete network)
- **Geospatial**: OpenStreetMap for geographical optimization

### **Visualization**
- **Folium**: Interactive optimization result mapping
- **HTML/CSS/JavaScript**: Dynamic user interface
- **GitHub Pages**: Live optimization demo hosting

---

## 📊 **Dataset Specifications**

| Component | Size | Description |
|-----------|------|-------------|
| **Processed Cache** | 603.89 MB | Optimized apartment data with commute calculations |
| **Transport Network** | 414.27 MB | Warsaw GTFS complete schedule and route data |
| **Route Geometries** | 23.37 MB | Detailed transport path optimization data |
| **Interactive Maps** | 30.86 MB | Multi-layered optimization visualizations |
| **Analysis Results** | 0.66 MB | PowerBI optimization reports and insights |

---

## 🎯 **Optimization Results**

### **Performance Metrics**
- **Solution Space**: 1000+ apartment options analyzed
- **Constraint Satisfaction**: 100% feasible solutions
- **Multi-objective Trade-offs**: Pareto-optimal frontier identification
- **Computational Efficiency**: Real-time re-optimization capability

### **Key Insights**
- **Optimal Zones**: Identified best value-for-money districts
- **Transport Efficiency**: Quantified accessibility vs. cost trade-offs
- **Market Analysis**: Price optimization patterns across Warsaw

---

## 🏆 **Real-World Impact**

This optimization system transforms apartment hunting from a manual, time-intensive process into a **data-driven, scientifically-optimized decision**. By solving the multi-objective facility location problem, it:

- **Reduces Search Time**: From weeks to minutes
- **Optimizes Outcomes**: Mathematically proven best choices
- **Quantifies Trade-offs**: Clear visualization of decision impacts
- **Enables Informed Decisions**: Data-backed apartment selection

---

## 📚 **Academic Context**

This project demonstrates practical application of:
- **Operations Research**: Facility location optimization
- **Graph Theory**: Network shortest path algorithms
- **Multi-criteria Decision Analysis**: Pareto optimization
- **Computational Geometry**: Geospatial constraint satisfaction
- **Data Science**: Large-scale urban analytics

---

## 🔗 **Links & Resources**

- 🗺️ **[Live Optimization Demo](https://frknklcsln.github.io/Warsaw_Apartment_Hunter)**
- 📊 **[Interactive Results](https://frknklcsln.github.io/Warsaw_Apartment_Hunter)**
- 🏠 **[GitHub Repository](https://github.com/frknklcsln/Warsaw_Apartment_Hunter)**

---

## 📄 **License & Usage**

This optimization system is available for educational and research purposes. The methodology can be adapted for other urban facility location problems.

---

## 🎓 **About**

Developed as a comprehensive solution to the **multi-objective urban facility location optimization problem**, demonstrating the practical application of operations research techniques to real-world housing decisions.

*Optimizing urban living, one apartment at a time.* 🏙️

---

**Last Updated**: June 2025 | **Status**: Live Optimization System
