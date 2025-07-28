Task 2: Auto Tagging Support Tickets using LLMs

 Objective
Automatically assign top 3 relevant tags to customer support tickets using large language models (LLMs).

Dataset
- Custom or public support ticket data (CSV)
- Each ticket has a text description and possible tags

 Approaches Compared
1. Zero-shot classification using `openai/gpt-3.5` or `facebook/bart-large-mnli`
2. Few-shot prompting with manual examples
3. Fine-tuned BERT model using `Trainer`

Tools & Libraries
- `transformers`
- `openai` 
- `pandas`, `sklearn`

Evaluation Metrics
- Precision@3
- Recall@3
- F1-score (multi-label)

Output
- Compare tagging performance of each LLM approach
- Efficient ticket classification pipeline
