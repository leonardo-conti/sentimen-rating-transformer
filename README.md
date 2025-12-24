# sentimen-rating-transformer
# Professor Rating Prediction Using Transformer Models

This project fine-tunes a BERT-based transformer model to predict professor star ratings (1–5) from PlanetTerp review text.

## Overview
- Collected real student reviews via the PlanetTerp API
- Fine-tuned BERT using PyTorch and HuggingFace Transformers
- Achieved 68.3% accuracy and 93% off-by-one accuracy

## Tech Stack
- Python
- PyTorch
- HuggingFace Transformers
- BERT
- NLP / Machine Learning

## Results
- Strong performance on extreme ratings (1★, 5★)
- Most errors within ±1 star
- Mid-range ratings are inherently ambiguous

## Future Work
- Expand dataset to more professors
- Explore larger transformer models
- Improve performance on neutral sentiment
