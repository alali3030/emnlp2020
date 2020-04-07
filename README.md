# digital_strategy_analytics
Digital Strategy Analytics is part of my PhD thesis to iinvestigate the digital strategy of Fortune 500 companies by mining their earnings calls.

There are 2 Notebooks:

1. Multi-label classifier to identify digital strategy
2. Multi-class classifier to identify digital maturity


Multi-label score is f1-score of 0.59 threshold of 0.35, roc auc score is 0.837:
                 
                precision    recall  f1-score   support
          BM       0.40      0.12      0.18        17
         Ops       0.55      0.64      0.59        33
         MnA       0.00      0.00      0.00        10
          CX       0.57      0.65      0.61        48
    Practice       0.35      0.29      0.32        24
     Product       0.66      0.79      0.72        84
     Enabler       0.56      0.73      0.63        62
         RnD       0.00      0.00      0.00         5

   micro avg       0.57      0.61      0.59       283
   macro avg       0.39      0.40      0.38       283
weighted avg       0.53      0.61      0.56       283
 samples avg       0.40      0.41      0.38       283

Initial iintuition is to add more labeled data for scores under 0.5 which are BM, MnA, Practice, and RnD
