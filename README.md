# parkinsons-detection
Detecting Parkinson's disease from voice measurements using Oxford Parkinson's Disease Detection Dataset 


## Dataset
Oxford Parkinson's Disease Detection Dataset 
195 voice recordings from 31 people
23 with Parkinson's disease, 8 healthy
22 voice measurements per recording

## Model
Support Vector Machine (SVM)

## Results
- Accuracy: 90%
- Recall for Parkinson's: 100% (zero missed cases)
- Precision for healthy: 100%

## Key finding
In medical diagnosis, recall matters more than accuracy.
Missing a real Parkinson's case is more dangerous than a false alarm.
This model caught 100% of actual Parkinson's patients.

## Tools
Python, pandas, scikit-learn, matplotlib
