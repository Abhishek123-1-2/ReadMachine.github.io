# SQuAD-QA
Question answering on SQuAD 1.1 dataset

## Results
The trained models obtain the following results on SQuAD-1.1 dev benchmark:
| Model                        | F1            | EM    |
| ---------------------------- |:-------------:| -----:|
| ALBERT                       | 86.97         | 78.39 |
| BERT                         | 81.51         | 71.82 |
| DistilBERT                   | 78.96         | 68.68 |
| DistilROBERTA                | 87.74         | 80.39 |
| DistilROBERTA + Linear Layer | **88.09**     | **80.93** |
