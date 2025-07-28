# 🧠 Task 1: News Headline Classification using BERT

Objective
Fine-tune a pretrained BERT model to classify news headlines into 4 categories using the AG News dataset.

Dataset
- **Source:** HuggingFace Datasets (`ag_news`)
- **Classes:** World, Sports, Business, Sci/Tech
- **Samples:** 120K training, 7.6K testing

Steps
1. Load AG News dataset
2. Tokenize using `bert-base-uncased`
3. Fine-tune BERT using `Trainer`
4. Evaluate accuracy on test data
5. Deploy using Gradio

Tools & Libraries
- `transformers`
- `datasets`
- `sklearn`
- `Gradio`

Output
- Trained classification model
- Gradio interface for real-time predictions

Metrics
- Accuracy
- F1 Score
