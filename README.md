# Customer Perception Analysis – Factor Analysis (Python)

## Problem
Understand how customers perceive toothpaste attributes and identify underlying dimensions driving perception.

## Dataset
Survey data covering attributes such as:
- Anti-cavity
- Gum strength
- Whitening
- Fresh breath
- Tooth decay prevention
- Filling tooth gaps  
(Likert scale responses)

## Approach
- Cleaned and standardized survey data
- Applied Factor Analysis using scikit-learn
- Visualized results using a perceptual (factor) map

## Key Insights
- Customer perceptions cluster into two clear dimensions:
  - Clinical dental protection
  - Cosmetic and sensory appeal
- Most attributes load strongly on only one dimension
- No feature strongly bridges both, indicating a potential positioning opportunity
## Factor Map Visualization

The perceptual map below visualizes how toothpaste attributes cluster across two latent dimensions—clinical dental protection and cosmetic appeal.

![Factor Analysis Map](visuals/factor_map_png)

## Tools
Python, Pandas, Scikit-learn, Matplotlib

## Output
- Factor loading table
- 2D perceptual map visualizing customer perception clusters
