# Diabetes-Data-Analysis
*According to WHO, Diabetes is a chronic disease that occurs either when the pancreas does not produce enough insulin or when the body cannot effectively use the insulin it produces. Insulin is a hormone that regulates blood sugar. Hyperglycaemia, or raised blood sugar, is a common effect of uncontrolled diabetes and over time leads to serious damage to many of the body's systems, especially the nerves and blood vessels.*
* *Over time, diabetes can damage the heart, blood vessels, eyes, kidneys, and nerves.*
* *Adults with diabetes have a two- to three-fold increased risk of heart attacks and strokes.*
* *Combined with reduced blood flow, neuropathy (nerve damage) in the feet increases the chance of foot ulcers, infection, and the eventual need for limb amputation.*
* *Diabetic retinopathy is an important cause of blindness and occurs as a result of long-term accumulated damage to the small blood vessels in the retina. Diabetes is the cause of 2.6% of global blindness.*
* *Diabetes is among the leading causes of kidney failure.*

Here,
* Functioned on Diabetes dataset available on Kaggle - https://www.kaggle.com/vikasukani/diabetes-data-set
* Visualized the data samples with positive and negative outcomes. Also, discerned the plot with relative features. We can make out that attributes like Glucose, BMI, DiabetesPedigreeFunction, and Age have much effect on Outcome as compared to other attributes.
* Eliminated duplicate values from the dataset, scaled training data after splitting the dependent and independent variable, and trained a Logistic regression model.
* Assessed result and saw confusion matrix, training score as 0.76, testing score as 0.31, and accuracy 31%.
* As the accuracy is low added interaction variables to the training data and testing data and trained and tested the model.
* Evaluated the results for the model with interaction variable and observed confusion matrix, training score as 0.79, testing score as 0.46, and accuracy as 46% for the modified data.
* In this case, the interaction effect has increased the accuracy of the model by 15%, and hence an enhanced model is observed. Also, pictured the model coefficient to view contribution by each variable.
