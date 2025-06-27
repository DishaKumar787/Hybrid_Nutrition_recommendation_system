# Hybrid_Nutrition_recommendation_system

A Python-based intelligent meal recommendation system that combines **BMI calculation**, **health profiling**, and **dietary filtering** to provide personalized food suggestions.

## Features

- Calculates BMI and categorizes health status (Underweight, Normal, Overweight, Obese)
- Visualizes BMI distribution using **Matplotlib** (Pie + Bar Charts)
- Collects health data: diseases, medications, allergies, dietary restrictions
- Filters food recommendations based on:
  - Maximum calorie limit
  - Allergies and medical conditions
  - Preferred diet (Vegetarian, Vegan, etc.)
- Displays recommendations in a clean table format using **Tabulate**

## Technologies Used

- **Python**
- **Pandas** – for dataset handling
- **Matplotlib** – for BMI distribution visualization
- **Tabulate** – for tabular display of meal suggestions

## Dataset Columns 

- `Food Recommendations`
- `Calories`
- `Protein`
- `Carbs`
- `Fats`
- `Diet`
- `Allergies`
- `Diseases`

## How to Run

1. Place `intelligent_health_meal_dataset.csv` in the same directory
2. Run the script:

```bash
python hybrid_nutrition_system.py
