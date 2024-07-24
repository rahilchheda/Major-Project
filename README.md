# Major-Project
Classification of Mice Based on Protein Expression Levels



Problem Statement: The objective is to identify subsets of proteins that are discriminant
between different classes of mice. The dataset includes protein
expression levels in the cerebral cortex of both control and Down
syndrome mice subjected to context fear conditioning. The aim is to
classify the mice into eight distinct classes based on genotype,
behavior, and treatment.


Steps Involved:
Data Preprocessing: Handle missing values. Normalize/scale the data. Encode categorical
variables if needed.
Exploratory Data Analysis (EDA): Summary statistics. Visualizations to understand data
distribution and class separability.
Feature Selection: Identify important features (proteins) using techniques like correlation
analysis, mutual information, or feature importance from models.
Model Training: Split the data into training and testing sets. Train classification models (e.g.,
Random Forest, SVM, Neural Networks). Tune hyperparameters using cross-validation.
Model Evaluation: Evaluate models using metrics like accuracy, precision, recall, and F1-
score. Identify the best-performing model.
Interpretation: Analyze the model to identify key discriminant proteins. Interpret the results in
the biological context.
Reporting and Analysis: Summary of key findings and their implications. Limitations of the
study. Recommendations for future research.





Conclusion:
Accurate Classification: The developed machine learning model successfully classified mice into one of
eight classes based on the expression levels of 77 proteins, with high accuracy and reliability. This
demonstrates the model's effectiveness in distinguishing between different combinations of genotype,
behavior, and treatment.

Key discriminant proteins identified: Feature selection add specific proteins and protein modifications
that are crucial for distinguishing between the classes. These key discriminant proteins provide valuable
insights into the biological mechanisms underlying learning and memory. Particularly in the context of
Down syndrome.

Impact analysis of Geno-type, Behavior and Treatment: The analysis revealed significant effects of
genotype (Control vs Trisomic), behavior (Context-shock vs Shock-context) and treatment (Saline vs
Memantine) On protein expression levels. This evaluation offers a deep understanding of how these
factors are Associative learning and the potential therapeutic benefits of memantine and trisomic mice.

Model used: After comparison of four different models through accuracy score, F score and recall, we
selected random forest classifier.

The top five proteins acquired from analysis: 1. CaNA_N , 2. pPKCG_N , 3. Ubiquitin_N , 4. ARC_N , 5.
Tau_N
