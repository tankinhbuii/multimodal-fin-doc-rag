# Multimodal Financial Document RAG 📊📈🔍

An advanced Retrieval-Augmented Generation (RAG) system specifically designed for financial analysts. This system processes complex PDF reports by simultaneously analyzing text, tables, and graphical charts using Vision-Language Models (VLMs).

## 🌟 Key Challenges Addressed
- **Chart Interpretation:** Extracts insights directly from line charts, bar graphs, and pie charts.
- **Complex Table Parsing:** High-fidelity table extraction that maintains hierarchical relationships.
- **Contextual Reasoning:** Correlates visual data (e.g., a declining trend in a chart) with textual explanations (e.g., "supply chain issues").

## 🛠️ Technology Stack
- **VLM:** GPT-4o / LLaVA / Claude-3.5-Sonnet for multimodal reasoning.
- **Vector DB:** Qdrant / Pinecone for indexing textual and visual embeddings.
- **Document Processing:** Unstructured.io / PyMuPDF / OpenCV.

## 🚀 Usage
```bash
python pipeline.py --pdf annual_report.pdf --query "Summarize the revenue growth in Q3"
```