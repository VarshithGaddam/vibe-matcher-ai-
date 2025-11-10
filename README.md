# Vibe Matcher - AI-Powered Fashion Recommendation System

A semantic search system that matches fashion products to vibe queries using OpenAI embeddings and cosine similarity.

## Quick Start

### 1. Setup
```bash
pip install -r requirements.txt
```

### 2. API Configuration
The notebook is pre-configured with OpenRouter API access. No additional setup needed!

### 3. Run the Notebook
Open `vibe_matcher.ipynb` in Jupyter or Google Colab and run all cells.

## What It Does

- **Input**: Vibe query like "energetic urban chic"
- **Process**: Embeds products and query using OpenAI's text-embedding-ada-002
- **Output**: Top 3 matching products ranked by cosine similarity

## Features

✅ 8 mock fashion products with diverse vibes  
✅ OpenAI embeddings for semantic understanding  
✅ Cosine similarity matching with threshold detection  
✅ Performance metrics and visualization  
✅ Edge case handling and fallback logic  
✅ Comprehensive evaluation with 3+ test queries  

## Project Structure

```
.
├── vibe_matcher.ipynb    # Main notebook with all code
├── requirements.txt      # Python dependencies
└── README.md            # This file
```

## Evaluation Metrics

- **Similarity scores** for match quality (>0.7 = good match)
- **Query latency** tracking and visualization
- **Edge case testing** for robustness

## Key Insights

The system successfully demonstrates semantic search for fashion, with potential improvements including:
- Vector database integration (Pinecone/Weaviate)
- Hybrid search with metadata filters
- Multi-modal embeddings with images
- Personalization layer

## Assignment Completion

This project fulfills all requirements:
- ✅ Data Prep: 8 products with descriptions and vibe tags
- ✅ Embeddings: OpenAI text-embedding-ada-002 integration
- ✅ Vector Search: Cosine similarity with sklearn
- ✅ Testing: 3+ queries with metrics (>0.7 threshold)
- ✅ Reflection: Improvements and edge cases documented

---

Built for Nexora AI Assignment
