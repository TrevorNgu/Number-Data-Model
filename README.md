# Number-Data-Model
Python Code that can be added to Google Colab to generate a Tensorflow Model.
NumberDataTest is used for the raw DIDA dataset, NumberDataV1M is for the converted DIDA dataset after cortical filters.

REQUIREMENTS:
- Google Colab
- A folder in your drive named "NumberData"
- DIDA dataset which can be found here (https://didadataset.github.io/DIDA/)

Download the DIDA dataset into the NumberData folder. I used the 10000, so the code will automatically work with that type. You can adjust the code to work with other datasets.

HOW TO USE:
1. Run the python code on Colab to enter a console based option system
2. Create Model to generate a model variable
3. Train Model to fit the model with the dataset. The model will automatically save into the NumberData folder

To make predictions, you need to make a "predict" folder in the temporary colab directory and put your JPEG/V1M files in there. Selecting predict will let you input a string for the model to read from and test.
