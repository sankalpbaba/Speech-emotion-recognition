# Speech-emotion-recognition

The problem of speech emotion recognition can be solved by analyzing one or more of these features. Choosing to follow the lexical features would require a transcript of
the speech which would further require an additional step of text extraction from speech if one wants to predict emotions from real-time audio. Similarly, going
forward with analyzing visual features would require the excess to the video of the conversations which might not be feasible in every case while the analysis on acoustic features can be done in real-time while the conversation is taking place as we’d just need the audio data for accomplishing our task.We checked the distribution of labels with respect to emotions and gender and found that while the data is
balanced for six emotions viz. neutral, happy, sad, angry, fear and disgust, the
number of labels was slightly less for surprise and negligible for boredom. While
the slightly fewer instances of surprise can be overlooked on account of it being a
rarer emotion, the imbalance against boredom was rectified later by clubbing
sadness and boredom together due to them being similar acoustically. It’s also worth
noting that boredom could have been combined with neutral emotion but since both
sadness and boredom are negative emotions, it made more sense to combine
them.The idea behind creating this project was to build a machine learning model
that could detect emotions from the speech we have with each other all the time.
Nowadays personalization is something that is needed in all the things we
experience everyday. So why not have an emotion detector that will gauge your
emotions and in the future recommend you different things based on your mood.
This can be used by multiple industries to offer different services like marketing
companies suggesting you to buy products based on your emotions, the automotive
industry can detect the person's emotions and adjust the speed of autonomous cars
as required to avoid any collisions etc
