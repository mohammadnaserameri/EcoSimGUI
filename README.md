EcoSim Calc – Growth Simulator

Overview
EcoSim Calc is a JavaFX desktop application that simulates and visualizes growth patterns over time using a simple exponential formula. Users input initial growth, weekly growth rate, and the duration in weeks, and the app estimates the final growth while displaying a dynamic line chart.
Features
- User-friendly interface with clearly labeled input fields
- Validation of inputs to prevent invalid calculations
- Real-time calculation and chart updates
- Displays projected growth using a JavaFX `LineChart`
- Error messaging for incorrect inputs
Inputs
- Initial growth (a):** Starting value in centimeters
- Growth rate (b):** Must be a positive number not equal to 1
- Number of weeks (x):** Must be a non-negative integer
Output
- A line chart visualizing growth across weeks
- A label showing estimated final growth at week x
How to Run
Requires JavaFX environment properly configured
1. Compile and run `EcoSimGUI.java`
2. Use the application window to enter values
3. Click **Calculate** to view results
