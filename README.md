# language detection from text for English and Luganda

This will include text used and the notebook

## PS: 

The large vocab csv file needs alot of RAM to compute , therefore I propose using the smaller vocab csv

The notebook identified here was run using google colab 

You can find the csv file for either the larger or smaller vocab in the data folder


## To run this

Install the requirements in a virtual environment using 


Then you can start the app using

```
 gunicorn app:app
 ```

You can access the endpoint using 

```
http://127.0.0.1:8000/predict?text="Obumenyi bw’amateeka bufuukidde Pulezidenti n’eggwanga ekizibu."
```
## Origin of data used

[A parallel corpus dataset](https://zenodo.org/record/5864560)


## Origin of notebook used 

[notebook on kaggle](https://www.kaggle.com/code/basilb2s/language-detection-using-nlp)