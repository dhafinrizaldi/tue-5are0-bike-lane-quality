# Google Docs
https://docs.google.com/document/d/1JVa07doYiEPqZTP8zUhnjcuHuiXHWiXPlITqG6AOyeA/edit?usp=sharing

# Protocol
- Positioning: The group has agreed to fix a position of the phone on the bike handle using a phone holder to ensure data consistency.
- Time: The duration of each recording should be around 60 seconds
- Speed: Bike at a normal speed (15-18 km/h)
- Quantity: 5x smooth and 5x bumpy measurements per person, 30 measurements in total

# Data Proprocessing
1. Load data: a function that loads a raw data csv file into a dataframe
2. Plotting feature: a function that takes in a dataframe and plots (x, y and z) in a time series graph.
3. Trimming: cut off the first and last 10 seconds of each recording, this is to ensure that any moment that does not pertain to an actual active recording (i.e. putting phone in the holder) is excluded.
4. Synchronization: ensure that the raw data follows a fixed grid. Although the app sets the sampling frequency to 100 Hz, the time elapsed per sample does not fall exactly within a uniform grid.

