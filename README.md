# Petfinder Adoption Prediction: 7th Place Solution

This repository contains the code and documentation for the 7th place solution in the Kaggle PetFinder.my Adoption Prediction competition. Our team, "We need a fulltime job", achieved a gold medal with this solution.

## The Competition

The goal of the competition was to predict the adoptability of pets based on a dataset of more than 150,000 animals from PetFinder.my, Malaysia's leading animal welfare platform. The dataset included tabular data, text descriptions, and images, making it a challenging and interesting problem.

## Our Solution

Our success in this competition was primarily due to extensive feature engineering and a robust validation strategy.

### Feature Engineering

We engineered a wide variety of features to capture as much information as possible from the dataset. These included:

*   **Improved JSON Parsing:** We extracted more information from the JSON data than the default parsers.
*   **Handcrafted Features:** We created features like relative pet age and interactions between health-related columns.
*   **NLP Features:** We used NLP techniques on the pet descriptions to extract sentiment and other textual features.
*   **Website-based Features:** We engineered features to mimic the PetFinder.my website's internal ranking and image SEO.
*   **Image-based Features:** We incorporated image dimensions and quality metrics.

### Modeling

Our final model was an ensemble of LightGBM and XGBoost, two powerful gradient boosting libraries.

### Validation Strategy

We used a double cross-validation strategy to ensure our model was robust and generalized well to unseen data.

## How to Use

### Dependencies

You can install the required dependencies using the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

### Data

The data for this competition can be found on the [Kaggle competition page](https://www.kaggle.com/c/petfinder-adoption-prediction/data).

### Running the Code

The `understanding_our_solution.ipynb` notebook contains the code for our solution. You can run the cells in the notebook to reproduce our results.

## Presentations

*   [Deep Learning For Puppies](presentations/Deep%20Learning%20For%20Puppies.pdf)
*   [KD_Milano_E2_Completo_REV02](presentations/KD_Milano_E2_Completo_REV02.pdf)

## The Team

Our team, "We need a fulltime job", was composed of 3 Kaggle masters and 3 Kaggle experts from three different countries.