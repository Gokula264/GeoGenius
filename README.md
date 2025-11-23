📍 GeoGenius — AI-Driven Location Intelligence for Coffee Shop Expansion

GeoGenius is an end-to-end AI Location Intelligence System that recommends the best places in India to open a coffee shop.
It combines RAG (Retrieval-Augmented Generation), document embeddings, scoring algorithms, and LLM-based business reasoning to simulate real-world commercial site-selection workflows used by major retail brands
🚀 Features
✅ 1. Multi-City Dataset (17 Locations Across India)

Includes commercial hotspots from:

Mumbai

Hyderabad

Bengaluru

Delhi NCR

Andhra Pradesh (Vizag, Guntur, Anantapur)
…and more.

Each location contains:

Avg. daily footfall

Number of coffee shops (competition)

Rent index

Median income

State + zipcode

✅ 2. Intelligent Embedding-based Retrieval (RAG)

Powered by SentenceTransformers (MiniLM-L6-v2)

Converts each location into a descriptive document

Generates embeddings

Performs semantic search (cosine similarity)

Retrieves the most relevant areas to the user’s query

Example:
"Best area for a youth-focused cafe in India?”

✅ 3. Geo-Scoring Engine

A custom scoring model that evaluates each location using weighted parameters:

Footfall (positive weight)

Competition (negative weight)

Rent index (negative weight)

Outputs:
✔ Score (normalized)
✔ Confidence value
✔ Ranked recommendation list

Supports different business strategies:

Balanced

Low competition

Low rent

✅ 4. LLM-Based Explanation Generator

Uses a lightweight GPT-2 model to produce clean, 1-sentence business explanations:

No hallucinations

Uses only available dataset facts

Strict repetition-cleaning logic

Example output:

“Cyber City, Gurugram is recommended because high footfall and moderate competition give it the strongest overall score.”

✅ 5. Complete End-to-End RAG Workflow

✔ Data → Documents
✔ Embeddings → Retrieval
✔ Scoring Engine → Ranking
✔ LLM → Explanation
✔ Final Recommendation with Provenance Table

🧠 Tech Stack
Component	Technology
Embeddings	SentenceTransformers (MiniLM-L6-v2)
LLM	DistilGPT-2 (Transformers)
Scoring Engine	NumPy, Pandas
Retrieval	Cosine Similarity (scikit-learn)
Notebook	Google Colab
Programming Language	Python
