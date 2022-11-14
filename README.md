# Attention-peaks-prediction-in-video-ads
Context:
The data comes from a workshop where two groups of 25 partecipants were asked to watch 3 video advertisement about footbal.
The neurodevices considered for the experiment were:
1. Muse to monitor Blink rate/Attention level
2. Shimmer to gather data about Heart Rate, Heart Rate Variability and Skin Conductance Level

Objectives of the research:
1. Define and study the attention and emotion arousal trend of the partecipants during the experiment
2. Develop an ML model to identify the presence of emotion/attention peaks aroused during the advertisements
3. Identify the video elements that had the greatest impact on the peaks' presence

In this repository I'll focus on the code side of the project, however if you are interested in knowing the steps taken for the descriptive analysis of the data and the results, feel free to contact me.

Following a thorough model selection and tuning process, a random forest was the best performing algorithm. The final results were above the average standards for industrial classification problems in terms of AUC score, f1-score and accuracy.
