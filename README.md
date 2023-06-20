# End-to-End : Job Market Analysis

<h2>Data Generation - Web Scraping </h2>
</br>
For this project job postings available on LinkedIn and Glassdoor were scrapped for three roles - Data Scientist, Data Analyst and Business Analyst
Using web scraping techniques, information on job titles, companies,locations, job descriptions, and additional details like required skills, education, years of experience, salary estimates, seniority level, employment type, job function, and industries was collected. All of this information is stored in a NoSQL database, which is better suited for handling unstructured data and allows for more flexible and scalable data models.
</br>
<h2>EDA and Model Fitting</h2>
</br>
Some exploratory data analysis was performed using excel to identify the most frequently sought after skills in these job postings and then some plots were created to identify the overlap between these three roles.
</br>
For the model fitting part first basic Logistic Regression was done followed by more complex models like Neural Networks. These models took the various skills as inputs and attempted to classify the job role as the output.
</br>
The data was fit to the following models - Logistic Regression, Ridge Regression, Lasso Regression, Lasso with CV, k-NN Classification,  SVM Classifier, Classification Tree, Random Forest, Neural Network
</br>
The aim of this model fitting was to be able to identify the most significant skills for each job class.
