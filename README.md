# Optimizing Meal Planning via Mixed-Integer Optimization

### Problem Statement
Meal planning is often complex, requiring balance across macronutrients, calorie intake, and dietary variety. This project addresses these challenges by developing an optimization framework that generates high-calorie, nutritionally balanced meal plans while minimizing undesirable components. The methodology is grounded in mixed-integer optimization and uses data-driven clustering for food categorization.

### Key Contributions
- **Single Meal Optimization:** Constructs nutrient-dense, balanced meals by selecting one food item per cluster, considering calorie and weight trade-offs.
- **Adaptive Meal Planning:** Extends the optimization to sequential meals, ensuring diversity and meeting cumulative nutritional requirements.
- **Robustness to Uncertainty:** Models uncertainty in nutrient data, improving real-world applicability.

## Repository Structure

- **`preprocessing/`**: Contains scripts for data cleaning and clustering food items into categories (e.g., carbs, proteins, vegetables).
- **`modelling/`**: Includes optimization models for single and sequential meal planning.
- **`results/`**: Contains analysis outputs and visualizations of the optimized meal plans.
- **`report/`**: The final project report detailing the methodology, experiments, and results.

## Results Summary

- The optimized meal planner consistently outperforms baselines (e.g., semi-random or typical meals), achieving superior adherence to nutritional requirements.
- Adaptive sequential modeling ensures dietary diversity across multiple meals while maintaining caloric and nutrient balance.
- Robust optimization accommodates uncertainties in nutrient data, further enhancing the model's reliability.

## Future Work
Planned extensions include integrating cost and utility preferences into the model to enhance real-world applicability.

---
