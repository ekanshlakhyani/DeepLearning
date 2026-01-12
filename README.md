# DeepLearning
Glassdoor Review Prediction & Insight Generation

Developed and trained a deep learning model to predict Glassdoor employer ratings using both structured features and natural language from reviews.

Model Architecture:
Implemented a Bidirectional LSTM neural network with word embeddings to process employee-written text and predict company ratings (1 to 5 scale). Achieved an R² of 0.63 and MSE of 0.3284 on training data.

Data Size & Structure:
Used 600,000+ reviews (combined structured + unstructured text data).
Cleaned and engineered features from pros, cons, and overall sentiment.
Predicted ratings for 100,000 unseen reviews.

Analytical Insights:
Segmented firms into low-, mid-, and high-quality tiers based on predicted average ratings and performed text analysis to extract actionable insights for each:

Low-Quality Firms: Common complaints include poor management, low pay, and staffing issues.
Mid-Quality Firms: Employees wanted clearer paths to promotion and better workload balance.
High-Quality Firms: Praise centered on flexible work, strong culture, and supportive teams—but with concerns about high expectations and slow processes.

Business Recommendations: Provided customized improvement strategies for each firm type—blending economic segmentation with NLP-driven feedback mining.

Causal Interpretation:
Discussed the limitations of observational text data and proposed steps to establish causal links between management changes and employee satisfaction.
