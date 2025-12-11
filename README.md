 Detecting Fake Airbnb Reviews Using NLP & Anomaly Detection

This project identifies potentially fake Airbnb reviews using:
-VADER Sentiment Analysis
-Feature Engineering (review length, frequency, time gaps)
-Isolation Forest anomaly detection
-Exploratory Visualization (KDE, boxplots, Venn diagram)

Project Structure
notebooks/       → final_project.ipynb (full code)
data/            → reviews_detailed.csv (Airbnb dataset)
visuals/         → saved plots
outputs/         → fake_reviews.csv, negative_reviews.csv
src/             → optional helper scripts

Techniques Used
-NLP (sentiment scoring with VADER)
-Unsupervised ML (Isolation Forest)
-Feature Engineering
-Data Cleaning & Preprocessing
-Visualization (boxplots, KDE, Venn diagram)

Key Results
-Fake reviews tend to be significantly longer
-Reviewer frequency and time gaps strongly influence anomaly scores
-Combining sentiment + anomaly detection increases reliability

Author
-Amina Sana