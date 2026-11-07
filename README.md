# Ireland IMF Financial Stability Analysis Using LLMs

## Project Overview
This project analyses Ireland's 2025 IMF Article IV Consultation Report using Large Language Models (LLMs), Retrieval-Augmented Generation (RAG) and Python. It extracts economic information, generates summaries and presents the findings in a four-panel dashboard.

## Tools and Models
- **Language Model:** Qwen2.5-1.5B-Instruct
- **Embedding Model:** all-MiniLM-L6-v2
- **Vector Search:** FAISS
- **Platform:** Google Colab
- **Libraries:** PyPDF, Transformers, Pandas, Matplotlib, Seaborn, Sentence Transformers

## Project Tasks
1. Extract and clean text from the IMF PDF.
2. Generate section summaries and an executive summary.
3. Analyse seven financial themes and key economic indicators.
4. Identify economic strengths and vulnerabilities.
5. Implement RAG for document-based question answering.
6. Evaluate outputs using LLM-as-a-Judge.
7. Create a four-panel financial dashboard.

## How to Run
1. Open the `.ipynb` notebook in Google Colab.
2. Enable GPU in the runtime settings.
3. Upload the Ireland IMF 2025 PDF.
4. Run all cells sequentially.
5. Review the generated JSON files, summaries, evaluation results and dashboard.

## Dataset
IMF Country Report No. 25/128 — Ireland: 2025 Article IV Consultation.

## Note
The project uses locally executed models and does not require API keys. Numerical indicators and generated findings should be verified against the original IMF report.
