# ML Algorithm Comparison on 'Diabetes Dataset with Notes'

Submission to Machine Learning Algorithms module for MSc AI @ UWE

## Contents
The notebook addresses a range of research questions, though the overarching theme is a **comparison between tree-based and linear-based ML models**. 

The analysis contains statistical tests to determine significance between base models and fine-tuned/engineered models (hyperparameter fine-tuning, data balancing, feature engineering), and an overall comparison of all methods split by overall model type.

The chosen dataset included a `notes` feature and was chosen to explore NLP techniques.   

## Main Finding
Model type (tree vs linear) comparisons showed statistically significant differences, while the engineering comparisons did not. This may be a result of the synthetic data used being generated with usability in mind, or perhaps that the models are powerful out of the box.

### Caveats
The main constraint was that the entire project should be contained within a single notebook without supporting `.py` files. Consequently, the notebook is quite long. One item of feedback was that the confusion matrices should have been side-by-side to aid comparison, which certainly would have improved the layout. 
