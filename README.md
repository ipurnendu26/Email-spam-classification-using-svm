# Email Spam Classification with a Linear SVM

A classical NLP notebook that transforms email text into sparse features and trains a support-vector classifier to distinguish spam from non-spam messages.

## Repository contents

- `SVM - Email Classification.ipynb`: preprocessing, feature extraction, training, and evaluation
- `emails.csv`: checked-in learning dataset

## Run locally

```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter lab
```

## Skills demonstrated

- Text normalization and vectorization
- Sparse linear classification
- Precision/recall tradeoff analysis
- Confusion-matrix interpretation

## Limitations

Spam filters operate under severe distribution shift and adversarial adaptation. Notebook results apply only to the included dataset and split. Deployment would require deduplication, time-aware evaluation, threshold tuning, sender/domain features, false-positive controls, drift monitoring, privacy review, and safe handling of untrusted message content.

## License

Code is available under the [MIT License](LICENSE). Dataset rights remain with the original publisher.
