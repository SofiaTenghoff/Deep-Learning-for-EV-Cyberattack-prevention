# Deep Learning for EV Cyberattack Prevention
This project contains two neural networks for preventing cyberattacks on electrical vehicle charging stations. 
These two neural networks use features such as charging start time, charging session energy demand, and charging duration
to predict whether or not a cyberattack has occurred.
## Usage
To use the code of the Feed Foward Neural Network I created, open the file FNN_starting (1).ipynb. Copy and paste the code from all cells, in order,
except for the cells that are headed by a comment that says "don't run this cell" (these will be obvious because they have red error boxes at the bottom),
into any coding environment of your choice and run to see the results.
To use the code of the Recurrent Neural Network I created, open the file RNN_starting (1).ipynb. Copy and paste the code 
into any coding environment of your choice and run to see the results. The files in this repository show the results of running the code at the bottom
of each file, in a section titled "FINAL RESULTS." If you run the code yourself, the "FINAL RESULTS" section will be reprinted in the terminal of your coding
environment.
## Features
The FNN achieved an accuracy of 86.75%, compared with the RNN which only achieved an accuracy of 16.74%. This is part of a larger
experiment that proves that FNNs are better than most other machine learning models at predicting cyberattacks on electrical 
vehicle charging stations based on the selected features.
