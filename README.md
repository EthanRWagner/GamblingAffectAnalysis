## GAMBLING AFFECT ANALYSIS

[Data Accessible Here](https://drive.google.com/drive/folders/1RcegESj-_UpARv1KQdkfohvcj0Cf5p3s?usp=drive_link)

To properly run the Google Colab notebook, need to mount Google Drive and change appropriate path information.

This project utilized the Emotiv Insight 5-channel EEG and Pupil Core Eye Tracking Glasses to 
analyze the difference in affect while participants gamble online with fake and real money. 
This dataset consists of 3 males, ages 20-25 years old.

Some useful notes after pre- and post-analysis notes are below:

# FINAL RESULTS

------
## P1
------

__EEG:__
Sensor 2 was not connected throughout the recording which affected the focus and excitement classifications. The focus reading was -1 the entire trial, while I believe the polarity of the excitement reading is reverse. To correct the excitement reading, one idea would be to reflect all values across a mean line. However, I am unsure if this is reliable. For now, I filtered out these values so that they do not distract the audience from real data.

Some general trends noticed in the PAD data were positive correlations in arousal with wins and losses. This means that the more the participant won the higher the arousal and the morre the participant lost the lower the arousal. These effects are not single event changes but increase/decrease with repeated results. Excitement had higher volatility when the participant used real money compared to using fake money. Interest had larger values towards the beginning of each trial and generally declined over time, but had large spikes when user won multiple hands in the real money trial.

__Eye tracking:__
Eye tracking data was ommitted due to inaccurate calibration. The predictions were fixated on keyboard and lower screen most of the collection and did not display the more dynamic movements seen in the other eye tracking collections. It was evident that participant would frequently shake head side to side after losses.

__Statistics:__
All affect labels (excluding "Focus" due to aforementioned reasons) and PAD categories had statistically significant differences with fake money and real money with an alpha value of 0.01.

__Other:__
Cannot determine balance checks due to eye tracking miscalibration.

Fake record: 8-10-1

Real record: 12-7-2

------
## P2
------

__EEG:__
Sensor 2 had volatile connection up until 1:40. This has clear affect on the focus reading in the affect chart. Therefore, this noise was dropped from the chart. There is one large spike that shows across the arousal, dominance, and excitement charts that corresponded to a late lost in the real money trial. There are huge spikes in excitement accoss both trials are primarily correlated with losses. When the participant lost all their real money there was a large shift of arousal in the negative direction and dominance in the positive direction. This state corresponds with relaxation which shows a sharp increase at the same time. This is unexpected after losing money and one could expect even negative pleasure in this state which combined with the current arousal and dominance would product disdain which would be appropriate. No noticeable drops in pleasure were observed among all participants.

__Eye tracking:__
9 balance checks on fake, most often after loss and look at audience after each win minus 2 samples. 12 balance checks on real money, often double checking balance after each hand, less gaze of audience. Participant had extreme head movements at times after losses which included head rolls and after wins which included vertical head nods.

__Statistics:__
All affect labels (excluding "Focus" due to aforementioned reasons) and none of the PAD categories had statistically significant differences with fake money and real money with an alpha value of 0.01.

__Other:__

Fake record: 6-6

Real record: 2-4

--------
## P3
--------

__EEG:__
There is some volatility in the sensor 2 connection, however, the quality of the signal is always above 2, so data collection from this sensor can be trusted. Slight negative trend in pleasure over whole recording, lower baseline of pleasure compared to other participants. Large positive trends with increasing focus, engagement, and stress over whole recording. Large spikes of excitement following multiple losses or multiple wins. Often, prompted user to change betting pattern. Large spikes of interest in the fake money trial due to experimentation with betting patterns and learning the gaming interface.

__Eye tracking:__
11 balance checks after every bout of betting with fake money no correlation with game play but when spamming balls monitored balance. 12 balance with real money;checks 5 after loss and 6 after win and 1 after push.

__Statistics:__
All affect labels and PAD categories had statistically significant differences with fake money and real money with an alpha value of 0.01.

__Other:__

Fake record: 7-9

Real record: 9-8-3

------
## Results
------

* Some equipment was not properly calibrated or recording properly, namely, the EEG sensors located on the forehead
* No noticable drops in pleasure across participants (all highly positive pleasure, lowest recorded value ~0.88) => generally, participants had fun playing regardless of stakes 
* Affective states are different among all participants when playing with fake money vs. real money 
* Higher volatility (related to variance bounded in a certain time) of affective states when playing with real money
