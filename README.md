# English-French-Translation-System
A comprehensive machine learning project implementing bidirectional English-French translation using state-of-the-art neural machine translation models. This project demonstrates various translation approaches, quality evaluation metrics, and practical applications for language processing tasks.
This project implements a complete translation pipeline using two different neural machine translation approaches:

Marian MT Models: Specialized translation models trained specifically for English-French language pairs
T5 Models: Multi-task transformer models adapted for translation tasks through task-specific prompting

The system provides bidirectional translation capabilities (English ↔ French) with comprehensive quality evaluation and performance analysis.
Features
Core Translation Capabilities

Bidirectional Translation: Seamless translation between English and French
Automatic Language Detection: Intelligent detection of input language for automatic translation
Multiple Model Support: Compare results from different translation architectures
Batch Processing: Efficient translation of multiple texts simultaneously

Quality Evaluation

BLEU Score Calculation: Industry-standard translation quality metrics
Back-Translation Testing: Round-trip translation for consistency evaluation
Length Ratio Analysis: Statistical analysis of translation length patterns
Visual Performance Metrics: Comprehensive charts and graphs for result analysis

Advanced Features

Domain-Specific Testing: Evaluation across different text domains (Technology, Science, Business, Literature)
Model Comparison: Side-by-side performance analysis of different translation approaches
Error Handling: Robust processing with comprehensive error management
Statistical Analysis: Detailed performance statistics and trend analysis

Technical Implementation
Models Used

Helsinki-NLP Marian MT: opus-mt-en-fr and opus-mt-fr-en models
Google T5: t5-small model with task-specific prompting
Hugging Face Transformers: Complete integration with transformers library

Key Libraries

transformers: Hugging Face transformer models and tokenizers
torch: PyTorch deep learning framework
datasets: Dataset loading and processing utilities
sacrebleu: BLEU score calculation for translation evaluation
matplotlib/seaborn: Data visualization and performance analysis
pandas/numpy: Data manipulation and statistical analysis
