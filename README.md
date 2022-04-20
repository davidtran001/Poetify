# Poetify
Poetify is a NLP Machine Learning pipeline written in Python on Jupyter Notebook, using the PyTorch library. This neural network is built with transformer architecture functions to transform internet reviews into stylized poems. It does so by taking a review as an input, summarizes the review, and generates poems using the shortened summary.

# Web Application
Users can try out Poetify using the Poetify [web application](https://poetify.anvil.app/) built with [Anvil](https://anvil.works/).

# Contributors
This project was co-developed by David Tran (www.github.com/davidtran001), Stephen Wang (www.github.com/Stephenwang3801), William Sati (www.github.com/WilliamSati), and Percy Wang (www.github.com/junwjie).

For more information regarding the project regarding models, data processing, and architecture please click the link below: https://github.com/Stephenwang3801/Poetify/blob/main/Poetify%20Desc.pdf

|Model Architecture|
|------------------|
|<img src="https://github.com/Stephenwang3801/Poetify/raw/main/Images/Model%20Architecture.png?raw=true">|

|Example of what the model does:|
|-------------------------------|
|<img src="https://github.com/Stephenwang3801/Poetify/blob/main/Images/Problem%20Break%20down.png?raw=true">|

|Context Transfer|
|------------------|
|<img src="https://user-images.githubusercontent.com/46908974/142655752-899f0bc8-c67a-4c6a-81f4-b93ce4d4d47e.png">|
|*Highlighted text represents the text in the input that had their subject and sentiment transferred to the output poem. Blue represents how the music subject, text highlighted in red represents the calm and quiet sentiment.*|

# Datasets
Poetify was trained on various review and poem datasets sourced from [Kaggle](https://www.kaggle.com/)

[Haiku Dataset](https://www.kaggle.com/hjhalani30/haiku-dataset)

[Complete poetryfoundation.com dataset](https://www.kaggle.com/johnhallman/complete-poetryfoundationorg-dataset)

[Amazon Reviews for Sentiment Analysis](https://www.kaggle.com/bittlingmayer/amazonreviews)
