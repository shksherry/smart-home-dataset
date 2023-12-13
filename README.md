# smart_home_dataset

Dataset for Smart Home Appliances:

1.	Unix Timestamp: Represents the Unix timestamp corresponding to each data entry, providing a standardized time format.
2.	Transaction ID: Assigns a unique identifier to each transaction or entry in the dataset, ensuring distinction between different observations.
3.	Appliance Usage (Television, Dryer, Oven, Refrigerator, Microwave): Binary indicators (0 or 1) indicating whether each corresponding smart home appliance is in use (1) or not (0).
4.	Voltage Metrics (Line Voltage, Voltage, Apparent Power):
•	Line Voltage: The voltage level in the electrical line.
•	Voltage: The voltage level at the specific location.
•	Apparent Power: The combination of real and reactive power in the electrical system.
5.	Energy Consumption (kWh): Represents the amount of energy consumed, generated randomly within a specified range.
6.	Timestamp Components (Month, Day of the Week, and Hour of the Day): Derived from the Unix timestamp, these components provide temporal information.
7.	Offloading Decision: Randomly selects between 'Local' and 'Remote' to simulate decision-making for offloading computational tasks.



 The dataset is created with 3,000 rows, spanning a simulated period of three years. The generated dataset is saved in a CSV file named 'smart_home_dataset.csv'. It serves as a valuable resource for analyzing smart home behavior, energy consumption patterns, and decision-making scenarios related to offloading computational tasks.
