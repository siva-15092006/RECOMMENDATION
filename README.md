# RECOMMENDATION
**COMPANY**: CODETECH IT SOLUTIONS

**NAME**: PAKALAPATI SIVA KUMAR RAJU

**INTERN ID**: CT04DN951

**DOMAIN**: JAVA PROGRAMMING

**BATCH DURATION**: MAY 18th,2025 to JUNE 18th, 2025

**MENTOR NAME**: NEELA SANTHOSH KUMAR

# AI-BASED-RECOMMENDATION-SYSTEM
A JAVA PROGRAM WITH A WORKING RECOMMENDATION ENGINE AND SAMPLE DATA

# Recommendation System Using Apache Mahout

This is a simple recommendation system implemented in Java using the Apache Mahout library. The system provides product recommendations based on user preferences.

# Project Structure

- `src/ProductRecommendation.java`: The main Java program to generate product recommendations.
- `data/user_ratings.csv`: Sample dataset with user ratings for different items.
- `pom.xml`: Maven configuration file for dependencies.

# Setup

1. Clone the repository.
   ```bash
   git clone https://github.com/your-username/recommendation-system.git
   cd recommendation-system
2. Set Up Apache Mahout
    - Add Mahout dependencies in your pom.xml (if using Maven).
    - Ensure you have Java installed and configured correctly.
3. Load the Dataset (user_ratings.csv)
    - Read the dataset using BufferedReader or CSVReader in Java.
    - Convert it into a DataModel object compatible with Mahout.
4. Implement Collaborative Filtering
    - Use Mahout’s GenericItemBasedRecommender or GenericUserBasedRecommender.
    - Create a DataModel with user-item interactions.
    - Set up a similarity metric like PearsonCorrelationSimilarity or EuclideanDistanceSimilarity.
5. Generate Recommendations
    - Use Mahout’s recommender methods to suggest items. 


   
