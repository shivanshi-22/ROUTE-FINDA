Route Finda
Route Finda is a C++ application designed to optimize metro route planning by providing the shortest path between stations. It uses graph algorithms and data from the Delhi Metro fare matrix to calculate and visualize routes efficiently.

Features
Shortest Path Calculation: Uses graph algorithms to find the optimal route between metro stations.
Fare Estimation: Integrates fare matrix data for accurate fare calculation.
Visualization: Outputs graphical representations of routes and station connectivity.
Project Structure
route_finda_.cpp: Core application logic.
Fare Matrix Delhi Metro.xlsx: Data file containing metro fare details.
stations.txt: Lists station IDs and related metadata.
graph.png: Graph visualization of the metro network.
path.png: Example of a calculated route.
Requirements
C++ Compiler: The project is implemented in C++ and requires a standard compiler like GCC.
Graphviz (Optional): For visualizing .dot files.
How to Run
Clone this repository:
git clone https://github.com/shivanshi-22/route_finda_.git
Compile the code:
g++ route_finda_.cpp -o route_finda
Execute the program:
./route_finda
