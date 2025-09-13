Phishing remains one of the most persistent cybersecurity threats, exploiting human vulnerabilities 
and technical weaknesses to compromise sensitive information. Conventional detection methods, 
such as rule-based systems and blacklists, are reactive and limited in their ability to address the 
evolving sophistication of phishing attacks. This report investigates the application of predictive 
analytics and machine learning for the proactive detection of phishing websites, focusing on technical 
indicators including URL structure, SSL certificate status, domain registration details, and web traffic 
measures. 
A range of machine learning and deep learning algorithms were implemented and evaluated, 
including Logistic Regression, Support Vector Machines, Decision Trees, Random Forest, Extra 
Trees, XGBoost, Multilayer Perceptron (MLP), k-Nearest Neighbors, and AdaBoost. The 
comparative analysis demonstrates that ensemble and deep learning models consistently outperform 
linear classifiers. Notably, XGBoost, Random Forest, Extra Trees, and MLP achieved superior 
predictive performance, with accuracies of approximately 97% across cross-validation folds. Feature 
importance analysis revealed that factors such as suspicious anchor links, insecure or absent SSL 
certificates, domain name irregularities, and the use of multiple subdomains were highly predictive 
of phishing activity. 
To enhance transparency, model-agnostic interpretability techniques, namely SHAP and LIME, were 
integrated into the evaluation. These methods provided both global insights into overall feature 
significance and local explanations for individual predictions. The incorporation of interpretability 
ensures that the models are not perceived as “black boxes” but instead offer explainable and 
trustworthy outputs, facilitating adoption in high-stakes organizational settings and supporting 
regulatory compliance. 
The study concludes that predictive analytics, when combined with interpretability, provides a robust 
and scalable framework for phishing detection. It is recommended that organizations adopt ensemble
based models, implement regular retraining with updated datasets, and leverage explainable 
dashboards to support both cybersecurity professionals and non-technical users. This approach 
demonstrates strong potential for practical deployment and contributes to enhancing resilience against 
phishing threats. 
Keywords: Phishing detection, machine learning, predictive analytics, cybersecurity, explainable AI, 
SHAP, LIME
