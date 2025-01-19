# Jester---Movie-Recommendation-System (Data Mining)

## Introduction
This project aims to develop a movie recommendation system using data mining techniques, focusing on association rule mining and collaborative filtering. The dataset used is the Jester dataset, containing user ratings for jokes.

## Features
- **Data Preprocessing**: Handling missing values, data normalization, and feature scaling.
- **Association Rule Mining**: Implementing Apriori and FP-Growth algorithms to generate recommendations.
- **Collaborative Filtering**: Utilizing weighted ratings to improve recommendation accuracy.
- **Visualization**: Generating visual representations of recommendations and data distributions.

## Requirements
To run this project, you need the following libraries:
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- MLxtend

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/OmphemetseSenna-Ops/Jester---Movie-Recommendation-System
2. Navigate to the project directory:
   ````
   pip install -r requirements.txt
3. Run the main script:
   ````
   python main.py

## Methodology
The following methods are employed in this project:

- **Data Handling**: Loading and cleaning the dataset, including replacing missing values.
- **Correlation Analysis**: Analyzing correlations between jokes to determine relationships.
- **Recommendation Algorithms**:
  - **Apriori Algorithm**: Generates frequent itemsets and association rules based on user ratings.
  - **FP-Growth Algorithm**: An efficient method for finding itemsets without candidate generation.
- **Visualization**: Using heatmaps, scatter plots, and bar charts for analysis and presentation of findings.

## Results
The project provides:
- Top 5 joke recommendations using both the Apriori and FP-Growth algorithms based on raw and weighted ratings.
- Visualizations for:
  - Distribution of ratings across jokes.
  - Correlation matrices for jokes.
  - Average joke rating vs. number of ratings.

## Conclusion
This project showcases the effectiveness of data mining techniques in creating a movie recommendation system. The results indicate that both the Apriori and FP-Growth algorithms can successfully generate valuable recommendations.

## Future Work
- Improve performance of the recommendation algorithms.
- Incorporate more advanced data mining techniques, such as clustering.
- Include additional features such as user demographics and joke genres for better recommendations.

## License
This project is licensed under the MIT License.

## Acknowledgements
- Thanks to the developers of the Jester dataset for providing a rich set of ratings for this analysis.
- Special thanks to the community resources for Pandas, NumPy, and Scikit-learn which aided in the development of this project.