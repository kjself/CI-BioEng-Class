## Mini Project 2A: Classification of accelerometer data using the micro:bit
In this mini-project, our group used a physical [micro:bit device](https://makecode.microbit.org/) and analyzed its accelerometer data to determine whether it was `shaken` or `not_shaken`. However, this can also be simulated on the micro:bit's website using a "shake" button.

### Acquire the Data
Whether you use the simulation or the actual micro:bit, run the device such that the state is observed to be `still` - `shake` - `still` - `shake`, each for 5 seconds.

### Graph your Data
Once the data is acquired, one must upload their .csv file (example file named `still_shake.csv`) to make them accessible to the notebook provided (see `still_shake.ipynb`). The notebook will then graph the position of the accelerometer over time. The difference between two adjacent points will indicate whether or not the device was shaken, and the graph will highlight any shaken sections.
