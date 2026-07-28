# Iris Flower Classifier API

A machine learning application that predicts Iris flower species using sepal and petal measurements. Includes a REST API and a basic web interface.

## Classes

* Iris Setosa
* Iris Versicolor
* Iris Virginica

## Tech Stack

Python, Flask/FastAPI, Scikit-learn, Pandas, NumPy, HTML, CSS

## Setup

```
git clone https://github.com/your-username/iris-ml-api-webapp.git
cd iris-ml-api-webapp
pip install -r requirements.txt
python app.py
```

Open: http://127.0.0.1:5000/

## API

**POST /predict**

```
{
  "sepal_length": 5.1,
  "sepal_width": 3.5,
  "petal_length": 1.4,
  "petal_width": 0.2
}
```


Response:

```
{
  "prediction": "Iris-setosa"
}
```

## Author

Riya Shukla
https://github.com/riyaashukla30
