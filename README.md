# Eye-movements-classification
Classification of eye movements generated by intra cortical microstimulation of primary visual area (V1)- Thesis project

Can electrical stimulation of brain visual areas be decoded based on the eye movement data?

It is known that artifical stimulation can evoke a perception of a small spot of light (Phosphene). Sometimes an observer would look at the position of precevied Phosphene after stimultion. In this work I've tried to classify the exisetnce of stimultion based on the eye movement data.

Classification of data oculomotor records (time-series) data by ML: random forest, and DL: MLP, CNN, Transformer (based on visual transformer' patching method). 
Building a full pipeline- data retrieving, feature extraction methods (e.g. spectral analysis), model implementation, and hyper-parameter optimization.
The research included careful examination of previous literature and massive raw-data inspection.

A trial with clear affect of the electrical stimultion: 
x-axis is time (ms), y-axis is the center of the eye gaze in relation to a fixation point (0,0). blue line is X axis of the visual field and orange line is the Y axis. 
(for instance, on 0 time point, the gazing was for the (-0.1,0.1) point)
Time point 0 is the stimulation onset, on 450ms after stimulation there was a saccade caused by the electrical stimultion
![image](https://user-images.githubusercontent.com/62498821/155530543-7fb33fcd-9dc7-4491-b60a-b5117cf82b6b.png)

A lot of trials do not show a clear effects caused by the weak stimultion.

