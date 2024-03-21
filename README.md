# smart home dataset

Dataset for Smart Home Appliances:

1.	Unix Timestamp: Represents the Unix timestamp corresponding to each data entry, providing a standardized time format.
2.	Transaction ID: Assigns a unique identifier to each transaction or entry in the dataset, ensuring distinction between different observations.
3.	Appliance Usage (Television, Dryer, Oven, Refrigerator, Microwave): Binary indicators (0 or 1) indicating whether each corresponding smart home appliance is in use (1) or not (0).
4.	Voltage Metrics (Line Voltage, Voltage, Apparent Power):
•	Line Voltage: The voltage level in the electrical line.
•	Voltage: The voltage level at the specific location.
•	Apparent Power: The combination of real and reactive power in the electrical system.
5.	Energy Consumption (kWh): Represents the energy consumed, generated randomly within a specified range.
6.	Bandwidth (kbps): Bandwidth in a smart home system refers to the capacity or speed at which data can be transmitted between devices. It is crucial in facilitating smooth communication, enabling seamless control, monitoring, and automation of various home functions.
7.	Offloading Decision: Randomly selects between 'Local' and 'Remote' to simulate decision-making for offloading computational tasks.



 The dataset is created with almost 49,000 rows, spanning a simulated period of four years. The generated dataset is saved in a CSV file named 'smart_home_dataset.csv.' It serves as a valuable resource for analyzing smart home behavior, energy consumption patterns, and decision-making scenarios related to offloading computational tasks.
