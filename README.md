# ROUTE-FINDA

**Route Finda** is a C++ application designed to optimize metro route planning by providing the shortest path between stations. It uses graph algorithms and data from the Delhi Metro fare matrix to calculate and visualize routes efficiently.

---

## 🌟 Key Features

### 🛤️ **Shortest Path Calculation**
Uses graph algorithms to find the optimal route between metro stations, ensuring efficient travel.

### 💰 **Fare Estimation**
Integrates fare matrix data from the Delhi Metro system for accurate and real-time fare calculation.

### 🖼️ **Visualization**
Provides graphical representations of routes and station connectivity for better understanding.

---

## 📂 Project Structure

- **`route_finda_.cpp`**: Core application logic.
- **`Fare Matrix Delhi Metro.xlsx`**: Data file containing metro fare details.
- **`stations.txt`**: Lists station IDs and related metadata.
- **`graph.png`**: Graph visualization of the metro network.
- **`path.png`**: Example of a calculated route.

---

## 🛠 Requirements

- **C++ Compiler**: The project is implemented in C++ and requires a standard compiler like GCC.
- **Graphviz (Optional)**: For visualizing `.dot` files to better represent the metro network graphically.

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/shivanshi-22/route_finda_.git
   ```
2. Compile the code:
   ```bash
   g++ route_finda_.cpp -o route_finda
   ```
3. Execute the program:
   ```bash
   ./route_finda
   ```

---

## 🌟 Future Enhancements

- **Real-Time Data Integration**: Include live metro timings and delays.
- **Multi-Language Support**: Make the application accessible to a broader audience.
- **User-Friendly GUI**: Develop a graphical interface for easier interaction.

---
