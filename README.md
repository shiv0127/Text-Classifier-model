# Text-Classifier-model
 A Text Classifier API using FastAPI and scikit-learn to categorize text inputs. It preprocesses text (e.g., TF-IDF), trains a model (e.g., SVM), and provides a /predict/ endpoint for predictions, returning categories and confidence scores. Ideal for tasks like sentiment analysis or spam detection.


.
.

The project structure can be summarized as follows:
text_classification/
├── app/
│   ├── main.py         # FastAPI app
│   ├── routes.py       # API routes
├── model/
│   ├── train.py        # Model training
│   ├── predict.py      # Prediction logic
├── requirements.txt    # Dependencies
└── README.md          # Documentation

.
.
.
.
To run the application:

Install dependencies: pip install -r requirements.txt
Train the model: python model/train.py
Run FastAPI: uvicorn app.main:app --reload
