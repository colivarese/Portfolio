## Cesar Olivares
This is my portfolio of Data Science/Machine Learning projects.

# Potato Leaves Disease Classification on Google Cloud
On this project a Convolutional Neural Network model is trained using images from potato leaves,
with three clases, healthy and two with diseases. The model achieves an accuracy around 0.95.
The model is used in a React local webpage having a drag and drop function, which returns the
predicted class with its accuracy.

<p align="center">
<img width="360" alt="Captura de Pantalla 2022-01-03 a la(s) 19 39 26" src="https://user-images.githubusercontent.com/80273045/148007912-17dc44c5-2dc6-44fa-9126-0e345ffda445.png"> <img width="360" alt="Captura de Pantalla 2022-01-03 a la(s) 19 40 20" src="https://user-images.githubusercontent.com/80273045/148008320-02b47121-1c63-4eca-84c2-4f2a8664b7bf.png">
</p>

The trained model is then loaded into Google Cloud Platform, connected with the FastAPI to get
predictions with a cloud server and tested with Postman.

# Sentiment Analysis on Movies Reviews
On this project a pre-trained BERT Model was taken from Hugging Face, specifically a Multilingual uncased sentiment to assign a value to a sentence given on the sentiment of the text. Data was retrieved from the popular website RottenTomatoes using the Request Dependency, processed with the BeautifulSoup library and RegEx, finally formatted on a Pandas DataFrame.
<p align='center'>
<img width="180" alt="Captura de Pantalla 2021-12-22 a la(s) 0 21 26" src="https://user-images.githubusercontent.com/80273045/148016857-61fec97d-d687-45cc-9d0a-fdcbf4e21292.png">
</p>

