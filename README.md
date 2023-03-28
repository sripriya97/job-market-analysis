# Job Market Analysis

<h2>Data Generation - Web Scraping </h2>
</br>
For this project my team and I scrapped job postings available on LinekedIn and Glassdoor for three roles - Data Scientist, Data Analyst and Business Analyst
Using web scraping techniques, we have collected information on job titles, companies,locations, job descriptions, and additional details like required skills, education, years of experience, salary estimates, seniority level, employment type, job function, and industries. All of this information is stored in a NoSQL database, which is better suited for handling unstructured data and allows for more flexible and scalable data models.
</br>
<h2>EDA and Model Fitting</h2>
</br>
We performed some exploratory data analysis using excel to identify the most frequently sought after skills in these job postings and then went ahead and created some plots to identify the overlap between these three roles.
</br>
For the model fitting part we started from a basic Logistic Regression and went on to more complex models like Neural Networks. These models took the various skills as inputs and attempted to classify the job role as the output.
</br>
We fit the data to the following models - Logistic Regression, Ridge Regression, Lasso Regression, Lasso with CV, k-NN Classification,  SVM Classifier, Classification Tree, Random Forest, Neural Network
</br>
The aim of this model fitting was to be able to identify the most significant skills for each job class.
