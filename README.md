# cynbit-revio-ai-review-intelligence-poc
AI-powered customer review sentiment analysis, aspect detection, complaint prioritization and response recommendations using Python and NLP.
# Revio Intelligence — AI Review Analysis PoC

A Jupyter Notebook proof of concept for the Cynbit AI/ML Engineer Intern assessment.

## Features
- TF-IDF + Logistic Regression sentiment classification
- Rule-based aspect detection (delivery, product quality, support, pricing, usability)
- Transparent heuristic review prioritization
- Human-review response templates
- Basic visual summaries

## Run locally in JupyterLab
1. Create/activate a Python environment.
2. Install JupyterLab: `pip install jupyterlab`
3. Open this folder in a terminal and run: `jupyter lab`
4. Open `Revio_AI_Review_Intelligence_PoC.ipynb`.
5. Run cells from top to bottom.

The notebook includes a `%pip install` cell for required libraries.

## Important limitations
This is an illustrative PoC using a small hand-labelled sample dataset. Its evaluation metrics are not production performance claims. Aspect detection and response generation are rule/template based. No Cynbit systems, customer data, external LLM or APIs are connected.

## Suggested GitHub repository name
`cynbit-revio-ai-review-intelligence-poc`

## Suggested repository description
`A Jupyter-based NLP proof of concept for customer review sentiment analysis, aspect detection, complaint prioritization and human-approved response suggestions.`

## Suggested next steps
- Replace sample data with permissioned, anonymized and representative reviews.
- Build a larger labelled evaluation set.
- Compare a TF-IDF baseline with a fine-tuned transformer.
- Add a Streamlit UI or REST API after validating the baseline.
