
# Sentiment Analysis & Text Classification

### Decoding User Emotions: Sentiment Analysis for Streaming Success

## 🎯 About This Project

What if you could read every customer's mind? This project gets pretty close! I analyzed 119,000+ NetElix app reviews and 8,800+ movie descriptions to understand what users really think and more importantly, why they think it.

## 💡 The Counterintuitive Discovery

Here's the plot twist: **negative reviews get more engagement than positive ones!** Our analysis revealed that critical feedback receives significantly more "thumbs up" from other users. This suggests that customers value honest, critical reviews more than glowing testimonials.

I also learned that **class imbalance is a silent accuracy killer**. Our text classification model achieved 70% accuracy but struggled with the minority "TV Show" class. This taught me that overall metrics can hide important weaknesses.

## 📊 What We Uncovered

### Sentiment Patterns That Matter:
- **75% of reviews are neutral** - Users mostly comment without strong emotion
- **17% positive vs 8% negative** - But negative reviews drive conversation
- **Negative reviews get 12.9% more engagement** - Critical feedback resonates

### App Version Insights:
- Identified most-loved app versions through review volume and sentiment
- Discovered specific features that drive positive vs negative feedback
- Found that stability updates generate more praise than new features

### Regional Content Preferences:
- **Action and drama** dominate globally, but regional variations exist
- **Country-specific trends** reveal opportunities for localized content
- **Release timing matters** - January-February see peak engagement

## 🛠️ Technical Implementation

### Text Classification Pipeline:
- **CountVectorizer** for term frequency analysis
- **Multinomial Naïve Bayes** for movie/TV show classification
- **Random UnderSampling** to handle class imbalance
- **70% accuracy** with better performance on "Movie" class

### Sentiment Analysis Approach:
- **VADER sentiment analyzer** for polarity scores
- **Word frequency analysis** with NLTK
- **Word clouds** for visual theme identification
- **Correlation analysis** between sentiment and engagement metrics

