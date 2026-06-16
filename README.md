# Credit-Risk-Classification-Using-KNIME
Developed a credit risk classification model in KNIME by comparing multiple machine learning algorithms and evaluating model performance on unseen data.

Overview

I completed this project as part of my Data Mining & Predictive Analytics course to learn more about how machine learning can be used to support lending and credit approval decisions. The goal was to predict whether a loan applicant would be classified as a good or bad credit risk based on information such as their financial situation, employment status, and other personal factors. This project gave me the opportunity to work through the entire machine learning process, from preparing the data to comparing different models and evaluating their results.

What I Did

I started by preparing the German Credit Risk dataset from the UCI Machine Learning Repository. Since a large portion of the dataset contained categorical variables, I first converted them into dummy variables so they could be used in machine learning models. After that, I used Principal Component Analysis (PCA) to reduce the number of variables and simplify the dataset while still keeping most of the useful information.

Once the data was ready, I built and compared three different machine learning models in KNIME: Logistic Regression, Decision Tree, and Neural Network. I split the data into training and testing sets, trained each model, and compared their performance using confusion matrices and other evaluation metrics. After reviewing the results, I selected the Decision Tree model because it performed well and was easy to interpret, which is especially important in situations where lending decisions need to be explained and justified.

Skills Used

Through this project, I got hands-on experience working with machine learning in KNIME and learned a lot about the steps that happen before a model is ever built. I worked with data preparation, dummy variable creation, dimensionality reduction using PCA, and classification modeling. I also built and compared Logistic Regression, Decision Tree, and Neural Network models to see how different approaches performed on the same dataset. Along the way, I became more comfortable evaluating model performance using confusion matrices and classification metrics, while also learning that accuracy alone does not always tell the full story. This project helped me better understand how machine learning can be applied to real business problems and the trade-offs involved when choosing between different models.

Key Findings

After comparing all three models, the Decision Tree provided the best balance between performance and interpretability. While the model was very effective at identifying reliable borrowers, it had more difficulty identifying higher-risk applicants, which highlighted the challenges that come with imbalanced datasets. One of the biggest takeaways from this project was learning that a model can have strong overall accuracy while still struggling with the outcomes that matter most from a business perspective.

What I Learned

This project helped me move beyond simply building machine learning models and focus more on understanding their results. I learned how important data preparation is, how different models can approach the same problem in different ways, and why business context matters when evaluating model performance. Working through this project gave me a much better understanding of how machine learning can be used to support decision-making and manage risk in real-world situations.
