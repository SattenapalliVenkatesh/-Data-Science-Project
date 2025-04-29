English-to-SQL Translator
This project uses T5-small and CodeT5-small Transformer models to translate English questions into SQL queries. It includes:

Fine-tuning on a small custom dataset (~100 examples)

Sensitivity analysis of decoding parameters (beam width, temperature, top-k, top-p)

Comparison of general-purpose vs. code-specialized models

 Key Finding
CodeT5-small consistently generates more accurate and stable SQL queries than T5-small.
