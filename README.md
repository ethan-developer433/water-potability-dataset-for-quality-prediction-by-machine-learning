# water-potability-dataset-for-quality-prediction-by-machine-learning
The dataset consists of water quality measurements for approximately 2,500 samples, categorized as potable (1) or non-potable (0) for prediciting water quality
The dataset contains water quality measurements for approximately 2,500 water bodies, with each record categorized as either potable (safe) or non-potable (unsafe).


Feature Attributes
The dataset includes the following columns:
ph: The pH level of the water, indicating its acid-base balance.
Hardness: The concentration of calcium and magnesium salts in the water.
Solids (Total Dissolved Solids): The concentration of dissolved substances in the water, measured in ppm.
Chloramines: The amount of Chloramines present in the water.
Sulfate: The concentration of sulfates dissolved in the water.
Conductivity: The electrical conductivity of the water.
Organic_carbon: The amount of organic carbon present in the water.
Trihalomethanes: The concentration of Trihalomethanes.
Turbidity: A measure of light-emitting properties indicating water clarity.
Potability (Target): A binary classification where 1 indicates potable and 0 indicates non-potable.

#Key Features for Predicting Potability
Through statistical analysis and feature evaluation, the following attributes have been identified as the most significant predictors of water safety within this dataset:
Solids (Total Dissolved Solids): This feature consistently emerges as the most influential factor in determining potability. High variations in dissolved solids are strongly correlated with changes in water safety classification.
pH Level: As a fundamental indicator of water chemistry and potential contamination, the pH level serves as the second most critical feature for model accuracy.
Turbidity: Ranking as the third major predictor, turbidity provides essential information about the physical clarity of the water, which is a key indicator of its overall safety and quality.
