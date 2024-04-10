# voice-emotion-classification
**Voice Classification Project for Machine Learning Class 0451 with Catie Baxter and Otis Milliken**

## Abstract
Emotion classification allows for an improved understanding of human communication, as the meaning of speech can vary depending on the tone in which it is spoken. It can be difficult for computers to recognize nuances in human communication. Our goal is to create a model that can classify audio files by the emotion denoted in the tone. We will evaluate our success by our improvement in data manipulation skills and our understanding of how to build an efficient model.

## Motivation and Question
Our aim for this project is to convert the audio files in our data into vectorized information that we can use to classify the emotional tone used by the actor. We have a large data set which we will use to create predictive and exploratory models that will help us generate specific hypotheses regarding what elements of the audio indicate certain emotions. The target variable and other information about the file are included in the names of the audio files so we will also need to extract that information as we make our data usable. We then hope to use the tools and algorithms we have learned in class to build a model that will be able to classify emotion with a fair amount of accuracy. Speech emotion recognition falls under the category of affective computing which aims to investigate interactions between humans and computer and inform the optimization of these exchanges.[^1] It is important to be able to classify emotion because so much of understanding human speech rests on understanding the tone for which something is said. Someone saying "I hate you" in a fun loving tone means something incredibly different than "I hate you" in a deep angry tone. So while classify emotion is in itself an intriguing problem, it is also imperative for the grander vision of computers understanding human language effectively.

## Planned Deliverables
Our planned deliverables will include a Python package that contains all of the code we use to prepare our data, analyze the audio files, and build the model. We will also include a Jupyter notebook that illustrates the use of this package.

If everything works out, our full success would be if we are able to build a model that correctly classifies the emotion of an audio recording with a substancial amount of accuracy. We would also create clear and conscise functions that allow us to vectorize and visualize the audio files so that we fully understand why the model behaves as it does. 

Even if we are not able to accomplish everything we would like, our partial success would be if are able to build a model that correctly classifies the emotional tone of an audio file with an accuracy greater than randomly assigning categories

## Resources Required
We are using the Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS). This dataset can be found on Zenodo at https://zenodo.org/records/1188976#.XrC7a5NKjOR. It contains 24 professional actors (12 male, 12 female) speaking identical phrases in calm, happy, sad, angry, fearful, surprise, and disgust tone in a neutral North American accent. The data files exist in audio format and have naming conventions that described the tone that they are. The tones were rated 10 times by 247 other individuals and put into emotional categories.  
While the data set is much larger and contains video and song files, we will only be examining the audio data files 

## Learning Goals
Otis: Catie and I picked this project because we wanted to work with data that resembles more what you may encounter in the real world. I have never worked with audio files before and I'm excited to learn how to vectorize and draw data from them. Additionally, I'm excited to dig into the different models that people use for emotion classification and deepen my model making skills.

Catie: My goal for this project is to learn more about working with audio data. While I have done some light data cleaning before, I do not have a lot of experience really having to manipulate the data I select to make it usable - which is a lot closer to anything I would be doing in the real world. I hope to also do a deeper dive into the machine learning models we have discussed in class and learn about the best way to select an optimal algorithm for our research. I want to improve my collaboration skills and work with Otis to ensure that we are communicating in a clear and efficient manner. 

## Risk Statement
The main risks associated with this project is that it may be more involved than we realized. Neither of us have worked with audio files or emotion classification before which makes accurately estimating the amount of time and effort required difficult. While this does worry us, we are optimistic that we can produce some kind of model even if it might not be the most optimal or accurate one possible.

Through listening in on the audio files, we also noticed that how obvious different supposed emotions were varied greatly between actors. Sometimes we even had difficulty trying to categorize the emotion that the actor was trying to exemplify. We're not fully sure how to handle this issue but we might decide to remove some data we find hurts our model training or potential add personal audio files to increase the range that the model will train on.

## Ethics Statement
1. Our project could overall improve machines that are trying to interpret human emotion. This could be important in any device that uses speech because understanding tone is crucial for understanding human speech. In this way, our model could help anyone who wants to have speech recognition on their devices for ease of use. It could also help blind or seeing impaired people because their speech could be better read by a device.
2. While we're excited about the prospects of our project, we understand that it will exclude the majority of English speakers and all non-English speakers. This is because our training data only contains American English voices. This means that our models will most likely work siginificantly worse for people in different countries or with accents. We understand that this may perpetuate existing algorithmic inequities and possible xenophonic or racist attitudes. However with this understanding and the knowledge that we won't spread our model, we feel confortable undertaking our project as a learning exercise. 
3. We believe that our project offers a crucial stepping stone for language comprehension. While our project in its current form will most likely exlude people, it offers a methodology that future research can build on with more comprehensive data. We hope that our project also serves to teach us valuable insights about emotion classifications and audio vectorization.

## Timeline
Week 3: After 3 weeks we hope to have been able to vectorize our audio files and have usable data. Ideally, we would like to have explored the data and generated our hypotheses. 

Week 6: After 6 weeks we hope to have implemented our machine learning model and tested our model on a custom testing data set that we've created. We also hope to have some analysis on how a variety of accents impact that accuracy. 

## Works Cited
[^1] Cambria, E., Das, D., Bandyopadhyay, S., Feraco, A. (2017). Affective Computing and Sentiment Analysis. In: Cambria, E., Das, D., Bandyopadhyay, S., Feraco, A. (eds) A Practical Guide to Sentiment Analysis. Socio-Affective Computing, vol 5. Springer, Cham. https://doi.org/10.1007/978-3-319-55394-8_1
